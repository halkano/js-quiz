# JavaScript Online Quiz
#### This is a project of a short javascript quiz, 18th August 2018
#### By **Maryann Gitonga**
## Description
This is an online quiz website that hosts questions on JavaScript, allowing the user to check their answers in radio buttons and in the end one is given an output of their score.
## Setup/Installation Requirements
To start using this project use the following commands:

* `git clone https://github.com/MaryannGitonga/js-quiz.git`
* `cd js-quiz`
* `atom .`
* `code . `(this is if Visual Studio Code is your preferred text editor)
##Behavior Driven Development
* The program should return an alert when none of the radio buttons has been checked:

      **Input Example**: no checked answer

      **Output Example**: Please answer question(number specified according to the current question not answered) to proceed!

    If it's the last question:

      **Input Example**: no checked answer

      **Output Example**: Please answer question(number specified according to the current question not answered) to submit answers!

* The program should return this when the input is a wrong answer is checked:

      **Input Example**: wrong answer

      **Output Example**: input value = 0

* The program should return this when the correct answer is checked:

      **Input Example**: right answer

      **Output Example**: input value = 10

* The program should return the Submit Answers button is clicked when all questions are answered:

      **Input Example**: Click on Submit Answers

      **Output Example**: You have scored (the number of points the user has attained) .

## Link to Live Website
http://maryanngitonga.github.io/js-quiz/
### License
MIT License

Copyright (c) 2018 Moringa School

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
