# Python News Feed
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

This Python News Feed application was a refactoring exercise where I was able to learn how to replicate an existing Node application using Python. This application allows users to create accounts, login, and create posts, or upvote and comment on other users' posts. This site's purpose is to allow users to post links to helpful tech articles and foster discussion and education.

Some of the key learning points include:

* Setting up a Python/Flask work environment
* Building routes with Blueprint and @route decorators
* Connecting to and querying an SQL database using the SQLAlchemy ORM and Flask
* Defining models using Python classes
* Handling errors using the "assert" keyword and "try ... except" statements
* Importing custom filters into Jinja templates for clean and accurate formatting
* Managing database connections using the Flask context
* Leveraging Flask session and redirect for persistent login functionality
* Using custom decorator function to act as middleware protecting secure routes from logged out users

## Table of Contents
        
- [Installation](#installation-if-you-would-like-to-clone-the-repo-and-work-from-the-backend-otherwise-simply-visit-the-deployed-application)
- [Link to Deployed Application](#link-to-deployed-application)
- [Credits](#credits)
- [License](#license)
- [Contributing](#contributing)
 
## Installation (if you would like to clone the repo and work from the backend; otherwise simply [visit the deployed application](https://morning-tor-74579-9e2c56a00e99.herokuapp.com/)) 
1. Install Python
    - [Download Version 3.8 or greater of Python](https://www.python.org/downloads/)
2. Clone this repo
   ```sh
   git clone https://github.com/michael-loeffler/python-newsfeed
   ```
3. Install the dependencies included in the requirements.txt file
   ```sh
   npm i
   ```
4. Start the server by using the following command in the command-line
   ```sh
   python -m flask run
   ```
5. Open the site on your local host (e.g., http://127.0.0.1:5000)

## Link to deployed application
[https://morning-tor-74579-9e2c56a00e99.herokuapp.com/](https://morning-tor-74579-9e2c56a00e99.herokuapp.com/)

Preview: 

![](Preview%20-%20Python%20News%20Feed.png)

## Credits
Most of the application's front end was supplied from EDX Coding Bootcamp continuation courseswork as this was a refactoring exercise.

Python Libraries used:
  - Flask
  - Jinja2
  - bcrypt
  - PyMySQL
  - SQLAlchemy
  - python-dotenv
  - Gunicorn

## License
    
Covered under the MIT License. For more details and to view the license in full, please visit the [MIT License Webpage](https://choosealicense.com/licenses/mit/).

## Contributing
    
If you have a suggestion for improvement, please fork the repo and create a pull request. You can also open an issue and tag it for "enhancement".
1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/featureName`)
3. Commit your Changes (`git commit -m 'adds featureName'`)
4. Push to the Branch (`git push origin feature/featureName`)
5. Open a Pull Request