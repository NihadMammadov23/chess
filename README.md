# Chess Master

![Chess Master Banner](https://github.com/NihadMammadov23/chess/blob/main/chess1.png)  
![Chess Master Banner](https://github.com/NihadMammadov23/chess/blob/main/chess2.png)  
![Chess Master Banner](https://github.com/NihadMammadov23/chess/blob/main/chess3.png)  

---

## Overview

**Chess Master** is a comprehensive chess application built in Java. It provides several play modes:

- **Hotseat:** Two players can play on the same device by taking turns.  
- **AI Mode:** Challenge the computer with different difficulty levels.  
- **Multiplayer Network:** Connect with another player over the network using IP address and port.

The game features a clean GUI, full chess rules enforcement, and a flexible setup for multiplayer gaming.

---

## Features

- ♟️ Full chess rules support including castling, en passant, promotion, and check/checkmate detection.  
- 🧑‍🤝‍🧑 **Hotseat Mode:** Play with friends locally on the same machine.  
- 🤖 **AI Opponent:** Play against computer-controlled opponent with adjustable difficulty.  
- 🌐 **Network Multiplayer:** Host or join games via IP address and port for remote play.  
- 🎨 Graphical User Interface (GUI) built with Java Swing for an interactive experience.  
- 🔄 Undo and game reset functionality.  

---

## Technologies Used

- **Java SE** (Standard Edition) for game logic and GUI.  
- **Java Swing** for user interface components.  
- **Java Networking** (Sockets) for multiplayer communication.  

---

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or higher installed on your system.  
- Optional: An IDE such as IntelliJ IDEA or Eclipse for easy project setup.

### Running the Game

1. **Clone the repository**

```bash
git clone https://github.com/NihadMammadov23/chess
cd chess
```


2. **Compile the Java files**

```bash
javac -d bin src/*.java
```


3. **Run the game**
   
```bash
java -cp bin Main
```


**Usage**
   - Choose your desired play mode from the main menu: Hotseat, AI, or Network Multiplayer.
   - For network multiplayer, enter the host IP address and port number to connect.
   - Use the GUI to make moves by clicking on pieces and target squares.
   - Access game options to undo moves, reset the board, or quit.

**Future Enhancements**
  - Implement a chess engine with advanced AI algorithms (e.g., Minimax with Alpha-Beta pruning).
  - Add online matchmaking and chat features.
  - Improve UI with custom themes and animations.
  - Save/load game states and replay functionality.

**Contribution**
Contributions are welcome! Feel free to fork the repository and submit pull requests to enhance the game.

**License**
This project is licensed under the MIT License.

**Author**
***Nihad Mammadov***
