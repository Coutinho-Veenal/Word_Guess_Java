# Word Guess Game (Java)

A simple word-guessing game built using Java and Swing. The goal is to guess a hidden five-letter word within five attempts. The game provides color hints after each guess to help you figure out the correct word.

## Getting Started

### Prerequisites

* Java JDK 17 or later
* Visual Studio Code
* Java Extension Pack for VS Code

### How to Run

1. Clone this repository or download the project.
2. Open the project folder in VS Code.
3. Open the terminal and run the following commands:

```bash
javac -encoding UTF-8 -d out src/Main.java
java -cp out Main
```

You can also open `src/Main.java` and click **Run** in VS Code.

## Features

* Register and log in as a player.
* Guess a five-letter word in five attempts.
* Get color hints for each letter:

  * **Green:** Correct letter in the correct position.
  * **Orange:** Correct letter in the wrong position.
  * **Grey:** Letter is not in the word.
* Play up to three new words per session.
* Access an admin report to view game activity.

## Technologies Used

* Java
* Java Swing

## Note

This project stores user details and game activity in memory, so the data resets whenever the application is closed.

The application also includes a demo admin account for local testing. The login credentials are kept out of the user interface.

## Future Improvements

* Store user details and game history permanently.
* Add more words and difficulty levels.
* Track player scores and previous games.

---

Built as a simple Java project to practise programming and GUI development.
