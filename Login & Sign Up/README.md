
# LoginGUI

## Description
The `LoginGUI` is a Java Swing application that provides a simple graphical user interface (GUI) for user login functionality. It includes fields for entering a username and password, and a login button to verify the credentials. A success or failure message is displayed based on the input provided.

## Features
- Input fields for username and password.
- A button to submit login information.
- Displays a success message for valid credentials or an error message for incorrect credentials.
- User-friendly design with clear input prompts and feedback.

## Installation
1. Ensure you have Java Development Kit (JDK) installed on your machine.
2. Clone this repository or download the source code files.
   
  ```bash
  git clone https://github.com/itsvee0120/Java-JavaSwing
  cd Java-JavaSwing/"Login & Sign Up"
  ```

3. Compile the Java file using the following command:
   ```bash
   javac LoginGUI.java
   ```
4. Run the application with:
   ```bash
   java LoginGUI
   ```

## Usage
1. Launch the application.
2. Enter your username in the "Username" field.
3. Enter your password in the "Password" field.
4. Click on the "Login" button.
5. The application will display:
   - **"Login successful!"** for correct credentials (username: `n`, password: `123`).
   - **"Wrong Credentials"** for incorrect credentials.
   - **"Enter your credentials to login"** if fields are left blank.

## Code Structure
- **LoginGUI.java**: The main class that sets up the login GUI and handles the login logic.
  - **actionPerformed(ActionEvent e)**: Method to handle button click events and verify the login credentials.
  - **Arrays.equals()**: Used to safely compare the password entered by the user with the stored password.

## Example
If the user enters:
- **Username**: `n`
- **Password**: `123`

The application will display:
```
Login successful!
```

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- Created by Violet Nguyen.
- Inspired by Java Swing tutorials and online resources on building GUI applications.
- The `README.md` file was generated using an AI prompt, with additional details checked for accuracy by Violet.

