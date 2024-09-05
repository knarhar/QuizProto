# Vowel Quiz Application

## Project Overview
This project is a web-based quiz game designed to help users learn and practice the International Phonetic Alphabet (IPA) vowel sounds. The quiz plays vowel sounds and presents the user with multiple-choice answers. Users must match the correct vowel sound to its corresponding symbol.

## Features
- **Interactive Quiz**: The quiz consists of 10 questions where the user listens to a vowel sound and chooses the correct IPA symbol.
- **Multiple Choice**: Each question presents 4 possible answers, randomly shuffled.
- **Score Tracking**: The user's score is tracked and displayed after each question.
- **Mistake Adaptation**: If a user selects an incorrect answer, the quiz tracks the mistake and revisits it in subsequent questions to help with learning.
- **Audio Playback**: An audio player is embedded to play the vowel sounds, and users can click an icon to repeat the sound.

## Technologies Used
- **HTML**: For the basic structure of the webpage.
- **CSS**: For styling the application.
- **JavaScript**: For the quiz logic, including handling user input, scoring, and dynamically generating questions.
- **Font Awesome**: For the volume icon in the audio player.
- **Audio Files**: The vowel sounds are included as audio files (in `.ogg` format) and dynamically loaded into the audio player.

## File Structure
- `index.html`: The main HTML file that contains the structure of the quiz.
- `style.css`: Contains all the styling for the quiz layout and design.
- `vowels/`: A folder containing the vowel sound files in `.ogg` format.
- `README.md`: This file with the project description.

## How to Use
1. Open `index.html` in a web browser.
2. The quiz will automatically start by loading the first question.
3. Click on the volume icon or use the audio player to play the vowel sound.
4. Select the correct IPA symbol from the multiple-choice answers.
5. If you answer correctly, your score will increase. If you answer incorrectly, the correct answer will be displayed, and the mistake will be tracked for future questions.
6. After answering, click "Next Question" to move on.
7. The quiz continues for 10 questions, after which the final score is displayed.

## How to Extend the Project
- **Add more vowels**: You can add more vowel sounds to the `vowels` array in the JavaScript by providing new audio files and corresponding IPA symbols.
- **Change the number of questions**: You can adjust the `questionsCount` variable in the JavaScript to modify the number of questions in the quiz.
- **Style customization**: Modify the `style.css` file to change the appearance of the quiz.

## Dependencies
- **Font Awesome**: Used for the volume icon.
- **Browser support for `audio` element**: Ensure the browser supports the HTML5 `audio` element for playing `.mp3` files.

## License
This project is licensed under the MIT License. Feel free to modify and distribute it as needed.

## Author
This project was created as a fun way to practice and learn IPA vowel sounds through interactive quizzes.
