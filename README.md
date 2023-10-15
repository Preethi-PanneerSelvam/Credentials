# User Authentication System

This Python script implements a basic user authentication system where users are required to enter their username and password to log in. The system allows users a limited number of login attempts before their account is blocked. 

## Usage

1. Set your username and PIN (password) at the beginning of the script:

```python
User = "Preethi"
Pin = 2107
```

2. Set the maximum number of login attempts in the `No_attempt` variable:

```python
No_attempt = 3
```

3. Run the script.

4. When prompted, enter your username and password. The script will provide feedback based on the correctness of the input.

## Features

- The user is prompted to enter their username, and if it matches the predefined `User`, they are prompted to enter their password (PIN).

- The user has a limited number of login attempts, controlled by the `No_attempt` variable. If the user exceeds this number of attempts, their account is blocked.

- The script provides feedback on the number of remaining attempts and warns the user when they have one attempt left before account blocking.

- Error handling:
  - If the user enters a non-numeric password, the script catches a `ValueError` and asks the user to enter the password using numbers only.
  - If there are other unspecified errors during input, a general exception is caught, and the script advises the user to enter credentials in the correct format.

## Example

Here's an example of how to use this script:

1. Set your username and PIN at the beginning of the script.

2. Set the maximum number of login attempts.

3. Run the script.

4. Follow the prompts, entering the username and PIN.

5. Observe the feedback provided by the script regarding login success, incorrect credentials, remaining attempts, or account blocking.

## Note

This is a basic implementation for educational purposes. In real-world applications, you would use more secure authentication methods and store user credentials securely. Additionally, you might want to implement account recovery and other features to enhance user experience and security.
