# Word Guess Game (Java)

Simple Java desktop version of the Word Guess game. It uses Java Swing, so no extra libraries are needed.

## Run in VS Code
1. Install a JDK (Java 17 or later) and the Java Extension Pack in VS Code.
2. Open this folder in VS Code.
3. Open `src/Main.java` and click **Run**, or use the terminal:

```powershell
javac -encoding UTF-8 -d out src/Main.java
java -cp out Main
```

## Features
- Player registration and login
- Five-letter word guessing game (five attempts)
- Green = correct letter and position; orange = letter exists elsewhere; grey = letter not in the word
- Up to three new words per player in the running session
- Admin activity report for games played during the running session

For simplicity, users and game reports are kept in memory and reset when the app closes.

The built-in demo admin account is not displayed in the UI. Credentials for local testing: username `Admin`, password `Admin$123`.
