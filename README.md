# Coding Dojo Bootcamp Assignment  
## Web Fundamentals / CSS / Plotting Your Blocks  

### Submitted Files
```
plottingyourblocks.html
plottingyourblocks.css
```

### Assignment details  
Try to duplicate the image below by adjusting the CSS code provided. Use margins and paddings to adjust the spaces between divisions and use the display property to be able to put each block in its proper place. You may need additional CSS properties.  
Here's the HTML code:
```
<!DOCTYPE html>
<html lang="en">
   <head>
      <title>Position Practice</title>
      <link rel="stylesheet" type="text/css" href="style.css">
   </head>
   <body>
       <div id="wrapper">
         <div id="header"></div>
         <div id="navigation"></div>
         <div id="main_content">
            <div class="subcontents"></div>
            <div class="subcontents"></div>
            <div class="subcontents"></div>
            <div id="advertisement"></div>
         </div>
      </div><!-- end of wrapper -->
   </body>
</html>
```

And CSS:
```
/*CSS reset settings here*/
*{
 margin: 0px;
 padding: 0px;
}
#wrapper{
 width: 950px;
 background-color: silver;
 margin: 0px auto;
}
#header{
 height: 150px;
 background-color: green;
}
#navigation{
 height: 300px;
 width: 200px;
 background-color: blue;
}
#main_content{
 height: 400px;
 width: 700px;
 background-color: red;
}
.subcontents{
 height: 200px;
 width: 210px;
 background-color: yellow;
}
#advertisement{
 height: 120px;
 width: 660px;
 background-color: purple;
}
```



