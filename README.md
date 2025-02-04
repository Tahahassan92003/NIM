# NIM
This project implements the game of Nim, a mathematical strategy game, where players take turns removing objects from distinct piles. 

Here’s a description for your project:  

---

### **Nim Game with AI (Reinforcement Learning)**  

This project implements the game of **Nim**, a mathematical strategy game, where players take turns removing objects from distinct piles. The game is enhanced with an AI opponent that utilizes **Q-learning**, a reinforcement learning technique, to improve its decision-making over time.  

#### **Features:**  
- **Game Mechanics:**  
  - Two players take turns picking objects from different piles.  
  - The player forced to take the last object loses.  
- **AI Opponent:**  
  - Uses **Q-learning** to learn from previous games.  
  - Stores Q-values in a dictionary to evaluate optimal moves.  
  - Trained by playing thousands of self-play matches.  
- **Training & Gameplay:**  
  - The AI undergoes **self-play training** to improve its strategy.  
  - Players can challenge the trained AI in an interactive game session.  
- **Decision-Making:**  
  - AI selects moves based on learned Q-values.  
  - Introduces **exploration vs. exploitation** using an **epsilon-greedy strategy**.  
- **User Interaction:**  
  - The game provides a simple terminal-based interface for human players.  
  - Users can choose their moves while competing against the AI.  

#### **Technology Stack:**  
- **Python**  
- **Reinforcement Learning (Q-Learning)**  
- **Randomized Decision-Making**  
- **Terminal-based Gameplay**  

This project serves as a great introduction to **reinforcement learning** concepts and strategic AI development.
