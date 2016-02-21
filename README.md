# Shift
### Description
- As part of the Work/Study program of the university students are assigned a limited quantity of hours per semester that they must complete. These hours must be tracked and it is currently being done in paper by signing every time you start a shift and end it.  At the end of the month the student turns in the signing sheet and sees how much hours he has left. Keeping track of the remaining hours is easy for the student but it is very tedious for the manager to keep track of the remaining hours for each student. We propose a Mobile-First Web-App called Shift where students login to submit their working shifts and keeps track of these hours at an individual level, and at the level of the manager.

###How to install and get it running.
1. Configure SSH communication with github. [Guide](https://help.github.com/articles/generating-an-ssh-key/)
2. Clone github repository using  your terminal:
	- cd your_workspace/
	- git clone git@github.com:xTrot/shift.git
3. Install dependencies(npm must be installed):
	- cd your_workspace/shift/
	- npm install (needs admin priviledges)
4. Run server:
	- npm start
