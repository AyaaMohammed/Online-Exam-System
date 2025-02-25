# Online-Exam-System

## Project Overview
This is a simple web-based examination system where students can take an exam with multiple-choice questions. The system ensures a smooth user experience with a well-aligned design, a timer, and randomized questions.

## Features
- Exam questions are stored in a JavaScript array of objects.
- Each question includes a title, an image, multiple answers, and a correct answer.
- The interface is designed using HTML, CSS, and JavaScript.
- The home page collects the student's name using a sign-in login form and activates the start button.
- A timer bar (1 minute) manages the exam duration.
- Only one question is displayed at a time, with a **Next** button (no **Previous** button).
- Google Font is applied to the questions and answers for styling.
- The **Next** button is disabled until the student selects an answer.
- The selected answer gets a gray background color immediately after selection.
- Questions and answers are randomized each time the exam runs.
- The result is displayed at the end of the exam or when the timer expires.

## Technologies Used
- HTML
- CSS
- JavaScript

## Installation & Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/simple-exam-system.git
   ```
2. Navigate to the project folder:
   ```sh
   cd simple-exam-system
   ```
3. Open `index.html` in a browser to start the application.

## File Structure
```
/simple-exam-system
│── index.html      # Main HTML file
│── style.css       # Stylesheet for design
│── script.js       # JavaScript logic for the exam
└── assets/         # Folder for images and other assets
```

## How It Works
1. The student enters their name in a sign-in login form.
2. A start button is activated to begin the exam.
3. The exam displays one question at a time with an image and multiple choices.
4. The student selects an answer (the selected option is highlighted in gray).
5. The **Next** button becomes active after selecting an answer.
6. The exam is timed (1 minute).
7. At the end of the exam or when time runs out, the results are displayed.

## Contribution
Feel free to contribute by submitting a pull request or reporting issues.

## License
This project is licensed under the MIT License.


