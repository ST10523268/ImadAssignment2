# ImadAssignment2
# Life Hack or Urban Myth? - Flashcard Game

## Project Overview
**Life Hack or Urban Myth?** is a native Android application developed using **Kotlin** and **Android Studio**. In an era where internet rumors and "viral hacks" are everywhere, this app helps users distinguish between genuine productivity tips and dangerous or useless urban myths.

The app uses a flashcard-style interface to present questions, provide immediate educational feedback, and track the user's score to determine their "Hacker Level."

---

##  Features
* **Welcome Screen:** A clean introduction to the app's purpose with a quick-start entry point.
* **Interactive Flashcards:** Users are presented with a series of statements and must decide if they are a "Hack" (True) or a "Myth" (False).
* **Immediate Feedback:** After every answer, the app provides a detailed explanation to educate the user.
* **Scoring System:** Tracks correct answers and provides personalized feedback at the end based on performance.
* **Review System:** Allows users to reflect on their performance after completing the quiz.

---

##  Tech Stack
* **Language:** Kotlin
* **IDE:** Android Studio
* **Layouts:** LinearLayout (for structured, responsive design)
* **Architecture:** Activity-based navigation using Intents.
* **Version Control:** Managed via GitHub.
* **CI/CD:** Automated builds configured through GitHub Actions.

---

## Project Structure
The app is organized into three primary activities:
1.  **MainActivity:** Handles the entry point and initial navigation.
2.  **QuestionActivity:** Contains the core game logic, question list (Flashcard data model), and score tracking.
3.  **ScoreActivity:** Calculates the final results and displays personalized performance messages.

---

##  CI/CD & Automation
This project utilizes **GitHub Actions** to ensure code quality and build stability. Every push to the repository triggers an automated build process to verify that the application compiles correctly.


##  Design Considerations
* **User Experience (UX):** Simple vertical layouts ensure that the interactive elements (buttons) are always within thumb-reach.
* **Educational Focus:** The inclusion of an "Explanation" field in the data model ensures users learn the *why* behind every answer.
* **Visual Feedback:** Color coding (Green for correct/Hack, Red for incorrect/Myth) provides immediate visual cues to the user.

---

##  Video Presentation
https://youtu.be/2DI1X5_3YBg

## Refrences 
Reference listBloominBinary --Web & Mobile Dev (2025). FLASHCARD QUIZ GAME. [online] YouTube. Available at: https://www.youtube.com/watch?v=8SMY3JOqBdg [Accessed 24 Apr. 2026].Kevin Stratvert (2024). How to Screen Record on Laptop (2025). [online] YouTube. Available at: https://www.youtube.com/watch?v=PJB7pM5bvNI.Sharepoint.com. (2026). Sign in to your account. [online] Available at: https://advtechonline.sharepoint.com/:w:/r/sites/TertiaryStudents/_layouts/15/Doc.aspx?sourcedoc=%7BCA5A47EE-F107-44AD-AB60-6E296E0B3EAE%7D&file=IMAD5112MM.docx&action=default&mobileredirect=true.

GitHub Repo Link https://github.com/ST10523268/IMAD-Assignment-2/edit/main/README.md

