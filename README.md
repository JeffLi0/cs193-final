# cs193-final
A study tracker web app with a to-do list and time tracking that runs on localhost.
 
## The Problem
 
I have a lot of things to keep track of over a lot of different platforms. For school I have to check Brightspace and Ed, and for extracurriculars there's a bunch of other apps to check. I built this so everything I need to keep track of is in one place, to help with time management.
 
## How It Works
 
studylog is a web page that runs on a local Node.js server at localhost:3000. On the page you can add to-dos with a class and due date, log study hours or run a timer, and see your hours for the week. The server saves everything to one JSON file so nothing is lost when you close the page.
 
MVP:
 
- Add and check off to-dos with a class and due date on the page
- Log study hours for a class
- Start / stop timer on the page
- Weekly view of hours per class and upcoming to-dos
- Local server on localhost that saves everything to `data/studylog.json`
![System diagram](docs/system-diagram.png)
 
![Eisenhower Matrix](docs/eisenhower-matrix.png)
 
## Tech Stack
 
- **Language:** JavaScript, HTML, CSS
- **Libraries:** Express, Day.js, Jest
- **External tools:** Node.js, npm, Git, GitHub, draw.io
## Roadmap
 
- [ ] Pull assignments from Brightspace and Ed automatically
- [ ] Reminders before something is due
- [ ] Charts of study time per class
- [ ] Edit or delete a to-do
- [ ] Recurring to-dos (weekly homework, club meetings)
## Author
 
Jeff Li, [JeffLi0](https://github.com/JeffLi0)