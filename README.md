# Whack-A-Groundhog1
Groundhog Whack Game is a classic entertaining game written in C language that will help players enhance their reaction. Players shall try their best to hit the groundhogs with the hammer as many times as possible. The specifications and instructions of the game are shown as follows:

* The main content of the game is displayed on the 320 x 240 pixels VGA screen.
* Countdown numbers and the number of hits per game are updated on the Seven-segment displays.
* The game starts as the player presses the compile, restart, and continue button.
* The game ends in 50 seconds or when the user presses on the 1st switch button.
  * “GAMEOVER” png will be shown on the VGA screen.
  * The score will still be displayed on the Seven-segment displays
* Groundhogs as rectangles appear from the bottom of the screen randomly after the game starts.
* At the beginning of the game, the green hammer stays on the top left corner of the screen. After any moves, its color changes to pink.
* Speed of the groundhogs can be adjusted by toggling on the push button.
  * Fast mode: all push button shall be unselected
  * Moderate mode: click the 2nd push button 
  * Slow mode: click the 3rd push button
* Groundhogs can be frozen by the player when the 1st push button is turned ON.
* User can move the hammer around by clicking the keys on the keyboard:
  * Left: A-key
  * Right: D-key
  * Down: Enter-key
* As the hammer strikes on the groundhog:
  * The groundhog turns from yellow to red and back to yellow.
  * The hammer returns to its starting location on the top left corner of the screen.
  * The score will be incremented on the seven-segment displays.
<img width="602" alt="Screen Shot 2021-05-01 at 6 43 49 PM" src="https://user-images.githubusercontent.com/56233967/116796767-2f073e00-aaad-11eb-86cb-4fb8db0de43a.png">

<img width="599" alt="Screen Shot 2021-05-01 at 6 44 12 PM" src="https://user-images.githubusercontent.com/56233967/116796772-39c1d300-aaad-11eb-91e2-0ad6ea35713b.png">
## Code can be compiled in CPULator
https://cpulator.01xz.net/?sys=arm-de1soc
