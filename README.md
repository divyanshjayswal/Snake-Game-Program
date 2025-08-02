# 🐍 Snake Game in Java (Swing GUI)

This is a classic Snake Game built using **Java Swing**. The game features a simple GUI where the snake moves around collecting food. Each time the snake eats food, it grows longer. The game is controlled using arrow keys.

## 🎮 Features
- Built with Java Swing (`JFrame`, `JPanel`, `KeyListener`, `Timer`)
- Snake movement with arrow keys
- Food appears at random positions
- Snake grows when it eats food
- Simple graphics using `ImageIcon`

## 📁 Project Structure
snakegame/ 
├── snakegame.java    # Main game logic
├── dot.png           # Snake body image
├── head.png          # Snake head image
├── food.png          # Food image

> ⚠️ Make sure all image files are placed in the same `snakegame` directory.
## 🛠️ How to Run
### Option 1: Using Command Line
   ```bash
   cd path/to/snakegame   //Navigate to the project folder
   javac snakegame.java   //Compile the game
   java snakegame         //Run the game
  ``` 
### Option 2: Using an IDE (IntelliJ IDEA / Eclipse)- Open your IDE
- Create or import a project named snakegame
- Add snakegame.java to the source folder
- Place dot.png, head.png, and food.png in the same directory
- Run snakegame.main() method

⌨️ Controls- Arrow Keys – Move the snake (Up, Down, Left, Right)

🧑‍💻 Author Divyansh - Made with ❤️ in Java
