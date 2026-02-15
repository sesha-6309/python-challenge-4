 Student Risk Score Analyzer
 Overview

This Python program analyzes student scores and categorizes them into different risk levels. It also applies personalized filtering based on the last digit of the registration number and tracks valid, ignored, and removed entries.

 Objective

To categorize student scores into risk levels

To apply personalized filtering logic

To count valid and ignored inputs

 Features

Accepts multiple student scores as input

Ignores negative (invalid) scores

Categorizes valid scores into:

Low Risk (0–30)

Medium Risk (31–60)

High Risk (61–100)

Critical Risk (Above 100)

Applies personalized filtering:

Even registration digit → Removes Low Risk scores

Odd registration digit → Removes Critical Risk scores

Displays total valid, ignored, and removed entries

🛠 Technologies Used

Python

Lists

Loops

Conditional Statements

 How to Run

Open Python (IDLE / VS Code / Terminal).

Copy and run the program.

Enter the number of scores.

Enter your registration number.

Enter the scores when prompted.

Output

The program displays:

Risk categories before filtering

Risk categories after filtering

Total valid entries

Ignored entries

Removed entries due to personalization
