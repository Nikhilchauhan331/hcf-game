# HCF Factor Factory ⚙️

HCF Factor Factory is an interactive educational web game designed to help students in grades 4-7 learn and practice finding the Highest Common Factor (HCF) in a fun, engaging way.

The game uses a "factory" theme where players must choose the correct "tool" (the HCF) to process two "gears" (numbers). It includes a PHP-powered backend to save high scores and display a persistent leaderboard.

---

## Features

-   **Interactive Gameplay:** Engages students with a visual, hands-on approach to learning math.
-   **Dynamic Problem Generation:** Randomly generates new number pairs for endless practice.
-   **Immediate Feedback:** Instantly tells the player if their answer is correct and shows the right answer if they are wrong.
-   **Score Tracking:** Keeps track of the player's score throughout the quiz.
-   **PHP Leaderboard:** A persistent leaderboard saves top scores, encouraging replay and competition.

---

## Technology Stack

-   **Frontend:** HTML5, CSS3, Vanilla JavaScript
-   **Backend:** PHP
-   **Data Storage:** JSON file (used as a simple database for scores)

---

## Local Setup and Installation

To run this project locally, you need a server environment that can execute PHP, such as XAMPP, WAMP, or MAMP.

1.  **Download a Server:** Install [XAMPP](https://www.apachefriends.org/index.html) or a similar local server solution.

2.  **Start Your Server:** Launch the XAMPP Control Panel and start the **Apache** service.

3.  **Clone or Download the Project:** Place the project files into the server's root web directory. For XAMPP, this is the `htdocs` folder (e.g., `C:/xampp/htdocs/`).

4.  **Place the Files:** The final directory structure should look like this:
    ```
    /xampp/htdocs/hcf-game/
    |
    |-- index.php
    |-- style.css
    |-- script.js
    |-- README.md
    |
    |-- /api/
        |-- get_scores.php
        |-- save_score.php
    ```

5.  **Run the Game:** Open your web browser and navigate to `http://localhost/hcf-game/`. The game should now be running.

    **Note:** The `scores.json` file will be created automatically in the root `hcf-game` directory the first time a player submits a score.

---

## How to Play

1.  **Observe the Numbers:** Two numbers will appear on the large "gears" on the factory floor.
2.  **Select a Tool:** From the toolbox below, click on the number (the "tool") that you believe is the **Highest Common Factor** of the two numbers.
3.  **Check Your Score:** If you're correct, your score increases! If not, the game will show you the correct answer.
4.  **Continue:** Click "Next Question" to proceed. After 10 questions, the game ends.
5.  **Submit to Leaderboard:** If you're proud of your score, enter your name to submit it to the leaderboard!
