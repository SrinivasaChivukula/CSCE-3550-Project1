\# CSCE 3550 – Project Repository



This repository contains my solutions for the CSCE 3550 course projects.  

Projects are designed to be graded automatically using \*\*GradeBot 9000\*\*.



---



\## Requirements



\- \*\*Python 3.9+\*\* (already installed on most systems)

\- \*\*pip\*\* package manager

\- \*\*GradeBot 9000\*\* (provided by instructor – included in this repo as `gradebot.exe`)



---



\## Setup



1\. Clone or download this repository.



&nbsp;  ```bash

&nbsp;  git clone <repo-url>

&nbsp;  cd CSCE\_3550



2\. Each project has its own folder:

CSCE\_3550/

├── gradebot.exe

├── project1/



3\. Install dependencies for a project before running it:



&nbsp;  cd project1

&nbsp;  pip install -r requirements.txt





Running Projects with GradeBot



GradeBot does not start your server automatically.

You must start your server first, then run the GradeBot checker.



Example: Project 1



1. Start the server:



* cd project1
* python server.py



2\. Open a new terminal and run GradeBot:



* cd ..
* .\\gradebot project1



3\. GradeBot will connect to your server and run tests.

Scores and feedback are displayed in the terminal.



\## Example Work-Flow:

# Setup

cd project1

pip install -r requirements.txt



\# Run server

python server.py   # keep this terminal open



\# In another terminal

cd ..

.\\gradebot project1







