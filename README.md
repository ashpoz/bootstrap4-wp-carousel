# bootstrap4-wp-carousel

Here is example code on how to integrate the Bootstrap 4 carousel into Wordpress using the ACF repeater field.

### Prerequisites

- Wordpress
- Bootstrap 4 integrated correctly in your theme
- ACF Pro Plugin

### Installing

1. Make sure Bootstrap 4 is integrated correctly in your Wordpress theme functions.php file
- See Step 5: https://www.lyrathemes.com/bootstrap-wordpress-theme-tutorial-1/

2. Install the ACF Pro Plugin in Wordpress if you haven't already

3. Create new ACF group or select preexisting ACF group
- make sure under Location, to select where you want this field group to appear, Page, Post etc.

4. Create a ACF Repeater Field
- In this example I called my repeater field 'carousel'

5. Create two ACF subfields for your ACF repeater field, one for your slide image and another for your slide text
- In this example they are 'carousel_image' and 'caption' respectively

6. Insert this code directly into the desired theme file or call it as a template part.
- https://developer.wordpress.org/reference/functions/get_template_part/


## Built With

* [Bootstrap 4](https://getbootstrap.com/docs/4.0/components/carousel/) - Bootstrap 4 carousel component used
* [Wordpress](https://codex.wordpress.org) 
* [ACF Pro](https://www.advancedcustomfields.com/add-ons/repeater-field/) - ACF Pro Plugin


## Authors

* **Adrian S. Haynes** - https://github.com/hellomaryjo


