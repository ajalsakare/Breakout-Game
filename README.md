# Breakout-Game

At some point in your life you must have played this game atleast once, here I have tried to create that same experience using Python and Turtle module.<br>

I have created this game using the concept of OOPS so for each component in the game(paddle, ball, colorful bricks, score) I have created different classes and their objects ( I
have created different files for each class beacuse that makes it quick and easy to understand but you can combine it into one), all the classes I have created(Paddle, Ball, 
Boxes, Score) inherits Turtle class because that's what we are using to create this game, let me explain to you what each component or file does :

<ul>

  <li>  <b>Screen</b> : First of all I created the main window by instantiating Screen class, and then I set the attributes such as screen size, window title. </li> <br>

  <li>  <b>paddle.py</b> : This file contains the <b>Paddle</b> class which creates the paddle to play with ball, I have added listener events in the main program and two methods 
  <b>move_left()</b> and <b>move_right()</b> calling which paddle can be moved to right or left using the right-left arrow keys.  </li> <br>

  <li>  <b>ball.py</b> : This file contains the Ball class, which is the must required to play this game. This class contains different methods such as <b>refresh()</b> which 
  moves the ball through the screen, <b>bouncex()</b> which reverses the x-coordinate of the ball so it bounces back after hitting on sidewall, <b>bouncey()</b> which reverses the 
  y-coordinate of the ball so it bounces back after hitting upper side or the paddle, and the <b>restart()</b> method which takes the ball to center after player has missed the ball.
  </li> <br>
  
  <li> <b>boxes.py</b> : Creates boxes with random colors, nothing more than that.</li> <br>
  
  <li> <b>score.py</b> : This class is used to display the total no of boxes hit by the ball and the final score which is displayed after player has hit all the boxes and also
  how many times he missed the ball.</li> <br>
  
  <li> <b>main.py</b> : Here all the classes are imported and instantiated, and using the <b>Box</b> class it creates nearly 50-100 random boxes, the game runs when the while
  loop starts which loops until all the boxes aren't hit and then displays the final message.</li> <br>

</ul>

Feel free to play with this and I am open to any feedback you have.
