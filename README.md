Compose Calculator (CMSC 495)

A modern calculator application for Android built with Kotlin and Jetpack Compose.
This project focuses on Compose UI layout, state handling, and collaborative development using GitHub, with a custom visual theme.


Features

Basic arithmetic operations: addition, subtraction, multiplication, and division

Decimal input with formatted output

Toggleable calculation history panel

Custom UI theme using dark ink tones, gold operators, and plum accents

Fully Compose-based UI using Material 3 components

Concise inline comments for readability and collaboration


Core Controls

AC — clears all input and resets the calculator

⌫ — removes the last entered character

⏱ — shows or hides calculation history

= — evaluates the current expression


UI Design Notes

The interface uses a centralized color palette to keep the visual style consistent and easy to modify.

Deep ink tones are used for the app background

A parchment-style display improves contrast and readability

Operator buttons are highlighted in gold to stand out from number keys

Plum accents are used sparingly for visual interest

All UI colors are defined in a single palette object, allowing the theme to be adjusted without changing layout or logic.

Built With

Kotlin

Jetpack Compose

Material 3

Android Studio

State is managed directly in Compose using remember and mutableStateOf to keep the logic straightforward and appropriate for the project scope.

Getting Started
Prerequisites

Android Studio Iguana (2023.2.1) or newer

Android emulator or physical Android device

Installation

Clone the repository:

git clone https://github.com/jsadegh/AndroidCalculatorCMSC495.git


Open the project in Android Studio

Allow Gradle to sync and install dependencies

Run the app on an emulator or device

Usage

Use the number and operator buttons to build an expression

Press = to calculate the result

Use ⌫ to delete the last character

Tap ⏱ to toggle the history panel

Press AC to clear all input

The display automatically formats whole numbers and decimals for clarity.

Collaboration and Git Workflow

This project was developed collaboratively using GitHub branches and pull requests.

UI theming and documentation updates were made on feature branches

Pull requests were used to merge changes cleanly and avoid conflicts

Each pull request clearly describes what was changed and what remained untouched

This workflow reflects standard collaborative development practices.

Contributing

Suggestions and improvements are welcome.

To contribute:

Fork the repository

Create a feature branch

git checkout -b feature/YourFeatureName


Commit your changes

Push to your branch

Open a pull request

License

Distributed under the MIT License.
See the LICENSE file for more information.

If you want, I can:

Tighten this further to match a grading rubric

Add a short design rationale section for instructors

Write a one-paragraph submission blurb you can reuse elsewhere

You’re in excellent shape — this looks intentional, not rushed.

make it warmer and a bit more... idk whatever you think would be a good addition fo a college capstone readme section

Absolutely — for a college capstone, the README benefits from a bit more voice and reflection while still staying clean and professional. The goal is to show intent, learning, and design thinking, not just features.

Below is a warmer, slightly more human version with one added capstone-style section that professors tend to love. Still clean. Still professional. Just more you.

Compose Calculator (CMSC 495)

A modern calculator application for Android built using Kotlin and Jetpack Compose.
This project was developed as part of the CMSC 495 capstone and focuses on UI design, state management, and collaborative software development using GitHub.

Rather than aiming for feature overload, this calculator emphasizes clarity, polish, and maintainable structure—both in code and in design.

Screenshot

Features

Basic arithmetic operations: addition, subtraction, multiplication, and division

Decimal input with clean, formatted output

Toggleable calculation history panel

Custom dark UI theme using gold, plum, and ink tones

Fully Compose-based layout using Material 3

Clearly commented code to support team collaboration

Core Controls

AC — clears all input and resets the calculator

⌫ — removes the last entered character

⏱ — shows or hides calculation history

= — evaluates the current expression

UI Design Approach

The calculator uses a centralized color palette to keep the interface cohesive and easy to adjust.

Deep ink tones create a calm, low-contrast background

A parchment-style display improves readability and visual balance

Gold operator buttons guide the eye toward primary actions

Plum accents add character without distracting from usability

All colors are defined in a single palette object, allowing the theme to evolve without impacting layout or logic.

Built With

Kotlin

Jetpack Compose

Material 3

Android Studio

State is handled directly in Compose using thoughtful remember and mutableStateOf usage to keep logic readable and appropriate for the scope of the project.

Capstone Focus and Learning Outcomes

This project was designed to reflect the goals of a capstone course by prioritizing:

Readable, maintainable code over unnecessary complexity

Intentional UI design, rather than default styling

Team-based development practices, including branching, pull requests, and code review

Clear documentation that explains both what the app does and why design decisions were made

Through this project, the team gained hands-on experience working with Jetpack Compose, managing shared codebases, resolving merge conflicts, and making UI decisions collaboratively.

Getting Started
Prerequisites

Android Studio Iguana (2023.2.1) or newer

Android emulator or physical Android device

Installation

Clone the repository:

git clone https://github.com/jsadegh/AndroidCalculatorCMSC495.git


Open the project in Android Studio

Allow Gradle to sync and install dependencies

Run the app on an emulator or device

Usage

Use number and operator buttons to build an expression

Press = to calculate the result

Use ⌫ to delete the last character

Tap ⏱ to view calculation history

Press AC to reset the calculator

Results are automatically formatted for clarity, displaying whole numbers cleanly and trimming unnecessary decimal zeros.

Collaboration and Git Workflow

This project was developed collaboratively using GitHub.

Features and UI changes were developed on separate branches

Pull requests were used to merge changes cleanly

Descriptions clearly outlined what was modified and what remained unchanged

This workflow mirrors common professional development practices and ensured a stable main branch throughout development.

Contributing

Suggestions and improvements are welcome.

To contribute:

Fork the repository

Create a feature branch

git checkout -b feature/YourFeatureName


Commit your changes

Push to your branch

Open a pull request

License

Distributed under the MIT License.
See the LICENSE file for more information.
