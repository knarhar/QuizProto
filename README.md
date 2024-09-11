# Vowel Quiz Application

## Project Overview
The **Vowel Quiz Application** is a web-based tool designed to help users practice and learn the **International Phonetic Alphabet (IPA)** vowel sounds. Through an interactive quiz format, users can listen to vowel sounds and match them to the correct IPA symbols.

## Features
- **Interactive Quiz**: A series of 10 questions where users listen to a vowel sound and choose the corresponding IPA symbol.
- **Multiple Choice Answers**: Each question provides four possible answers, randomly shuffled to encourage careful listening.
- **Real-time Scoring**: The user's score is updated after each question and displayed throughout the quiz.
- **Adaptive Learning**: If a mistake is made, the quiz remembers and revisits similar questions, helping users to reinforce their learning.
- **Audio Playback**: An embedded audio player lets users replay the vowel sound as needed.
- **Time Warning**: A modal popup notifies users when only one minute remains in the quiz, enhancing time management.

## Technologies Used
- **HTML**: To structure the application and present the quiz interface.
- **CSS**: For styling and responsive design.
- **JavaScript**: Provides the logic for quiz functionality, including handling user input, scoring, dynamic content generation, and managing mistakes.
- **Font Awesome**: Used for icons, specifically the volume control.
- **Audio Files**: Vowel sounds are provided as `.mp3` files, dynamically loaded into the audio player.

## Project Structure
- `index.html`: The main HTML file containing the structure and logic for the quiz.
- `style.css`: Stylesheet responsible for the layout, design, and responsive elements.
- `vowels/`: Directory containing `.mp3` files for each vowel sound.
- `README.md`: Project description and instructions (this file).

## How to Run the Project
1. Download the project files or clone the repository.
2. Open `index.html` in any modern web browser.
3. The quiz will start once you press the "Play" button.
4. Listen to the vowel sound by clicking the volume icon or using the audio player.
5. Select the correct IPA symbol from the provided multiple-choice answers.
6. After selecting an answer, click "Next Question" to proceed.
7. Your score is updated after each question, and the quiz will adapt if you make any mistakes.
8. After answering all 10 questions, your final score is displayed.

## How to Extend the Project
- **Add New Vowel Sounds**: Expand the quiz by adding more vowel sounds. To do this, include new `.mp3` audio files in the `vowels/` folder and update the vowel data array in JavaScript with corresponding IPA symbols.
- **Increase/Decrease Number of Questions**: Modify the `questionsCount` variable in the JavaScript to adjust the total number of questions in the quiz.
- **Customize Styling**: Tweak the `style.css` file to change colors, layout, fonts, or button styles.
- **Additional Quiz Features**: You can implement new features such as a timer-based scoring system or track user progress across multiple quiz sessions.

## Dependencies
- **Font Awesome**: For the volume icon.
- **HTML5 Audio Element**: The quiz relies on modern browsers that support the `<audio>` element to play `.mp3` files.

## License
This project is licensed under the MIT License, allowing for open use, modification, and distribution.

## Author
This project was developed as an engaging way to help learners practice IPA vowel sounds through interactive quizzes.
