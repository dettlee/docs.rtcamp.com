---
title: rtp_hook_after_comment_author_avatar
---

### Description


This hook adds the content after author gravatar in comment section.


### Example



    
    function custom_rtp_hook_after_comment_author_avatar() { ?>
    <p>This is content after author gravatar.</p><?php
    }
    add_action( 'rtp_hook_after_comment_author_avatar', 'custom_rtp_hook_after_comment_author_avatar' );
