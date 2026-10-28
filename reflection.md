\# Lab 5 - Reflection



\## 1. What did you learn about static code analysis?



I learned that static code analysis helps identify programming issues without executing the code. Pylint checks code quality and conventions, Bandit detects common security vulnerabilities, and Flake8 identifies formatting and style problems.



\## 2. Which issue was the most important to fix and why?



The SQL injection issue was the most important because constructing SQL queries using string concatenation can allow untrusted input to alter the query. Parameterized SQL queries separate the SQL statement from the supplied values and help prevent this vulnerability.



\## 3. Did static analysis find every possible issue?



No. Static analysis is useful for identifying many common problems, but it cannot guarantee that a program is completely correct or secure. Testing and code review are still necessary.



\## 4. How did the code quality improve?



The Pylint score improved from 4.69/10 to 10.00/10. Bandit reported no remaining issues, and Flake8 reported no formatting violations. The code also became easier to read and maintain through consistent naming, documentation, and formatting.



