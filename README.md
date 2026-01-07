🛡️ Shas Milim Gameshow

Shas Milim Gameshow is an interactive, offline-ready web application designed for Gemara classrooms. It gamifies the process of learning and testing vocabulary (Shas Milim) through various engaging modes like Team Battle, Solo Challenge, and Fire Rounds.

🚀 Features

Zero Installation: Runs entirely in a single HTML file. No internet connection required after initial load.

3 Game Modes:

Standard: Turn-based round robin.

Solo Challenge: 60-second "Hot Seat" speed run.

Quiz Mode: Multiple-choice projection for the whole class to answer on paper.

Team Play: Automatically splits the class into Team A and Team B for competitive scoring.

Fire Round: A "Survivor" style mode where incorrect answers eliminate players until one champion remains.

Classroom Management:

Track active/absent students.

Upload custom class rosters via CSV.

Persistent settings (saves to browser memory).

Teacher Tools:

Export daily statistics/mistakes to Excel/CSV.

Undo button for accidental clicks.

Keyboard shortcuts for faster gameplay.

🛠️ How to Use

Download: Download the shas_milim_offline.html file.

Play: Double-click the file to open it in any modern web browser (Chrome, Edge, Safari, Firefox).

Setup:

Select the range of words to test (e.g., 1-20).

Mark any absent students so they are skipped in the rotation.

Choose your game mode and click Start.

🎮 Game Modes Explained

1. Standard Mode

The classic "round-robin" style. The game randomly picks a student and a word.

Correct: The student gets a point (if in Team Mode) and the turn passes.

Incorrect: The student is marked for the round. If "Fire Round" is enabled later, they will not advance.

Streak: The class builds a "Streak" counter for every consecutive correct answer.

2. Solo Challenge ("The Chidon")

Select one student to sit in the "Hot Seat".

They have 60 seconds (adjustable) to answer as many words as possible.

Scoring is individual. Perfect for finding the "class champion."

3. Quiz Mode

Designed for the whiteboard/projector.

Displays a word and 4 multiple-choice definitions (A, B, C, D).

"None of the above" logic is included to prevent simple guessing.

Includes an Answer Key reveal at the end so the class can self-mark their papers.

⌨️ Keyboard Shortcuts

Keep the game flowing without using the mouse:

Action

Keys

Correct

Spacebar / Enter / Right Arrow

Incorrect

Backspace / Delete / X / Left Arrow

Undo

Ctrl + Z (Windows) / Cmd + Z (Mac)

📂 Customization (CSV Uploads)

You can replace the default lists with your own data using the Manage Class and Manage Words buttons.

Uploading Students

Create a .csv file with a single column of names:

Adler, Gavriel
Beller, Yishai
Brodie, Aryeh
...


Uploading Vocabulary

Create a .csv file with 3 columns (Number, Hebrew Word, English Meaning). Do not include a header row.

101,גמרא,Gemara
102,משנה,Mishnah
103,תנא,Tanna
...


📊 Data & Privacy

Local Storage: All data (student names, vocabulary, game settings, and daily stats) is stored locally on your specific computer/browser.

No Cloud: No data is sent to the internet. It is completely private and safe to use.

Export: You can export game logs to a .csv file to track student progress in Excel.

💻 Technologies

React 18: For UI logic and state management.

Tailwind CSS: For styling and responsive design.

Web Audio API: For synthesized sound effects (Buzzers, Chimes, Fanfare) without external audio files.

Created for the classroom.
