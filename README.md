# brix-arduino
BRIX is a Arduino based game targeting young children, helping them acquire and improve basic counting skills.
The goal of the game is to successfully count, identify and declare the exact number of squares on a card within 
the given time frame. The smart game-board enables real-time feedback for the child and progress reports for the 
parent via Android phone app. BRIX main differentiation element are the playing cards. The cards visualize numbers 
in a non-traditional way based on the Polyomino system allowing a variety of geometric figures formed per each 
number, in a “Tetris” like form. This forces the player to always count since the multiple representation per each 
number are almost impossible to memorize.

How does it work?
RFID tags are attached to the playing cards, and then read by the Arduino based board to recognize the number that the card represents. 
Once the child places a card on the board a LED timer starts counting. The child counts the number of squares on the card, clicks on the 
corresponding button, and gets a visual and audio indication according to the correctness of his answer. Timing and accuracy calculations 
are performed in the background and are sent in real-time to a mobile application on the parents’ device.

