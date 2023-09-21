## QuantumCaptcha

This is a captcha that challenges users to solve a random quantum physics or calculus problem. Based on JS and HTML.

**Overview**

The captcha displays a randomly generated physics or calculus problem in the UI. Users enter the solution to the problem. When the form is submitted, the solution is checked. If correct, a new random problem is generated. If incorrect, the user is shown the same problem again.

**Code Overview**

* `generateProblem()`: Generates a random quantum or calculus problem.
* `generateQuantumProblem()`: Generates a quantum physics problem.
* `generateCalculusProblem()`: Generates a calculus problem.
* The submit handler checks the solution and generates a new problem.

**To Do**

* Improve UI/UX.

**Usage**

To use the captcha:

1. Open `index.html` in a browser.
2. Fill in the solution to the displayed problem.
3. Click submit.
4. If incorrect, repeat steps 2 and 3.
5. If correct, a new problem will display.
