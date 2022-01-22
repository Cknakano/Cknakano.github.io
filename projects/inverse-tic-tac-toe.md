---
layout: project
type: project
image: images/tictactoepic.png
title: Inverse Tic Tac Toe
permalink: projects/inversetictactoe
# All dates must be YYYY-MM-DD format!
date: 2020-12-04
labels:
  - Eclipse IDE
  - Java
summary: An Inverse Tic Tac Toe game I created for my ICS 111 Final Project.
---

<div class="center">
  <img class="ui small left floated image" src="../images/tictac2.png" />
</div>

Inverse Tic Tac Toe has opposite rules from the regular Tic Tac Toe game. The goal is to make your opponent get three in a row. If you get three in a row, you lose. This was my final project for ICS 111, where we learned the basics of Java. The hardest part of this project was getting the icons to spawn where the mouse clicked because I had to get the correct x and y positions. On top of that, drawing the shapes for the icons and the board was also a challenge. Although I had prior experience with Java, I never had to draw or create a mini game before. I learned how to use different mouse events, such as mousePressed and mouseReleased. ICS 111 taught me a lot about mouse listeners, JPanels, paint component, etc. 

Although it was an individual learning experience, I had some help from classmates and peers in understanding how to use the different components of draw, color, panels, etc. I developed more skills in Java and learned many things I did not know you could do in Eclipse before. The experience I gained through this project was extraordinary and even though not every part of the code works perfectly, it was a great challenge. Figuring out how to get the computer to play and make optimal choices was enjoyable.

Here is some code that illustrates how it reads where the mouse is clicked and draws the corresponding icon:

```java
public void mouseClicked(MouseEvent e) {
      int xPos = e.getX()*3 / getWidth();
      int yPos = e.getY()*3 / getHeight();
      int pos = xPos + 3*yPos;
      if (pos>=0 && pos<9 && position[pos]==BLANK) {
        position[pos]=O;
        repaint();
        // Computer plays
        putX();  
        repaint();
      }
    }
```
Through this project, I got to learn some features that I would learn the following semester and I did some self-studying. Not all the resources and code we needed were provided or taught to us. We went over mouse events in class but not in depth or detail, so many aspects of tic tac toe, I had to figure what needs to happen in different mouse events. I also had to figure out the positioning and it was mostly trial and error. I had to find how to relate the x and y position within each other in the formulas and make sure that the icons were all centered. This class also introduced me to different IDEs and editors that I could use in the future. One thing I failed at on this project was creating a shape that was not a square. I wanted to make a diamond but I could not figure out how to draw the diamond or rotate the square to make a diamond. Therefore, the only way to differentiate between the player and the computer, is through the colors. 


Source: <a href = "https://github.com/Cknakano/InverseTicTacToe"><i class="large github icon"></i>Cknakano/InverseTicTacToe</a>.



