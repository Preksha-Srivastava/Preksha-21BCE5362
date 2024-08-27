Here's a step-by-step guide to execute the turn-based game using the provided Python WebSocket server code. This guide will help you set up the development environment, run the server, and play the game.

## Step-by-Step Instructions to Run the Game

### Prerequisites

1. **Python Installation**: Ensure you have Python 3.7 or higher installed on your machine. You can download it from [python.org](https://www.python.org/downloads/).

2. **WebSocket Library**: You will need the `websockets` library. You can install it using pip. Open your terminal or command prompt and run:
   ```bash
   pip install websockets
   ```

### Step 1: Create the Project Directory

1. Create a new directory for your project. You can name it `turn_based_game` or any name you prefer.
   ```bash
   mkdir turn_based_game
   cd turn_based_game
   ```

### Step 2: Create the Python Server File

1. Save the Python file named `server.py` in your project directory.

### Step 3: Run the WebSocket Server

1. In your terminal, ensure you are in the project directory where `server.py` is located.
2. Run the server using Python:
   ```bash
   python server.py
   ```

3. You should see no output if the server starts successfully. It will be running and waiting for client connections.

### Step 4: Create the Client HTML File

1. Save the HTML file named `client.html` in the same project directory.
   ```bash
   touch client.html
   ```
   for Player A save the file client1.html, and for player B save the file client2.html

### Step 5: Open the Client in a Web Browser

1. Open the `client.html` file in two different browser tabs or windows. This will simulate two players (Player A and Player B).
2. **Open 3 separate terminals in the directory, run the python file in first, run client1 in 2nd terminal, and run client2 in 3rd terminal**
3. **You would need to refresh both page after first run to display both players.**
4. **Once a player makes a move, both tabs need to be refreshed to move to next player's turn**
5. In the first tab, Player A will be represented, and in the second tab, Player B will be represented. You can change the `playerId` variable in the JavaScript code to switch between players.

### Step 6: Play the Game

1. Follow the on-screen instructions to select characters and make moves.
2. The game will alternate turns between Player A and Player B, and you can see the game state update in real-time.

### Troubleshooting

- If you encounter any issues, ensure that the WebSocket server is running and that you are accessing the correct URL (`ws://localhost:8765`).
- Check the browser console for any error messages that may help diagnose issues.
