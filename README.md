# JavaScript MCQ Test Web App

## Overview

**Live Project:** [MCQ Web App](https://mcq-web-app.vercel.app/)
This is a simple web-based Multiple-Choice Questions (MCQ) test application built using HTML, CSS, and JavaScript. The test displays one question at a time, includes a timer for each question, and automatically submits unanswered questions when the timer runs out. A pagination system allows users to track their progress, showing attempted and unattempted questions.

## Features
- **Single Question Display:** Only one question is shown at a time.
- **Timer:** Each question has a countdown timer of 10 seconds.
- **Auto Submission:** If the timer runs out, the question is auto-submitted.
- **Score Calculation:** At the end of the test, the total score is displayed.
- **Pagination System:** Indicates attempted and unattempted questions.
- **Disabling Unattempted Questions:** Users cannot revisit unattempted questions before answering them.

## Technologies Used
- **HTML** for structuring the web page.
- **CSS** for styling and layout.
- **JavaScript** for handling logic, timers, and interactions.

## Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/mcq-test-app.git
   ```
2. Navigate to the project folder:
   ```sh
   cd mcq-test-app
   ```
3. Open `index.html` in a browser.

## File Structure
```
mcq-test-app/
│-- index.html  (Main application file)
│-- styles.css  (CSS styles for UI/UX improvements)
│-- script.js   (JavaScript logic for quiz handling)
```

## How It Works
1. The app starts by displaying the first question.
2. Users select an answer and click "Next" to proceed.
3. If the timer reaches zero, the question is automatically submitted.
4. At the end of the test, the user's score is displayed.
5. The pagination section shows attempted (green) and unattempted (gray) questions.

## Customization
- Modify the `quizData` array in `script.js` to add more questions.
- Change the timer duration by modifying the `timeLeft` variable in the `loadQuestion` function.
- Customize the styles in `styles.css` for a better UI.

## Contribution
Feel free to fork the repository and submit pull requests for improvements or new features.

## License
This project is open-source and available under the MIT License.

