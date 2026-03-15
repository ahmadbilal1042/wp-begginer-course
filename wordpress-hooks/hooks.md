# Hooks

its fundamental of wordpress
makes wp so extendable
hook aloows to interact or modify a wordpress request by your theme and plugin

2 types of hooks

filter hooks and action hooks
 
# Working With Hooks

# Hook Priority
 how quickly it should register/perfomr any action
 if you want it quickes use 1, you want it late use 20 default value is 10

# Hook parameters

Specifiy the number of params in function


-Hook order


add_action('the_content', 'wp_learn_the_hook', 10(priority), 1(params));

function wp_learn_the_hook (params) {
    // Code Here
}

Learn More Hooks in WP Hooks in Codex