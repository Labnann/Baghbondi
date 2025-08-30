# Baghbondi

Baghbondi is a board game implementation using Java and JavaFX.

## Features

- Interactive board game experience.
- Language selection (Bengali/English).
- Game timer and audio.

## Prerequisites

- Java Development Kit (JDK) 8 or higher.
- JavaFX SDK.

## How to Run

1. **Clone the repository:**
   ```sh
   git clone https://github.com/Labnann/Baghbondi.git
   cd Baghbondi
   ```

2. **Compile the source code:**
   ```sh
   javac -cp "path/to/javafx/lib/*" src/codes/*.java
   ```
   Replace `path/to/javafx/lib/*` with the path to your JavaFX SDK's `lib` directory.

3. **Run the application:**
   ```sh
   java -cp "path/to/javafx/lib/*:src" codes.Main
   ```
   On Windows, use `;` instead of `:` as the classpath separator.

## Notes

- Make sure the JavaFX SDK is downloaded and the `lib` directory path is correct.
- If you encounter errors about missing JavaFX modules, you may need to add `--module-path` and `--add-modules` options:
  ```sh
  java --module-path path/to/javafx/lib --add-modules javafx.controls,javafx.fxml -cp "path/to/javafx/lib/*:src" codes.Main
  ```

## License

This project does not currently specify a license.
