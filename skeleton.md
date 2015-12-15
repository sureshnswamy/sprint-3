What happens to the layout when you resize the screen to less than 550 px. How do you think that works?

  1.When the screen is resized less than 550px the following changes takes place to the grid
  
  2.The main header wraps and centers. The images and their description all fit within single column (overflow)

  
  3.The nav bar disappears. 
    This is done with @media less than 750px and display:none 
  
  4.The 12x12-colum grid collapses in to one is a assending order. 
    This is done with @media less than 750px
  
  5.All the buttons lists in single column.
  
  6.The Table colum space reduces and fits withing screen still maintaining the table structure.

  7.The images resizes and the description positions beneath the images.
  
  8.Code snipptes are wraped using <pre><code>

  9. Fonts re-sizes to screen resolution.
    This is done with <rems>.