<h3>Arcade<h3>

Arcade is a gaming platform: a program that lets the user choose a game to play and keeps a register of player scores.

<p>
  The main feature of this project is to being able to change of game and/or graphic library anytime you want.
  Two games and three graphical libraries are already implemented.
  If you want to build your own just refer to the documentation (located in the doc folder)
</p>

<h2>Graphical libraries implemented:</h2>
<li>
  <ul>Ncurses.</ul>
  <ul>Allegro.</ul>
  <ul>SDL2.</ul>
 </li>

<h2>Game libraries implemented:</h2>
<li>
  <ul>Pacman (not working completly)</ul>
  <ul>Nibbler</ul>
  <ul>SolarFox</ul>
 </li>

<h3>Program compilation:</h3>
<p>
  <li>
    <ul>$ make -> Will commpile the entire project.</ul>
  <ul>$ make core -> Only compile the core of the program.</ul>
  <ul>$ make games -> Wil only compile the game libraries.</ul>
  <ul>$ make graphicals -> Will only compile the graphical libraries.</ul>
    </li>
  #All the lib_arcade_[NAME_OF_THE_LIB].so are located in the ./lib folder.

  #All the lib_arcade_[NAME_OF_THE_GAME].so are located in the ./games folder.

  The games and lib folder will be created at compile time and erase with the fclean rule.
</p>

<h3>Launch the Arcade</h3>
<p>
  $ ./arcade ./lib_arcade_[NAME_OF_THE_LIB].so
  The program need to be launch with a set graphical library of your choice.
  Don't worry if you don't really like it you can change it when your game is launch.
</p>

<h3>How to play:</h3>
<p>
  Up and down arrow key let you go through the different elements and the left and right key change the menu you're in.
  Once you've choose both your graphical and game library just press SPACE to start the game.
</p>

<h3>Global commands</h3>
<p>
  As i've said before, while you are playing, you can switch of game and graphical library whenever you want.
  To do so some keys are binded:
</p>
<li>
  <ul>Switch between graphicals libraries:</ul>
  <li>
    <ul> 'E': Previous graphical library.</ul>
    <ul> 'Z': Next graphical library.</ul>
  </li>
  <ul>Leaving the game and the program:</ul>
  <li>
    <ul> Press 'ESCAPE' (while in game): Return to the Selection Menu.</ul>
    <ul> 'Q' (while in game) or 'ESCAPE' (in the startup menu): Quit the program.</ul>
  </li>
</li>

<h3>Game command</h3>
<li>
  <ul>Arrow key: Move your character.</ul>
  <ul>'S': Restart your game.</ul>
  <ul>'SPACE': To pause the game.</ul>
  <ul>Switching game:</ul>
  <li>
  <ul>'A': Go to the previous game.</ul>
  <ul>'Z': Go to the next game.</ul>  
  </li>
</li>

<h3>Project realised by:</h3>
<li>
    <ul>Alexandre Sachs : alexandre.sachs@epitech.eu</ul>
    <ul>Thomas Bleneau : thomas.bleneau@epitech.eu</ul>
    <ul>Antoine Pelletant : antoine.pelletant@epitech.eu</ul>
  </li>

<p>
  One of the goal of the project was to be able to load libraries, whom had been coded by an other group of student.
  To do so we've worked with:
  <li>
    <ul>Kellian Cipierre : kellian.cipierre@epitech.eu</ul>
    <ul>Martin Cotoni : martin.cotoni@epitech.eu</ul>
    <ul>Thomas Lombard : thomas.lombard@epitech.eu</ul>
  </li>
</p>
