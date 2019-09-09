## Robots vs Monsters 

![alt text](https://raw.githubusercontent.com/LABCAT/robots-vs-monsters/master/preview.jpg)

My final submission represents a battle for the earth between robots and monsters. There is a scoreboard in the bottom left hand corner displaying the current score. 
You can even influence the result by using your center (monster) and right (robot) buttons to help out your favourite side. 

### Project Summary

In the first stage of the assignment I created two portraits of cartoon robots.  My aim was to replicate them as closely as possible and managed to achieve this very well. I have continued to use the robot theme throughout the rest of the project.

In the drawing styles section of the assignment I choose to draw a bear, a robot and a monster.  The bear was inspired by various cartoon bears but for the robot and monster I was aiming to create original characters.  The monster is completely original however the robot still contains a heavy influence from the one of the robots (Bender) i drew in part one.  

For the randomize part of the assignment I started with monsters first as I felt that was my strongest character.  It worked quite well but I decided that I wanted to use two characters and came up with the theme of "Robot vs Monsters". I didn't need to change the ranges of my parameters too much as they worked very well.  However I did need to reduce the scale of both faces so they weren't too big.

For the distribution part of the assignment my aim was to make the generated population more likely to consist of the traits that I liked the most.  One feature of this part that I am particularly happy with was the use of the focusedRandom function to influence the eye size of the monsters.  I used a variable mean value basic on the monsters size which makes its more likely for a bigger monster to have smaller eyes and vice versa for smaller monsters.

For the final part of the assignment was heavily influenced by some code that I had to write to ensure loading performance was still acceptable. Drawing the monster face is quite a heavy process and I wanted to have a lot more faces on the canvas. To accomplish this I had to implement some code that outputs several faces at a time rather than all of them.  

The result was very interesting and inspired the idea that the composition could also act as a game of sorts. So I added a scoreboard which keeps track of the number of robots and monsters on the canvas. The layout of the composition is actually a grid but the order in which the faces are drawn at the different co-ordinates is totally random.  I think this makes the display process much more interesting than simply drawing them from left to right and top to bottom. 
