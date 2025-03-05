# Password-generator-project-3
# 🔐 Password Strength Meter

A web-based password strength checker built with Python and Streamlit that helps users create stronger passwords by providing real-time feedback and suggestions.

## 📋 Features

- Real-time password strength evaluation
- Color-coded strength indicators (red, orange, green)
- Detailed feedback for password improvement
- Check for multiple security criteria
- User-friendly web interface
- Password input masking for security

## 🔍 Password Criteria

The strength meter evaluates passwords based on:
- Length (minimum 8 characters, 12+ recommended)
- Presence of numbers
- Presence of lowercase letters
- Presence of uppercase letters
- Presence of special characters
- Absence of repeated characters

## 🚀 Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/password-strength-meter.git
cd password-strength-meter
```

2. Install the required packages:
```bash
pip install streamlit
```

## 💻 Usage

1. Run the Streamlit app:
```bash
streamlit run psm.py
```

2. Open your web browser and go to the URL shown in the terminal (usually http://localhost:8501)

3. Enter a password in the input field to see its strength evaluation

## 🎯 Strength Levels

- **Strong** (Green): Password meets most or all security criteria
- **Moderate** (Orange): Password meets some security criteria but needs improvement
- **Weak** (Red): Password needs significant improvement

## 🛠️ Technical Details

The application uses:
- Python 3.x
- Streamlit for the web interface
- Regular expressions for pattern matching
- Custom scoring algorithm for strength evaluation

## 📝 Example

```python
# Sample password evaluation
Weak password: "password123"
- Suggestions: Add uppercase letters, Add special characters

Strong password: "P@ssw0rd123!"
- Meets all criteria
```

## 👥 Contributing

Feel free to fork this repository and submit pull requests. You can also open issues for bugs or feature suggestions.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## ⚠️ Disclaimer

This tool is for educational purposes and provides basic password strength evaluation. For critical applications, please refer to current security best practices and standards.
