# Portfolio Website Template

Free website template built for professionals to market their skills and showcase their projects. 

Website features a responsive design, animated links and buttons, and responsive picture tiles and modal.

To view a live demo of this website, go to: http://waldronmatthew.com/portfolio/portfolio/index.html

## Features

* Animated buttons and social links
* Picture tiles
    * Responsive pictures
    * Even picture width and height
    * Centered picture text
    * Hover animations
    * Lightbox2 modal integration
* Auto-update copyright year
* CSS3 and HTML5 Compliant

Picture code block

'''
<div class="grid">
	<div class="grid_item two-center span" style="background-image:url('pictures/mnt1.jpg');">
        <a href="pictures/mnt1.jpg" class="grid_link" data-lightbox="p2" data-title="mnt1">
            <div class="tile"><p>2 pictures</p></div>
        </a>
    </div>
	<div class="grid_item two-center span" style="background-image:url('pictures/mnt2.jpg');">
        <a href="pictures/mnt2.jpg" class="grid_link" data-lightbox="p2" data-title="mnt2">
            <div class="tile"><p>2 pictures</p></div>
        </a>
    </div>
</div>
'''

Container for pictures
'''
class="grid"
'''

Picture layout

'''
class="grid_item two-center span"
'''

* grid_item - picture display and positioning
* span - picture width/responsiveness 
    * one-center - single picture width
    * two-center - two picture width
    * three-center - three picture width

Picture background image

'''
style="background-image:url('pictures/mnt1.jpg');
'''

Lightbox2 modal picture link and text container

'''
href="pictures/mnt1.jpg" class="grid_link"
'''

Lightbox2 modal image image set and image caption

'''
data-lightbox="p2" data-title="mnt1"
'''

Image text positioning, styling, and text
'''
class="tile", <p>2 pictures</p>
'''

## Built With

* HTML5
* CSS3
* jQuery/JavaScript

## Contributing

When contributing to this repository, you may fork and submit a pull request. Add a description of what you are doing and I'll review it.

## Versioning

Version 1.4.5

## Authors

* **Matthew Waldron** - (http://waldronmatthew.com)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

Please abide by the Terms of Use and Website Credits pages.

## Acknowledgments

A HUGE thank you to all developers whom I used MIT licensed code from. They are listed on the "Website Credits" page. 

