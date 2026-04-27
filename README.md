# Software Engineering Task 1: Study Quiz Generator
**My Interactive Website Project**

## About My Project
For this task, I designed and coded an interactive quiz website. The main goal was to create a tool that helps other students study for Software Engineering by testing them on things like programming logic and data types.

I didn't just write the code—I followed the whole development cycle. This meant planning out my requirements first, drawing a structure chart to see how the "bits" of my program fit together, and using GitHub to track my progress every week.

---

## How the Code Works (Part B Stuff)

To get the best marks, I made sure my code used the important structures we learned in class:

### 1. Data Structures
Instead of making a new page for every question, I used an **Array of Objects** called `quizData`. This is basically a big list that holds all my questions, options, and the correct answers in one spot. It’s cool because I can add 100 more questions to the list and the code will still work perfectly.

### 2. Subprograms & Passing Parameters
I broke my code into "subprograms" (functions) so it wasn't just one big mess:
* `loadQuestion()`: This runs every time a new question pops up.
* `handleAnswer(userChoice)`: This is a subprogram that uses **parameter passing**. It takes the button the user clicked (the parameter) and checks it against the right answer.
* `showResults()`: This only runs at the very end to show your total score.

### 3. Logic & Control Structures
* **Selection:** I used `if/else` statements to decide if the user got the point or if they got it wrong.
* **Iteration:** I used a `.forEach` loop. This "iterates" through my list of options to create the buttons automatically.
* **Sequence:** I made sure the code runs in the right order—you can't see your score until you finish the questions!

---

## What's in this Repo?
* **/src**: This is where my `index.html` file lives. It has all my HTML5, CSS3, and JavaScript code.
* **/docs**: My planning work, like my structure charts, pseudocode, and my bug log (where I wrote down the errors I fixed).
* **/assets**: Photos of my diagrams.

---

## Version Control
I used GitHub to manage this project. I didn't just upload it all at the end! If you look at my **commits**, you can see how I added the UI first, then the logic, and then fixed bugs. I also used **Pull Requests** to show how I can manage my code like a real software engineer.

---

## How to play
1. Download the `index.html` file.
2. Open it in Chrome or any browser.
3. Try to get 9/9!
