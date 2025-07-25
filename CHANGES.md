Major Issues identified in the previous version of code are:
1. I have made sure of making the different functionalities independent of each other making use of design principles in this way.
2. Before it is used to be like all logics was bundled into a single `app.py` file.
3. Making the code reusable /modular through seperation into different files.
4. Solved the problem of Inconsistent or incorrect use of HTTP status codes.
5. Made sure there are no security vulnerablities.
6. Debugged the previously provided code having raw sql queries through chatgpt which should be dealed correctly otherwise would be creating sql injections.
7. # Security Improvements
Replaced raw SQL with **parameterized queries** to prevent SQL injection..
Updated login logic to check hashed passwords.
8. Reorganized the code base to modular files like 
models.py, utils.py, routes.py etc..
9. Clean and readable `app.py` as the entrypoint.
10. Made sure of correctly handling the error messages.
11. Made use of Chatgpt for helping me work in a structered manner in a step by step format. Articulating the test cases generation according to the requirements I have provided.
