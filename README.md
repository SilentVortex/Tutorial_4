# Tutorial_4
 
Today we are going to learn how to make 2D player movement with side movement and jumping.

THe Unity version I am using for this will be 2022.3.46f1.

The first thing we are going to do is to create the placeholder for our character, I am going to use a triangle for this. You can find it by right clicking the hierachy then 2D objects > Sprites > Triangle. Once that is done we then need to add our 2 components to it. In the inspector we now need to click the add component button and add a "Rigidbody 2D" component as well as a "Collider 2D" of your choice, I will use "Polygon Collider 2D" for my one. You should use the collider most suitable for your application. Once that is done you then need to make something for your floor. You can use a square, found in right click hierachy > 2D objects > Sprites > Square, to create your platform by simply stretching it out and then duplicating it with the keybind Left control + D. After that you can leave a gap in the middle so you can jump across. Both of your squares will need a Box Collider 2D in order to collide with the triangle. 


![image](https://github.com/user-attachments/assets/ddf2ec43-8219-42c7-a851-cd5690f83140)
