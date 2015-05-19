12 Grid Responsive Framework
==============
Although i love to use bootstrap, I found that sometimes i needed something simpler and lighter when working on a project. I developed this framework for times when you don't need all the bells and whistles, just an easy way to make sure your webpage displays well across all devices. This framework breaks the page into twelve columns when the screen size is above 640px. When screen size is less than 640px all boxes are stretched across the whole screen.

![Screenshot](http://www.dominikdev.com/resources/github/screenshots/responsivefw.png "Screenshot")

View Project Page: [12 Grid Responsive Framework](http://bit.ly/responsivegrid)

Instructions
--------------

- Clone this project or download CSS File [Here](http://bit.ly/responsivegrid)
```
responsive_twelve_grid.css
````
- Add Link Reference in File
```HTML
<link href="path-To-File/responsive_twelve_grid.css" rel="stylesheet" type="text/css" />
```

How To Format HTML
--------------
1. Wrap Page in Container.
2. Wrap Each Row in div with class of "row".
3. Each column has class of "box-wrapper" plus class of how many grids it will stretch across.
```
     - "box-wrapper bw-1"
     - "box-wrapper bw-2"
     - "box-wrapper bw-3"
     - "box-wrapper bw-4"
     - "box-wrapper bw-5"
     - "box-wrapper bw-6"
     - "box-wrapper bw-7"
     - "box-wrapper bw-8"
     - "box-wrapper bw-9"
     - "box-wrapper bw-10"
     - "box-wrapper bw-11"
     - "box-wrapper bw-12"
```
**Example**

```HTML
<div class="container">
     <div class="row">
           <div class="box-wrapper bw-12">
                  <span>CONTENT</span>
           </div>
     </div>
     <div class="row">
           <div class="box-wrapper bw-6">
                  <span>CONTENT</span>
           </div>
           <div class="box-wrapper bw-6">
                  <span>CONTENT</span>
           </div>
     </div>
</div>
```
*To position "box-wrapper" on opposite side of page add class of "opp" as well*

License
--------------
Free to use in any project. Attribution is appreciated, but not neccessary. Enjoy!