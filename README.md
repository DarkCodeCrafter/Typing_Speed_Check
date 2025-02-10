# Typing Speed Test

This is a simple **Typing Speed Test** web application built using **Flask**, **HTML**, **CSS**, and **JavaScript (AJAX)**. The application displays a random phrase for the user to type, records the typing time, and calculates accuracy and speed (words per minute).

## Features
- Random phrase generation for each test
- Real-time typing speed and accuracy calculation
- Results displayed on the same page without reloading (AJAX)
- "Try Again" button to restart the test with a new phrase

## Technologies Used
- **Python (Flask)** – Backend server
- **HTML, CSS** – Frontend UI
- **JavaScript (jQuery + AJAX)** – Handle typing input and results calculation dynamically

## Installation and Setup

### 1. Clone the Repository
```bash
git clone https://github.com/DarkCodeCrafter/Typing_Speed_Check
cd typing-speed-test
```

### 2. Create a Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install flask
```

### 4. Run the Flask Application
```bash
python app.py
```

### 5. Open in Browser
Visit **http://127.0.0.1:5000/** in your browser.

## File Structure
```
/typing-speed-test
│── app.py              # Flask backend
│── /templates
│   └── index.html      # Frontend UI
│── README.md           # Project documentation
```

## Usage
1. Start the Flask app and open the web page.
2. A random phrase will be displayed.
3. Start typing in the input box (timer starts automatically).
4. Click **Submit** to see your typing speed and accuracy.
5. Click **Try Again** to reload a new phrase.

