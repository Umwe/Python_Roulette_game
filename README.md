## Python Roulette Game
This code is a simple implementation of a roulette game in Python. It allows multiple players to place bets on different cells on the roulette table and then randomly determines the winning cell. Players can be either human or computer-controlled.

How to Run the Game
To run the game, execute the Python script in your preferred Python environment. The script does not require any additional dependencies.

The game begins with initializing the table, creating players, and setting up the cells on the table. Each player starts with a specified number of coins.

During each round of the game, players take turns placing bets on the table. Human players will be prompted to enter their bet amount and the cell they want to bet on. Computer players will make random bets.

After all players have placed their bets, the winning cell is determined randomly. The players who have bet on the winning cell will receive a payout based on the betting rate of the cell. The payout is added to their total coins.

The game continues until one or more players run out of coins. At the end of the game, a message is displayed indicating which player(s) have run out of coins, and the game ends.

Customization
The game can be customized by modifying the following aspects:

Number of players: You can create additional instances of the Computer class to add more computer-controlled players.
Initial coins: You can change the initial coin amounts for each player when creating them.
Betting limits: The code currently limits the maximum bet amount to 99 coins. You can modify this limit by changing the value assigned to max_bet_coin in the Human class's bet method.
Roulette table: The current implementation includes 10 cells on the table, consisting of red cells, black cells, and numbered cells. You can modify the table by changing the create_table function.
Limitations
This code is a simplified implementation of a roulette game and has several limitations:

There is no user interface, and the game is played through the console.
The code does not include complex betting options such as split bets, corner bets, etc.
The code does not enforce realistic roulette rules, such as minimum and maximum bet limits, or specific payout rates.
The code does not include advanced roulette features such as special bets (e.g., odd/even, dozens, columns) or tracking of historical results.
Conclusion
This code provides a basic framework for a simple roulette game in Python. It can serve as a starting point for further development and customization to add more advanced features and improve the user experience.
