# Filter Hooks

modify or filter specific data at any specifi point

commonly in a filter hook a variable is passed to that filter and chnages are passed to that variable

add_filter ('the_content','wp_learn_filter');

function wp_learn_filter ($content) {
    $content = $content . <?php 
    <p>This line is showing at end of page</p>
    php?>
}