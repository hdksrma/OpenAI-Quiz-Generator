# Quiz Generator

The Quiz Generator and Grader is a project that allows teachers to generate quizzes and exams automatically based on the input they provide. The project uses OpenAI's completion API, Jupyter Notebook, and Python to create quizzes with a specific topic, number of questions, and number of options per question. The project also includes an exam simulation and an automatic grading system.

## Getting Started

To use the Quiz Generator and Grader, you will need to have a Jupyter Notebook environment set up on your machine. You will also need to have an API key from OpenAI to use their completion API.

Once you have these prerequisites, you can clone the project code from this GitHub repository and open the `Quiz_Generator.ipynb` file in your Jupyter Notebook environment.

## Usage

To use the Quiz/Test Generator and Grader, follow these steps:

    1. Start by providing a topic, number of questions, and number of options per question in the provided cell.

    2. Run the cell to generate a quiz or exam based on your inputs.

    3. Use the generated quiz or exam to test your students' knowledge.

    4. Run the grading cell to grade the quiz or exam automatically.

## Example Input and Exam Simulator

### Input

```
Topic: "Python"

Number of questions: 4

Number of options per question: 4 

```

### Exam Simulator

```
Q1. What type of language is Python?

A. Compiled 

B. Scripted

C. Object-oriented

D. Machine language

Enter your answer: b


Q2. What is the primary use of Python?

A. Web development

B. Mobile application development

C. Desktop application development

D. Data analysis

Enter your answer: d

Q3. Which of the following is not a core data type in Python?

A. Lists

B. Strings

C. Tuples

D. Classes

Enter your answer: d

Q4. What is the correct syntax to print the word 'Hello' in Python?

A. println(Hello)

B. print('Hello')

C. printf(Hello)

D. log('Hello')

Enter your answer: b

```

### Automatic grading

```

'3 out of 4 correct! You achieved: 75.0 % : Passed!'

```
