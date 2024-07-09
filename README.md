# RPG Raid Scheduler Program

## Objective

Create a console-based program for managing raid events in a RPG-themed game. The program allows the user to input how many raids are scheduled, and then enter the names, party sizes, and times of those raids. Use dynamic memory allocation and raw pointers to manage the raid information.

## Requirements

### Raid Management

- Use dynamic memory allocation to create an array of raid names based on user input.
- For each raid, dynamically allocate memory to store its party size and time.
- Allow the user to enter the names of the raids, party sizes, and times.
- Display the list of raids with their details.
- Clean up the dynamically allocated memory before the program exits.

## Steps

### 1. Set Up Project

- Create a new C++ project and set up your development environment.
- Include necessary headers (`<iostream>`, `<string>`).

### 2. Input Number of Raids

- Prompt the user to input the number of raids.
- Use dynamic memory allocation to create an array of strings to store the raid names.
- Dynamically allocate memory to store the party sizes and times for each raid.

### 3. Input Raid Names, Party Sizes, and Times

- Allow the user to input the names of the raids.
- For each raid, allow the user to input the party size and time.

### 4. Display Raid Information

- Display the list of raids with their details to the user.

### 5. Clean Up Memory

- Ensure that all dynamically allocated memory is properly cleaned up before the program exits.

## Example User Interaction

```plaintext
Enter the number of raids: 2
Enter the name of raid 1: Theatre of Blood
Enter the party size for Theatre of Blood: 5
Enter the time of raid Theatre of Blood: 6:00 PM
Enter the name of raid 2: Chambers of Xeric
Enter the party size for Chambers of Xeric: 10
Enter the time of raid Chambers of Xeric: 8:00 PM

Raids and their details:
Theatre of Blood:
  Party Size: 5
  Time: 6:00 PM
Chambers of Xeric:
  Party Size: 10
  Time: 8:00 PM
```
## Submission Details

### 1. Complete the project and ensure it is bug-free.

### 2. Add the completed project to your GitHub repository.

### 3. Submit the link to your repository through your program dashboard to continue the program.

### 4. A code review will be processed once the submission is received.
