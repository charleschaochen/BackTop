BackTop
=======

Create back to top icon in page easily and rapidly.

Usage steps:

1. Put backtop.gif, rocket.png under images direcotry

2.. Include Jquery and BackTop script:
  <script type="text/javascript" src="scripts/jquery-1.9.1.js"></script>
  <script type="text/javascript" src="scripts/backTop.js"></script>


3. Call createBackTop in the page

  <script type="text/javascript">
      $(function () {
          // Create back to top icon
          backTop.createBackTop();
      });
  </script>
  
Parameters:
backTop.createBackTop({
  bottom: "50px", // The bottom of the icon, default 50px
  right: "200px", // The right of the icon, default 40px
  style: 0  // The icon style, values: 0, 1, 2, default 0 
});

  
There are three style of icon can be used:
0: Simple style, no image needed
1: Arrow style, needs image “backtop.gif”
2：Rocket style, needs image "rocket.png"
