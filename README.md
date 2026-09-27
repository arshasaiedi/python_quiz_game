# Python Quiz Game
A simple quiz game built with python
## Table of contents

- [Table of contents](#table-of-contents)
- [Features](#features)
- [Project Structure](#project-structure)
- [Requirments](#requirments)
- [Installation](#installation)
- [Environment Setup](#environment-setup)
- [Usage](#usage)
- [Example Output](#example-output)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

## Features
- QUIZ SYSTEM
  - Asks the player multiple questions
  - Checks the answeres automatically
  - Calculates the final score 
- Result Storage
  - Saves quiz results in `result.txt`
- Admin Mode
  - Asks for the admin password
  - checks if th epassword is correct
  - keeps the private infromation outside the main python file
- loads the password from `.env`

## Project Structure
```text
python_quiz_game/
│   main.py
│   question.py
|   requirments.txt
│   .env.example
│   .gitignore
│   README.md
```
### File Description
- `main.py` - main file used to run quiz game
- `question.py` - stores questions and answers
- `requirments.txt` - lists the python packages needed for the project
- `env.example` - shows the environment variables needed by the project
- `gitignore` - tells git which files and folders should not be tracked
- `README.md` - contains the project documentation

## Requirments
Before running the project make sure you have
- `python 3`
- `python-dotenv`
  
## Installation
1. open a terminal in the project folder
2. check if python is installed
```bash
python --version
```
3. install the python packages
```bash
pip install -r requirments.txt
```
## Environment Setup
1. create a `.env` file from `.env.example`:
```bash
cp .env.example .env
```
2. open the new `.env` file
3. replace the example value with your own password
```text
QUIZ_ADMIN_PASSWORD=your_password_here
```
4. save the file
> Do not commit your `.env` file because it may contain private information

## Usage
1. open a terminal in project folder
2. run the quiz game
```bash
python main.py
```
3. choose `yes` or `no` for admin mode
4. if you choose `yes`, enter the password form your `.env` file
5. enter your name
6. answer the questions
7. see your final score and message
8. your results are saved in `result.txt`
## Example Output
```text
do you want to open admin mode? yes/no: no

what is your name? reza 
welcome

what language are we using?c
wrong

what command starts a git?git init
correct

what command shows git status?a
wrong

your score is: 1 out 3
keep practicing reza
```
## Roadmap
- [x] add multiple quiz question
- [x] calculate the final score
- [x] save results to a file
- [x] add admin mode
- [ ] add more quiz questions
- [ ] add difficulty levels
- [ ] add timer
## Contributing

## License

## Author
created by [Arsha Saiedi](https://github.com/arshasaiedi)