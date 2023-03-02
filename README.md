


# WDP Team Project

## Project description
The project is an example of a furniture store website coded from a free PSD template, in accordance with the client's guidelines based on JavaScript, SCSS, Redux, React technologies. Based on Bootstrap, so easy to expand, flexible. Lightweight, no heavy plugins. Compatible with RWD.

## Demo
Live demo here.

## Menu
Two language versions to choose from - Polish and English.

Ability to create an account or purchase without registration.

## Main page
Possibility to compare and buy the product from the home page. For those interested, a detailed product card.
Quick change of the number of displayed products.
Intuitive product rating system.
Ability to quickly update prices while leaving the old price.
A friendly and simple product purchase system.

## Blog
Current blog entries always on top
Ability to edit and add new entries
Ability to comment on entries

## Technologies
Bootstrap: 4.6.0
SASS - 4.14.0
Flexbox-grid: 2.1.2

## Directory structure
The structure of the files is arranged in accordance with the applicable rules:

src source directory
components: (components divided into categories) common, features, layout, views
redux (files related to Redux support)
styles (each section has a separate .scss style file)
class names correspond to individual sections to which they are assigned

## Project initiation
After cloning the project, install the required packages with yarn install (or npm install).
You can get started using the prepared yarn start (or npm start) tasks.
All the source files needed to work are in the src and public folders.

## NPM Scripts
There are 3 main scripts to speed up your work:

build: based on the files from the src and public folders, it builds a project in the build folder.
start: observes changes in the src folder and starts a working preview.
test: run unit tests.
refactor: the script automatically formats the files in the src/ folder according to the accepted code formatting convention, and also checks for errors using ESLint.
Git Hooks
The project uses Git Hooks - the ability to run scripts in response to selected Git program events. Each time you execute a git commit command, unit tests, formatting and linting will be run for the files that have been selected with git add and are to be saved in the commit.

## Conventions and good practices
Work standards:

Styles used in component files. We assign them variables with color names, e.g. "$footer-claim-bg: $darkGray" in settings.js. We do not use styles like "$white: #ffffff;"
We follow previous arrangements in settings.js and on the website, e.g. transition time for hovers, their colors and styles.

For a more efficient workflow:

Once a week we made a 45-minute video-meeting of the whole team.
Every day, each of us kept the rest informed of our progress via DAILY.
Everyone assigned tasks with the help of Jira.
Each of us kept order on the Kanban board and selected 1-3 tasks from the top.
Each task corresponded to a branch from the current master, with the same number.
Our PM had the ability to merge, to whom a Pull Request with a short description had to be sent each time.
Commits should be relatively short and concise, specifying what we did or what problem we solved.
When setting up PR, stick to the name of the task from which we create PR and try to describe the problem and the solution to the problem.
exploitation
Most of the text content in components is taken directly from state, thanks to which you can easily edit, for example, the text of the displayed component, section and photo data.

## Troubleshooting
Due to the use of different developer software, conflicts may occur in package-lock.json and yarn.lock. In this case it is recommended to remove them and reinstall either yarn install or npm install.

## Project status
The project is still being developed and stabilized.

