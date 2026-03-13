# 2 types of requests

# admin request 
# front end request

most of front end request are handled by index.php

in index.php WP_USE_THEMES contsant is setup and wp_blog_header is loaded to setup wordpress environment by requiring wp_load.php file

in wp_load ABSPath constant is defined

then require and include

# require includes the file which is being loaded similar syntax as # include in PHP 

simple difference is require throws an error if loaded file is not available

then load file loads wp-config.php

which includes all database contsants amd debuggings cinstants whhich included wp-settings.php

it has wordpress version and required files
calls different functions which are used in wordpress settings

# loads functions.php for theme and child theme if available

at the end wp_loaded function is called

