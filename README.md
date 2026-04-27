# Software Engineering Task 1: Study Quiz Generator
**Interactive Educational Product for Software Engineering Students**

## Project Overview
This project is an interactive, web-based educational tool designed to help students learn and review core Programming and Software Engineering concepts. It was developed to demonstrate the application of structured algorithms, modular programming, and version control.

### Purpose & Context
The goal of this software is to provide an intuitive interface where users can test their knowledge of variables, control structures, and development cycles. It was built using a **Software Development Life Cycle (SDLC)** approach, moving from requirements gathering to algorithmic design and finally implementation.

---

## Technical Features (Part B Requirements)

### 1. Data Structures
The application utilizes an **Array of Objects** (`quizData`) to store and manage the question bank. This allows the software to be scalable—new questions can be added to the data structure without changing the core logic of the program.

### 2. Subprograms & Parameter Passing
The code is modularized into several key subprograms to ensure readability and reuse:
* `loadQuestion()`: Initializes the UI and iterates through the data.
* `handleAnswer(userChoice)`: **Accepts a string parameter** from the user's action and performs selection logic.
* `showResults()`: Handles the end-of-session state.

### 3. Control Structures
* **Sequence:** The logical flow from loading questions to displaying results.
* **Selection:** `IF/ELSE` statements used to validate user answers and calculate scores.
* **Iteration:** Using `.forEach` to dynamically generate HTML buttons based on the number of options in the data structure.

---

## Repository Structure
* `/src`: Contains the primary `index.html` file (HTML5, CSS3, and JavaScript).
* `/docs`: Contains System Documentation, including:
    * `requirements.md`: Requirements and User Specifications.
    * `algorithms.md`: Structure Charts and Pseudocode.
    * `data_and_debugging.md`: Data Dictionary and Bug Log.
* `/assets`: Images and diagrams.

---

## Version Control & Collaboration
This project follows industry-standard **Git** workflows:
* **Weekly Commits:** Regular updates demonstrating the evolution of the software.
* **Branching:** Features were developed on separate branches before being merged into the main line.
* **Pull Requests:** Managed pull requests to simulate a collaborative engineering environment.
