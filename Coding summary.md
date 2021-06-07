

                                        CODING SUMMARY

​                                                                C-1 Object - Oriented Programming

Coding needs to be easily understandable and readable. A good programmer always adds comments for this reason. In this programming style, we write code as if everything in the programming world were an object - just like in the real world. Each object has some properties and functions. Here class is also called as 'blueprint'.This blueprint has two main types that is 

PROPERTIES are the qualities/characteristics of the object. 

FUNCTIONS are actions that the object can do. They define the behaviour of an object.

A programmer creating a paddle object would first make the design and assign all the properties and functions of the object to it. Based on this design, the programmer will create as many paddle objects as he/she wants in the game.

  The design is called a 'CLASS' in programming.

​                                                                                C-2 Sprite Objects       

In this SPRITE means that how to create object in the canvas. For creating the object in the canvas  " var sprite = createSprite(200,200,10,10);''.

var = variable

sprite = object name

createSprite = creating object 

And the numbers for position & size of the object. The first no. is for X position that is left to right position. When the no. reduces from 200 the object moves the left side. if bigger than 200 moves to right side. The second no. is for Y position that is top to bottom. When the no. reduces from 200 the object moves the top side. When the no. bigger from 200 the object moves the bottom side. If we should see the object we use the command as " drawSprites() ".Because of this we can see object in the canvas. This command should be done at last.          

​                                                                       C-3 Conditional Programing

In this we learned about how to control the object. For eg. design a ping pong game in that player,computer & ball should move,for that we use ' if ' command for player & computer . For ball we use createEdgeSprites & bounceOff. ' if ' command is used because by keyDown(RIGHT_ARROW or any keys)."keyDown" that is used control the object movements. In 'if' command we also "isTouching". For "isTouching" command we use 'or' as symbol (||). This is used for when ball is touching the palyer the ball bounce back from the player then again it touches the computer so that we use these two commands "isTouching", (||)

​                                                                 C-4 Designing a Ping Pong Game

In this we learned about velocity. There are velocityX & velocityY. VelocityX is to moves the object horizontally. VelocityY is to moves the object in vertically. Here "World.mouseY" this command is used for playerPaddle. When the mouse moves the playerPaddle also moves vertically because direction given has mouseY so the playerPaddle moves vertically. Also computerPaddle follows where the ball goes but it moves only vertical direction.

​                                                            C-5 Functions & Loops             

In this, we have a principle D-R-Y : Don't Repeat Yourself. In that ping pong game there was dotted lines in center of canvas. The dotted lines have been  continuously seen. For this we use the command "line(x1,y1,x2,y2)". But this not done continuously repeating the command "line(x1,y1,x2,y2)",for this we use "for" loop. This helps to not doing the repeating  this command continuously "line()". 

​                                                                        C-6 Game State  

In a game, there is a change of state, for example, Start, Play, and End. Here there three game state. They are

SERVE STATE :                                                                                                                                                                                                                         The first state (Serve state) is when the ball is at the center and the user needs to press "Space" to serve the ball.                                                                                                                                                                                          

PLAY STATE :                                                                                                                                                                                                    The second state  (Play state) is when the play starts, and the ball is in motion. Specific instruction: If the user presses space and the game is in SERVE state, then serve the ball.

GAME OVER STATE :                                                                                                                                                                 'When the ball crosses the screen' the game over state changes to serve state.

**===** (Triple equals) is a strict equality comparison operator in which returns false for the values which are not of a similar type.

​                                                                  C-7 Animation & Sound                                                                                                                                     The instruction "playSound()" gives an option to choose the sounds. You can choose the sounds from the library or upload a file or a recording. To hear the sound continuously mp3 there two potion true & false. "True" is to hear the sound continuously and "false" is to hear the sound the once. If an object needs an image we use the command "setAnimation". If you want search for the below the project there is two option - code & animation. In animation from uploads we can see many objects. From that we can select the image. For e.g. "ball.setAnimation = ball;" here we can see that ball image instead the shape.                                                                                    

​                                                Capstone Class C-8 World's Hardest Game        

​                                                                     

​                                

