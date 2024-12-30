## About

**Important Notice:**

This repository is the current and updated version of GameEasy. All updates, bug fixes, and support will now be handled here. The previous repository at https://github.com/Scratch-Software/GameEasy is no longer being updated. Please refer to this repository for the latest releases and developments.

GameEasy is a program developed by Scratch Software that allows you to easily run Windows-based games on Linux systems using Wine 🍷. This tool simplifies the process by handling dependencies and providing an interactive interface for game installation. GameEasy is designed to enhance the Wine experience for users who wish to play their Windows games on Linux without needing deep technical knowledge.

Note: GameEasy was fully made with Batch scripting 📝, providing a lightweight and efficient way to run your games.

All credits for this project go to Wine for making this possible. Thank you! 🙏
How GameEasy Works 🔧

GameEasy simplifies the process of setting up a Windows game on your Linux machine by doing the following:

    Directory Name: Asks for a name for the directory (typically the name of your game).
    Game Folder Path: Requests the folder path of the installed game.
    Dependencies Copy: Copies the required dependencies and folders for the game to work.
    Executable Selection: Identifies all .exe files in the game's folder and prompts you to select the executable file.
    Copy Process: Copies necessary files and provides feedback on whether the operation was successful or not.
    Running the Game: After a successful setup, it will create a .sh script to run the game. Right-click and select "Run as a program" 🎮.

## Installation ⚙️
Requirements:

    Wine (installed and set up properly on your Linux system)
    A Windows game you want to run
    GameEasy program files

Steps to Install:

    Download GameEasy:
    Clone or download the repository files for GameEasy.

    Install Wine:
    Make sure Wine is installed on your Linux system. You can install it using your package manager:

sudo apt install wine

Run GameEasy:
Once Wine is installed and GameEasy is downloaded, you can run the program with the following command:

    ./FileCreator.sh

## Tutorial 📝

Follow these steps to set up your game with GameEasy:

    Start the Program:
    Run the FileCreator.sh file to start the program. This will launch the interactive setup.

    Choose a Directory Name:
    The program will ask for a name for the new directory, which is typically the game's name. You can name it whatever you like.

    Select the Game Folder:
    The program will prompt you to select the path to the folder where your Windows game is installed. Navigate to that folder and provide the path.

    Copy Dependencies:
    GameEasy will automatically copy all necessary dependencies and files needed to run the game. This may take some time depending on the size of the game.

    Select the Game's Executable:
    Once the required files are copied, GameEasy will list all .exe files in the game's folder. Choose the one that runs the game (typically something like game.exe).

    Wait for the Process to Complete:
    After selecting the executable, GameEasy will continue copying and setting up everything. Wait until the program tells you that the operation is complete.

    Launch the Game:
    Once the setup is complete, go to the new directory GameEasy created. Instead of running the .exe file, look for a .sh file with the same name as the game. Right-click it and select "Run as a program" to launch the game 🚀.

    Troubleshooting:
    If the operation was not successful, GameEasy will provide an error code to help diagnose the problem. Check the error code and refer to the documentation for troubleshooting 🔧.

## License 📜

Before using GameEasy, please read the LICENSE.md file carefully. It contains important information about the terms and conditions for using the software. Ensure that you understand the license before proceeding with installation or usage.
Acknowledgments 🙌

    Wine: The core technology used by GameEasy to run Windows applications on Linux.
    Scratch Software: The team behind GameEasy and the development of this project.

Thank you for using GameEasy! Enjoy your games on Linux with ease! 🎮

