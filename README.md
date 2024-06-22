# AI02_Final-project STUDY PLANNING FOR ICI STUDENTS
## Overview
This project aims to provide an advanced tool designed to assist students at the International College of Innovation (ICI) in creating comprehensive and personalized study plans. It tailors these plans to each student's preferred field of study, career aspirations, and academic goals.
## Features
- Personalized study plan generation
- Integration with ICI's academic data
- Career-oriented recommendations
- User-friendly chatbot interface
#### Data Collection
The data for this project was collected from the ICI school website and compiled into an Excel file, which includes course titles, descriptions, teachers, credits, and schedules.
#### Installation
To run this project, follow these steps:
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/AI-Study-Planner-Chatbot.git
    ```
2. Navigate to the project directory:
    ```bash
    cd AI-Study-Planner-Chatbot
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

#### Usage
1. Run the Jupyter notebook to interact with the chatbot:
    ```bash
    jupyter notebook notebooks/study_planner.ipynb
    ```
2. Follow the instructions in the notebook to generate your study plan.

#### Project Structure
```
AI-Study-Planner-Chatbot/
│
├── README.md
├── data/
│   └── ICI Data Collection.xlsx
├── notebooks/
│   └── study_planner.ipynb
├── src/
│   └── main.py
├── requirements.txt
└── .gitignore
```

#### Input
- Keywords of the Study Field
- Academic Goals and Preferences

#### Output
- Course Lists for Each Year
- Career Path Suggestions
- Academic Goal Roadmap
- Professor’s Name for tailored recommendations

#### Limitations
- Incomplete Data: The effectiveness of the AI Study Planner heavily relies on the availability and accuracy of the course details, career path data, and academic goals. Any missing or outdated information can lead to suboptimal recommendations.
- NLP Limitations: The natural language processing models might not perfectly understand the nuances and context of the students' input, leading to less accurate recommendations.
- Limited Personalization: The planner might not account for all individual student preferences and unique circumstances, leading to generic recommendations.
Scope of Academic Goals: The planner might not fully support all academic goals, especially those that are highly specialized or unconventional.
