# Ajay Kumar Dhonthoju
I am from Hyderabad. I was a software engineer worked across 4 different companies. I am a front end developer with my area of interest as Angular. I have worked with different versions of angular namely 4.0 , 8.0 and 13.0. I enjoy watching movies and meeting new friends.
![My Picture](IMG_1408_2.JPG)
***
# Countries Table

| Name of Country        | Reason for recommendation           | Days Spent  |
| ------------- |:-------------:| -----:|
| India      | There are many historic places to visit with abundance of cultural heridity | 60 |
| United States of America |   Great infrastructure with great monuments and structures    |   30 |
| Srilanka | If you love Nature then Srilanka will blow your mind with very good scenaries      |    7 |
| Switzerland | A beautiful country with lot of mountains and greenary      |    9 |

***
# Quotes
> People often say that motivation doesn't last. Well, neither does bathing that's why we recommend it daily.  — *Zig Ziglar*

> Luck is a dividend of sweat. The more you sweat, the luckier you get.  — *Ray Kroc*

> If hard work is the key to success, most people would rather pick the lock.  — *Claude McDonald*

***
# Code Fencing

> How to include jQuery in a WordPress theme?

> Include jQuery in WordPress Theme

> I am pretty new to WordPress and I am figuring out how to include jQuery into a theme.
I create the following function into functions.php theme:

[Link to the question on wordpress in stackoverflow](https://stackoverflow.com/questions/46595134/retrieving-and-display-images-by-tag-in-wordpress)

```php
function load_java_scripts() {
    // Load FlexSlider JavaScript that handle the SlideShow:
    wp_enqueue_script('jQuery-js', 'http://code.jquery.com/jquery.js', array(), '1.0', true);
}
add_action('wp_enqueue_scripts', 'load_java_scripts');
```
> Answer to the above question in CSS - Tricks

```php
if (!is_admin()) add_action("wp_enqueue_scripts", "my_jquery_enqueue", 11);
function my_jquery_enqueue() {
   wp_deregister_script('jquery');
   wp_register_script('jquery', "http" . ($_SERVER['SERVER_PORT'] == 443 ? "s" : "") . "://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js", false, null);
   wp_enqueue_script('jquery');
}
```
[Answer to the question in CSS tricks :  Include jQuery in WordPress Theme](https://css-tricks.com/snippets/wordpress/include-jquery-in-wordpress-theme/)

