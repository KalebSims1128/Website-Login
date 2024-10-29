# Website Login Application

This is a simple command-line application written in Python for managing user login and signup functions. It allows users to sign up with an ID and password, log in with their credentials, and access a main menu with various sections (Utility, Game, Multimedia). Some features are currently placeholders and may be expanded in the future.

## Features

1. **Login/Signup System**
   - Users can sign up with an ID and password.
   - Login functionality allows users to access the main menu if credentials are correct.
   - If login credentials are incorrect, users receive an error message.

2. **Main Menu**
   - The main menu has three sections:
     - **Utility** (calculator, email, note) 
     - **Game** (poker, blackjack, starcraft)
     - **Multimedia** (music player, camera, download)

   Each section provides options, though many are placeholders for future development.

## File Structure

- `id.txt` - Stores user IDs.
- `pass.txt` - Stores user passwords.

> **Note**: Each file is accessed and modified by the program to manage user credentials.

## Usage

1. **Run the program**:
   - Execute the script to launch the login/sign-up menu.
2. **Sign Up**:
   - Select "2" from the menu to sign up with a new ID and password.
3. **Log In**:
   - Select "1" to log in with an existing ID and password.
4. **Main Menu Navigation**:
   - Access various sections through the main menu after logging in.

## Functions

- **menu()**: Displays the main login/sign-up options and handles user input.
- **signup()**: Allows new users to register by creating a unique ID and password.
- **login()**: Authenticates users by checking credentials in `id.txt` and `pass.txt`.
- **mainMenu()**: Displays sections (Utility, Game, Multimedia) available to logged-in users.
- **gameMenu()**: Contains placeholder options for games.
- **utility()**: Contains placeholder options for utilities.
- **multimedia()**: Contains placeholder options for multimedia functions.

## Future Improvements

- Add functionality to each menu option within Utility, Game, and Multimedia.
- Implement password encryption for secure storage of user passwords.
- Add error handling and validation for user input.

## Getting Started

To use this application:
1. Clone or download the project files.
2. Ensure Python is installed.
3. Run the script:

   ```bash
   python your_script_name.py
