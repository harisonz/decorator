Decorator Front-End Framework
==========

Decorator, an easy to implement and use component based front-end framework for creating web and mobile supported applications. 
Decorator is based on HTML, CSS and Javascript. It includes lot's of ready to use pre-built components. 

How To:
-------

Step one is to include the main decorator.css file into your projects file head section. If you want to use ttf or spire icons you need to include those css files as well and those need to be included right below the main decorator.css file. Next step is to create a theme.css file and include that one below all of the main decorator files, you can now make all your changes in theme.css file.

Responsive Design:
------------------

After you've included the main decorator.css file it's easy to make your layout responsive, all you have to do is add "fluid" class to your layouts body tag. Your layout is now responsive. However, if you want your navbar to act as a responsive menu; then you have to follow few more steps: Step one is to include the jquery into your footer section right above where "body" tag ends. After that's done include dc.menu.js file that comes with decorator js plugins right below jquery. You can now call your navbar selector and add responsive menu to it by adding few more lines of code like in example shown below:

```javascript
<script type='text/javascript'>

$(document).ready(function(){
    $('.navbar').dcMenu();
});
  	
</script>
  	
````
Examples:
----------
Few examples included to get you started. Click on thumbnails to view live demo.

| Thumbnail     | Description       | Link       
| ------------- |:-------------:|:-----:|
| <a class="link" href="http://codable.org/templates/one/" target="_blank"><img src="http://decorator.codable.org/img/examples/one.jpg" width="180"></a>    | One Column Responsive Layout |<a class="grid-title" href="http://codable.org/templates/one/" target="_blank">View Example</a></p> |
| <a class="link" href="http://codable.org/templates/two/" target="_blank"><img src="http://decorator.codable.org/img/examples/two.jpg" width="180"></a>    | Two Column Responsive Layout |<a class="grid-title" href="http://codable.org/templates/two/" target="_blank">View Example</a></p> |
| <a class="link" href="http://codable.org/templates/three/" target="_blank"><img src="http://decorator.codable.org/img/examples/three.jpg" width="180"></a>    | Three Column Responsive Layout |<a class="grid-title" href="http://codable.org/templates/three/" target="_blank">View Example</a></p> |
| <a class="link" href="http://codable.org/templates/grids/" target="_blank"><img src="http://decorator.codable.org/img/examples/grids.jpg" width="180"></a>    | Responsive Grids Layout |<a class="grid-title" href="http://codable.org/templates/grids/" target="_blank">View Example</a></p> |
| <a class="link" href="http://codable.org/templates/admin/" target="_blank"><img src="http://decorator.codable.org/img/examples/admin.jpg" width="180"></a>    | Responsive Admin Layout |<a class="grid-title" href="http://codable.org/templates/admin/" target="_blank">View Example</a></p> |


What's Next?
------------
I'm currently working on angular js components as well as on a new extensive and responsive documentation website.
Please stay tuned by following the project here on github. 


For more info and examples please check out: [Decorator Dox](http://decorator.codable.org) 
