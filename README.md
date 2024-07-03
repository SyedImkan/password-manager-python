# Password Manager

This is a simple password manager application built using Python and Tkinter.

## Features

- **Password Generator**: Generates a random password with a combination of letters, numbers, and symbols.
- **Save Password**: Stores website, email, and password details securely in a JSON file (`data.json`).
- **Retrieve Password**: Allows users to search and retrieve stored passwords based on the website.

## How to Use

1. **Generate Password**:
   - Click on the "Generate Password" button to create a random secure password.
   - The generated password is copied to your clipboard automatically.

2. **Save Password**:
   - Enter the website URL, your email/username, and the generated or your own password.
   - Click on the "Add" button to save the details securely.

3. **Retrieve Password**:
   - Enter the website URL and click on the "Search" button.
   - If the credentials exist in the database (`data.json`), the email and password will be displayed.

## Dependencies

- Python 3.x
- Tkinter (standard GUI library for Python)
- pyperclip (for copying passwords to clipboard)
- JSON (for storing data)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```
2. Install Dependencies:
   ```
   pip install pyperclip
   ```
3. Run the App:
   ```
   python password_manager.py
   ```
## Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to fork the repository and submit a pull request.
   
