### Password Generator Flask App

This is a simple web application built using Flask, HTML, CSS, and JavaScript that allows users to generate random passwords. The app provides options to customize the password length and the number of passwords to generate.

#### Features
- Generate multiple passwords with adjustable lengths.
- Secure password creation using a mix of lowercase letters, uppercase letters, and numbers.
- Simple and responsive interface for easy use.

#### Technologies Used
- **Flask**: A Python web framework to manage the backend logic.
- **HTML/CSS**: Used for the frontend layout and styling.
- **JavaScript**: Handles form submission and interacts with the backend using `fetch`.
- **Python**: Implements the password generation logic.

#### Installation

1. **Clone the Repository**  
   To get started, clone the repository:
   ```bash
   git clone https://github.com/Dev-Coder20/Password-Generator-Web.git
   cd password-generator-flask
   ```

2. **Install Dependencies**  
   Ensure you have Python and pip installed. Then, install Flask:
   ```bash
   pip install flask
   ```

3. **Run the App**  
   To start the Flask app, use the command:
   ```bash
   python app.py
   ```
   The app will be accessible at:  
   `http://127.0.0.1:5000/`

4. **Open the App**  
   Navigate to `http://127.0.0.1:5000/` in your web browser to start using the app.

#### Usage
- Enter the desired number of passwords in the **"Number of Passwords"** input field.
- Set the password length in the **"Password Length"** input field.
- Click the **"Generate"** button to generate passwords.
- The passwords will appear below the form in a list.

#### Customization
You can personalize the app by modifying the following:

- **Password Generation Logic**:  
  Modify the `generate_password`, `replace_with_number`, and `replace_with_uppercase_letter` functions in `app.py` to alter how passwords are generated.

- **Frontend Styling**:  
  Customize the look and feel of the web page by editing `styles.css`.
