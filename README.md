# Online Voting System

A Java-based GUI application developed using Java AWT to demonstrate a basic online voting workflow, including login authentication, candidate selection, vote counting, and result display.

## Features

- Login screen with username and password
- Candidate selection using radio-style checkboxes
- Vote counting for five candidates
- Voting confirmation screen
- Results display
- Simple graphical user interface

## Technologies Used

- Java
- Java AWT
- Java Event Handling
- Object-Oriented Programming (OOP)

## Candidates

- DMK
- ADMK
- TVK
- NTK
- BJP

## How to Run

1. Install the Java Development Kit (JDK).
2. Clone or download this repository.
3. Open a terminal in the directory containing the `Rithik` folder.
4. Compile the program:

   ```bash
   javac Rithik/OnlineVotingSystem.java
   ```

5. Run the application:

   ```bash
   java Rithik.OnlineVotingSystem
   ```

## Login for Demonstration

- Username: `admin`
- Password: `123`

These are hardcoded demonstration credentials, not secure production authentication.

## Limitations

- Vote counts are stored in memory and reset when the application restarts.
- The current implementation does not prevent the same user from voting repeatedly.
- It does not currently use a database or implement encryption.
- It is a desktop GUI prototype, not a deployed web-based election system.

## Future Enhancements

- Database integration using MySQL
- Secure user authentication
- Prevention of duplicate voting
- Improved interface design
- Persistent storage of voting results

## Author

Rithik M

Electronics and Communication Engineering

M. Kumarasamy College of Engineering
