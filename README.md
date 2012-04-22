Yii extension for [Foundation](http://foundation.zurb.com/ "Foundation")

Foundation is an easy to use, powerful, and flexible framework for building prototypes and production code on any kind of device.

[A Word about foundation](http://www.alistapart.com/articles/dive-into-responsive-prototyping-with-foundation/ "A List Apart")

## Demo
[Yii Foundation](http://foundation.oakwebdev.com/ "Yii Foundation")

## Setup instructions

1. Download the files and extract them to you project's desired folder
2. Add the following code to your application configuration:

```javascript
...
'preload'=>array(
    .....
    'foundation', // preload the foundation component
),
'components'=>array(
    .....
     // assuming you extracted foundation under extensions
    'foundation' => array("class" => "ext.foundation.components.Foundation"),
    
),
...
```

3. Start using it, check the documentation on using [forms](http://foundation.oakwebdev.com/index.php?r=site/forms "forms"), and [UI Components](http://foundation.oakwebdev.com/index.php?r=site/ui "UI Components")

> Info: This is a work in progress, not all components of foundation are to be found in the Yii extension yet. but you can still use them as you normally would use Foundation.

##Resources
 * [Forum Discussion](http://www.yiiframework.com/forum/index.php/topic/30716-extension-foundation/ "Forum Discussion") : for any questions or community support
 * [Project page](https://github.com/Asgaroth/foundation "Project page") : to fork and contribute
 * [Demo](http://foundation.oakwebdev.com/ "Demo")
 * [Foundation](http://foundation.zurb.com/ "Foundation")

##Changelog
###0.0.2 April 15, 2012
 
 - Added Breadcrumbs and Pagination

###0.0.1 April 10, 2012

 - Initial Release




