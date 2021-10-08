# Bootstrap 4 Pagination for WordPress

Bootstrap 4 Pagination for WordPress
(Bootstrap 5 supported)

## Getting Started

Include this file in your functions.php
```
include_once('wordpress-bootstrap-4-pagination.php');
```

Function to use
```
if ( have_posts() ) : 
    while ( have_posts() ) : the_post(); 
        // Display post content
    endwhile; 
    wp_boostrap_4_pagination();
endif; 
wp_reset_postdata();