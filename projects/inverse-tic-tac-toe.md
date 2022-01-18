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
  <img class="ui medium left floated image" src="../images/tictac2.png" />
</div>

Inverse Tic Tac Toe has opposite rules from the regular Tic Tac Toe game. The goal is to make your opponent get three in a row. If you get three in a row, you lose. This was my final project for ICS 111, where we learned the basics of Java. The hardest part of this project was getting the icons to spawn where the mouse clicked because I had to get the correct x and y positions. On top of that, drawing the shapes for the icons and the board was also a challenge. Although I had prior experience with Java, I never had to draw or create a mini game before. I learned how to use different mouse events, such as mousePressed and mouseReleased. ICS 111 taught me a lot about mouse listeners, JPanels, paint component, etc. 

Although it was an individual learning experience, I had some help from classmates and peers in understanding how to use the different components of draw, color, panels, etc. I developed more skills in Java and learned many things I did not know you could do in Eclipse before. The experience I gained through this project was extraordinary and even though not every part of the code works perfectly, it was a great challenge. 

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

Source: <a href = "https://github.com/Cknakano/InverseTicTacToe"><i class="large github icon"></i>Cknakano/InverseTicTacToe</a>.



