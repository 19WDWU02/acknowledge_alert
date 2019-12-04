# educational alert
This is a file which will show a pop up alerting the user that this is an educational use site. The users must check a box to acknowledge this and also can direct themselves to the real site if they would like.

### Installation
Download this file into your project and paste the following code into your functions.php. You may need to edit the line if you are putting it into a different folder.


```php
    require get_parent_theme_file_path('./addons/educational_alert.php');
```
Open the file and edit these three lines
```php
    $realSite = '';
    $realSiteURL = '';
    $designerName = '';
```
Put in your values for these variables.
