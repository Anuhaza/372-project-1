# Minesweeper CSC 372
This README is for the application/GUI portion of the project.
# Description
This program is a Minesweeper game where the player gets to play Minesweeper on different difficulty levels, ranging from easy to hard.
The harder the game, the less time the player has and the larger the grid is. The rules are similar to classic Minesweeper, where the player
has the choice of revealing or flagging a cell based on hints about nearby mines and can win or lose depending on whether mines were revealed
at all in the game.
# Running the Code
The code can be run on IntelliJ IDEA, a software for running Kotlin code. When starting a new project, the language should be toggled to Kotlin and
after pressing create, at the top of the code "package com.example.project_name" should be put. The "project_name" depends on what you name the project
on IntelliJ. It should start running the application then and the user is then able to choose the difficulty level and play the game. 

For testing, once the code is imported, there might be a few errors that show up because of junit being an "unsolved reference." To solve this, hover over
the error and click on "Add JUnit4 to classpath". You can also do Alt+Shift+Enter. Then, hover over one of the red underlined portions of the code, 
such as "@Test", and click on "Add 'requires junit' directive to module-info.java" or press Alt+Shift+Enter. The tests should be able to run after.
# Test Code
The test code tests the foundation of the Minesweeper grid. It tests whether a particular cell does get flagged, correctly returns whether it has a mine or not,
whether it has been revealed by a user or not, and whether the game is over or not.
