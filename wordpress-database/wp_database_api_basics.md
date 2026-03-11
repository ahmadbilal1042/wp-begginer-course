we can use functions defined in wordpress code refrence to interact with database

insert
update
delete
usually have same prefix wp_
sysntax
wp_{action_name}_{table_name}


for example for adding a new post

wp_insert_post
wp_update_post
wp_delete_post

functions to fetch data

use the prefix "get_" followed by table name or names

like get_posts
get_post

function to interact with metadata

format 
{action}_{table_name}_meta

add_post_meta
update_post_meta


moreover, 

wp_terms
wp_termmeta
wp_term_relationships
wp_term_taxonomy

these all belongs to tags and categories
