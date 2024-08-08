# Number Guessing Game (Spring Console Application)

## Overview

This is a console-based number guessing game implemented using Spring Framework. The game generates a random number and the player has to guess the number within a given range. The game provides feedback on whether the guess is too high or too low.

## Features

- Random number generation
- User input for guessing the number
- Feedback on guesses (too high, too low)
- Configurable range for the random number
- Game loop until the correct number is guessed

## Technologies Used

- Java
- Spring Framework
- Maven

## Setup and Running the Game

### Prerequisites

- Java Development Kit (JDK)
- Apache Maven

### Steps

1. **Clone the repository**:
    ```sh
    git clone https://github.com/yourusername/number-guessing-game-console.git
    cd number-guessing-game-console
    ```

2. **Build the project**:
    ```sh
    mvn clean install
    ```

3. **Run the application**:
    ```sh
    mvn exec:java -Dexec.mainClass="com.example.NumberGuessingGame"
    ```

## How to Play

1. The game will prompt you to guess a number within a specified range.
2. Enter your guess and press Enter.
3. The game will provide feedback on whether your guess is too high, too low, or correct.
4. Keep guessing until you find the correct number.
5. Once you guess correctly, the game will display the number of attempts you made.

## Project Structure

- `src/main/java`: Contains the main Java classes for the game
- `src/main/resources`: Contains the application configuration files
- `pom.xml`: Maven configuration file

