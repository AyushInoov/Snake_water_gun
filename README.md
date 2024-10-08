# Snake_water_gun
  This is a simple Python game that simulates a variant of the classic "Rock, Paper, Scissors" game with a twist. 
  
  In this game, players can choose between three options: "SNAKE", "WATER", and "GUN". The computer also randomly selects one of these options. 

  How It Works
  
  1.Computer's Choice: The computer randomly selects one of the three options (SNAKE, WATER, GUN) using the random.choice method.
  
  2.User Input: The player inputs their choice, which can be 's' for SNAKE, 'w' for WATER, or 'g' for GUN. Mapping Choices:
  
  3.The player's input is mapped to its corresponding numerical value using a dictionary, and the choices are converted to human-readable format using another dictionary.
  
  4.Determine the Outcome: The program compares the choices of the player and the computer to determine the outcome of the game:
  
  if both choices are the same, it’s a tie. 
  
  If the choices are different, the game determines the winner based on predefined rules: 
  
  SNAKE beats WATER 
  
  WATER beats GUN 
  
  GUN beats SNAKE 
  
  5.Display Results: The results of the game are displayed, showing the choices of both the player and the computer, and whether the player wins, loses, or ties.
  Example If the player chooses 's' (SNAKE) and the computer chooses -1 (WATER), the result is "You win!". If the player chooses 'g' (GUN) and the computer chooses 1 (SNAKE), 
  
  the result is "You lose!". 
  
  This game provides a fun and interactive way to practice basic Python programming concepts, such as conditionals, user input, and random number generation.
