# Tic-Tac-Toe

**Access the game on** : https://royjaym.github.io/Tic-Tac-Toe/ 

**List of Features**
- Pick a marker, either ‘X’ or ‘O’
- The game will allow you to take turns between X and O
- Whilst playing, the game UI will show whose turn it is and will not allow a player to go twice
- In the message area at the bottom of the board, results of every round will be shown
- To the right of the board, a scoreboard reflects how many games, be it X or O has won
- There is an option to restart the game which will clear the board and to completely reset all the data a page refresh will be needed

**Technologies & Game Logic**
- Javascript - Kept all the global variables @ the top
             - used arrays to create winning combinations
             - used click event listenerss for most of the fnctionalities
             - for the tie function, compared whether X or Y had won and if all the squares were filled and if these two conditions were met
             - for most choices and the expected responses or results, if-else, conditional statements were put to use
- CSS - CSS was used to manipulate the cell divs to create the 9*9 board
      - Kept the design very simple and basic
      - definitely some room for improvement on the CSS responsiveness
      - an overlay functionality was implemented to aid to the sophistication
- HTML - kept the HTML simple
       - included a favicon as well as an image to improve the UI outlook
       
**Wireframe**

![image](https://github.com/RoyJayM/Tic-Tac-Toe/assets/97867989/d4ed8f94-5c5b-447c-b186-a0bd08050d89)



**User Interface**

![image](https://github.com/RoyJayM/Tic-Tac-Toe/assets/97867989/8e505d3e-f331-4e91-b7f6-6a40f137ef36)



**User Stories : Must Haves**
- As a user, I should be able to start a new tic tac toe game
- As a user, I should be able to click on a square to add X first and then O, and so on
- As a user, I should be shown a message after each turn for if I win, lose, tie or who's turn it is next
- As a user, I should not be able to click the same square twice
- As a user, I should be shown a message when I win, lose or tie
- As a user, I should not be able to continue playing once I win, lose, or tie
- As a user, I should be able to play the game again without refreshing the page

**Potential Extra Tic Tac Toe Features: Nice to haves**
- Keep track of multiple game rounds with a win, lose and tie counter
- Allow players to customize their tokens (X, O, name, picture, etc)
- Make your site fully responsive so that it is playable from a mobile phone
- Get inventive with your styling e.g. use hover effects or animations

**Wins**
- learnt a great deal of computational thinking
- learnt some new CSS functionalities like the overlay which I then implemented

**Hurdles**
- had a hard time figuring out how to get the TIE function to come together but eveerything eventually worked out

**Areas of Improvement**
- responsiveness of the game space on different screen sizes
- stable and more efficient way to apply JS
- allow for log in or sign in to the game
- allow for users to save their game history
- allow for users to have different allias names

**References**
- W3 Schools
- MDN web docs
- Stack overflow
- Udemy
