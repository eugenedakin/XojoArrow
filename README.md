# XojoArrow
 Create an arrow with an arrowhead in Xojo

This example creates an arrow that can be drawn on a Canvas and the starting position of the arrow has x and y coordinates called FromX and FromY. The end of the arrow is at the x and y coordinates ToX and ToY. Thickness of the arrow and arrowhead are changed in the AThickness parameter, and colour of the arrow and arrow head is in AColour.

To make this portable the method DrawArrow was created and an example of the code in the Paint event of the Canvas is:

Sub Paint(g As Graphics, areas() As REALbasic.Rect) Handles Paint
  //Draw an arrow
  //g is graphics, FromX and FromY are the starting coordinates of the arrow
  //ToX and ToY are the arrow end points
  //AThickness is the arrow thickness
  //AColour is the arrow colour
  DrawArrow(g,5, 5, 100, 100, 2, &c11CCDD)
End Sub

![](https://github.com/eugenedakin/XojoArrow/blob/master/ArrowDemo.png)

This was created with Xojo 2019 r1.1 on 17 Sept 2019
