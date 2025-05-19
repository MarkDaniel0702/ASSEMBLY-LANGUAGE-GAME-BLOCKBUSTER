# BlockBuster: An x86 Assembly Language Game

---

## 🎮 Description

BlockBuster is a modern interpretation of the classic Atari Breakout (1976) formula, meticulously developed in x86 Assembly Language. This game serves as a comprehensive course project for Computer Architecture and Assembly Language Programming. It aims to showcase the capabilities of low-level programming while emphasizing core principles of computer architecture.

Drawing inspiration from the iconic legacy of Breakout, which revolutionized the gaming world by introducing the brick-breaker genre, BlockBuster strives to be both an educational tool and an engaging gaming experience. The video game industry has undergone a remarkable transformation, evolving from simple pixel-based games to complex, immersive digital worlds. This evolution is particularly evident in the arcade genre, where classic titles continue to inspire modern developers. Breakout's simple yet captivating mechanics captured the imagination of players worldwide and laid the foundation for countless similar games.

---

## 🧑‍💻 Developers

### Original Developers (BSCS 2-1 Group 4)
* Aguinaldo, Samantha S.
* Bautista, Anna Kathlyn A.
* Chaves, Samantha D.
* De Roxas, Carnation Jhulia I.
* Enriquez, Sybil Mitch S.
* Fallaria, Immaculate L.
* Pantoja, Rhayzel S.
* Pineda, Ernest Michael B.

### Current Developer/Upadaters (BSCS 2nd Year Block 1 Group 2)
* Abundo, Jonalene Ryza B.
* Apelledo, Mark Daniel D.
* Camus, Angel Lyn M.
* Dalangin, Hershey Anne S.
* Gernale, Xienen Lei M.
* Mabutas, Carla R.
* Miranda, Mariebethel Roussamiere C.
* Vaflor, Mariel Kim D.

---

## ✨ Features

### Original Version Features
* A progressive difficulty system across multiple levels.
* Different gameplay modes.
* Functional audio-visual feedback.

### Enhanced Version Features
* **Expanded Name Capacity System:** Player name input increased from 4 to 20 characters.
* **Dynamic Power-Up System:** Introduces power-ups like Longer Paddle Modification for strategic advantages.
* **Challenge Modifiers (Nerfs):** Added to balance power-ups, including Shortened Paddle Modification and Time Penalty for Missed Ball.
* **Visual Improvements:** Enhanced with more vibrant and colorful elements while preserving the classic arcade aesthetic. This includes a redesigned Main Menu and a Pause/Play system triggered by pressing 'P'.

### Multiple Game Modes
* **Level Mode:** Traditional progression-based experience with five increasingly challenging levels.
* **Timed Mode:** Fast-paced, score-driven mode where players race against the clock.
* **Powerplay Mode:** Dynamic challenge mode with randomly falling power-ups and/or nerfs.

---

## ⚠️ Original Challenges

The first iteration of BlockBuster faced several issues that have been addressed in the enhanced version:
* Restrictive four-character player name input.
* Static difficulty progression.
* A basic user interface.

---

## 🕹️ How to Play

### Starting the Game
The game begins with a landing panel. Press `'P'` to Play or `'C'` to View Controls.

### Enter Your Name
You will be prompted to input your name (maximum 20 characters).

### Main Menu
From the main menu, you can choose between Level Mode and Timed Mode. You can also adjust sound settings in the Options menu.

### Gameplay Mechanics
* Use the arrow keys to control the paddle.
* Your objective is to catch the ball and bounce it upward to break the blocks.
* Each round starts with three lives. A life is lost if the ball is missed and goes below the paddle.
* Look out for power-ups and nerfs that may fall from broken blocks. Catch them to gain advantages or face new challenges.

### Game Modes Explored
* **Level Mode:** Progress through five levels, each with increasing difficulty. To complete a level, you must break all the bricks.
* **Timed Mode:** Aim to break as many blocks as possible before the countdown timer runs out.
* **Powerplay Mode:** This mode introduces an element of surprise with randomly falling power-ups and/or nerfs, requiring quick adaptation and strategic thinking.

### Controls Reference
* **Left & Right Arrow Keys:** Move the paddle horizontally.
* **Enter:** Start the game and confirm selections in menus.
* **`'P'` Key:** Toggles the Pause/Play state of the game and accesses the pause menu.
* **`ESC` Key:** Return to the main menu or exit the current session.
* **Sound Toggle (in Options):** Turn sound effects on/off, adjust volume, and enable/disable background music.

---

## 🛠️ Installation Instructions

### Required Tools
* DOSBox Emulator
* Turbo Assembler (TASM)
* A text editor (e.g., Notepad++)

### Steps
1.  Install DOSBox from [dosbox.com](https://www.dosbox.com/).
2.  Download and set up TASM Tools.
3.  Clone this repository:
    ```bash
    git clone [https://github.com/MarkDaniel0702/ASSEMBLY-LANGUAGE-GAME-BLOCKBUSTER.git)
    ```
4.  Launch DOSBox and navigate to the game directory where you cloned the repository.
5.  Compile the game using TASM:
    ```bash
    tasm bbuster.asm
    tlink bbuster.obj
    ```
6.  Run the game:
    ```bash
    bbuster.exe
    ```

---

## 📜 Credits & References

* Original Game Inspiration: Atari Breakout (1976)
* x86 Assembly Language Reference Materials
* DOSBox Documentation
* Turbo Assembler Documentation
* Updated Code Repositories:
    * [BlockBusterUpdates on GitHub](https://github.com/jhamped/blockbuster-assembly)
    * [BBuster Neue Version on GitHub](https://github.com/MarkDaniel0702/BBusterNeueVersion)
    *(Note: The second link has been corrected to a typical GitHub repository URL format.)*

## Project Photos and Videos

### The Whole Group
![The Whole Group](https://github.com/user-attachments/assets/20a4c0b3-f065-4723-be78-f42f80ab0f75)

### The Game
![The Game](https://github.com/MarkDaniel0702/ASSEMBLY-LANGUAGE-GAME-BLOCKBUSTER/blob/4a98117d4d6b4fb12668eb9b1f5e4beb05b0e950/READMEPHOTOS/blockb-demo.gif)

---
