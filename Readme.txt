https://henryzhu123.github.io/GUI1-Assignment9/

Implemented features:

    Fully Working:
        Basic Functionality:
            Letter tiles in player's hand are selected randomly from a data structure with the proper distribution of letters - implemented using a modified version of the associative array provided by professor Heines
            Letter tiles can be dragged-and-dropped onto target Scrabble squares - Implemented using jQuery UI draggable and droppable features
            Program Identifies which letter tile is dropped onto which Scrabble square - Implemented via custom attributes and classes dynamically added and removed from letter and board tiles
            Board includes bonus squares - Implemented using special classes for bonus squares
            Score is tallied correctly, including consideration of bonus square miltipliers - Implemented in Javascript. Handles tracking score of the current word and the total score of the player. Current score updates dynamically.
        
        Additional Functionality:
            Any bumber of words can be played until the player wishes to quit - As long as the player doesn't run out of tiles in the bag, he can play as many words as he wants
            The board is cleared after each round so that a new word can be played - Implemented via draw new tiles button. Clears board and replaces played tiles with new tiles from the bag. The current score when button is clicked is added to the total score for the game.
            After playing a word, only the number of letter tiles needed to bring the player’s “hand” back to 7 tiles are selected - Implemented using a global vairable to track remaining tiles in the bag.
            Score is kept for multiple words - Any tiles that are on the board will count towards the current score. 

        Extra Credit:
            Multiple Scrabble board lines are implemented - Full board is implemented
            Full Scrabble board lines are implemented - Full  board is implemented

        Custom Functionality:
            Current Score updates dynamically - Implemented via calling calculate function any time a tile is moved. 
    Partially Working:

    Not Working: