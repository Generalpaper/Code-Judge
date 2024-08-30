# Code-Judge
A judge to check your cp, to see if you are a true cp enjoyer.

# What it does.
It allows you to host your competitive programming competitions.
Users can login to use the website. Logins will be done using github.com or regular email.

Things I need to create:
Login system
Contest creator
Code Sandbox 

# Tech Stack Ideas
1. Support C++, Golang, Java and Python to run in sandbox
It has to use specific interpreters to run each language
* Python: Python interpreters such as CPython are used, often with specific configurations to ensure consistent performance.
* Java: Java Virtual Machine (JVM) configurations are optimized for performance evaluation.
* C++: Specific compiler versions and flags are used to ensure consistent performance.
* JavaScript: JavaScript engines such as V8 or Node.js are used for execution.
2. It will be server-side execution.
3. Backend will be done with standard library go (glhf) 
Other frameworks to consider are (Go:Gin, Echo, C++:Pistache, CppCMS, JS: Node.js)
4. Use a docker to create containers for each supported language Each container should have its own runtime environment and resoucre limits
Execution Logic
* Validate: Ensure the code and input parameters are safe
* Execute: Run the Code in a Docker container.
* Virtual Machines for more robust isolation
* Capture Output: Collect and return output to the user
* Cleanup: Ensure containers are cleaned up after execution to free resources
* Judge0 can be considered, but it may not return reliable runtimes
5. Code Editor
Monaco Editor, which is also the editor in VSC
6. Test with Postman
make 
7. Security
* Logs: Detailed logs of code execution, including errors and performance metrics.
* Alerts: Alerts for abnormal behavior or performance issues.
* Security and Compliance: Ensuring the security of the code execution environment involves continuous security assessments, patch management, and compliance with best practices in security.

# Stuff to learn
1. re-learn my full-stack basics
2. Golang standard library
3. Docker
4. Each language respective interpreter / compiler or judge0
5. Security considerations.