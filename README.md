This Python script is a word guessing game where players attempt to guess a secret weapon foundry from the video game Destiny 2, chosen from a predefined list of weapon foundries ("hakke", "omolon", "tex mechanica"). Here's a brief overview of how this game works and its key features:
Starting the Game: When the script is executed, the main() function is invoked, which orchestrates the gameplay.
Choosing the Secret Weapon foundry: The choose_word function selects a random word from the weapon_foundry_bank list to be the secret word that the players will guess.
Game Loop:
The game continues allowing letter guesses and optionally word guesses until the player either guesses the word correctly or uses up their three allowed word guesses.
Each turn, the player is first allowed to guess a letter in the secret word:
If the guessed letter is in the word, the number of times it appears is displayed.
The guessed letters are tracked and displayed each turn to help the player.
After guessing a letter, the player can choose to guess the entire word.
Scoring:
The player's score is the number of letter guesses made before successfully guessing the word.
The game ends if the player guesses the weapon foundry correctly or exhausts their three allowed guesses. If all guesses are used without success, the game informs the player and terminates.
Overview of things my game/code cannot do:
My code does NOT have multiplayer capability and the script is designed for single player only
My code does NOT have an alternating word bank to make every game feel different from the last
My code does NOT extremely complex word as they are only pre-existing weapon foundries
Side Note: Looking back on this project I feel as if somehting I MAYBE could've implemented was a diffiuculty level and even more foundries, I feel as if 3 is too little to make it a TRUE guessing game.
