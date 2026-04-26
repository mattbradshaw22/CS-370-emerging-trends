# CS-370-emerging-trends
ML pathfinding agent for a matrix based maze
---
---
Briefly explain the work that you did on this project: What code were you given? What code did you create yourself?
---

We were given the GameExperience.py and TreasureMaze.py files as well as a large chunk of the starting code in the TreasureHuntGame.py file. The section for completing the q training algorithm has a comment start here where I wrote the code to get the model to train. It takes a random free cell as the starting point for the pirate and resets the maze. It observes the state of the environment and then makes moves that are valid actions amd gets the environment state reward and action from each move the agent makes to store in the replay memory. when the game ends in either a win or loss if the agent makes to many moves without reaching the treasure, the epoch is recorded as a win or loss by adding to the win count or not adding to it. Each move in the game is an episode so we can see how many moves it took the pirate to reach the treasure  or fail in each epoch


Connect your learning from throughout this course to the larger field of computer science:
---


What do computer scientists do and why does it matter?
---

Computer Science is a broad field where scientists can do many things from front end development working on user interfaces and web design to backend logic development getting the algorithms and functions working to efficiently complete goals. They also can create, manipulate, and work with datasets directly through databases in SQL or NoSQL databases or with backend functions connecting to them and even work with machine learning to use artificial intelligence to solve all sorts of problems


How do I approach a problem as a computer scientist?
---

Approaching any problem as a computer scientist involves critical thinking and logic. Breaking down bigger problems into their smaller pieces is a good way to gain understanding of the problem at a more fundamental level which helps approaching the problem to find real solutions. 


What are my ethical responsibilities to the end user and the organization?
---

Ethical issues are a large consideration in any aspect of life, but especially with something like computer science where any piece of code written may hold you responsible for peoples safety or personal information. Its important to examine ethical situations of anything you do or work on and make sure you are operating responsibly and diligently to minimize risks.
