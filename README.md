# Full Stack Development Preliminary 'Hello, World!' Exercise Using Node.js, Docker, React, and Github

The code contained in this repository was forked from https://github.com/hncj811/classIntro/tree/main, authored by
Morehouse Professor Hakeem Jones.

## Underlying Concepts & Supporting Technologies/APIs
It's highly recommended that programmers whoa are attempting to replicate this exercise or simply deploy the project 
be familiar with the following:
1. Github for code versioning
2. React for frontend development
3. Docker for containerizing and running apps
4. CLI for refactoring and modifying revision trees/working directories

If you haven't already, please perform the following set-up tasks to ensure your development environment, as well as
the site from which you'll deploy for React application is ready:

* Install node version manager (nvm), a tool for downloading and installing the Node.js JavaScript runtime environment: 
**Note: Node package manager (npm) is a tool that allows you to install JavaScript packages, and comes with Node.js**
Verify that both packages are installed with the following Linux command: npm/nvm --version

* Create a Github account and enroll an SSH key
Follow the directions at: https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent to generate and enroll
an SSH key for authenticating code versioning and revision management.

* Download Docker Desktop
Follow the instructions at: https://docs.docker.com/desktop/setup/install/mac-install/ for Mac users or 
https://docs.docker.com/desktop/setup/install/windows-install/ for Windows


## Core Dependencies
* ES6/ES2-15 JavaScript
This project uses ES6, a JavaScript specification containing a host of features supported by the suite of web
browsers with which programmers should be acquainted. ES6 ratified the majority of features and syntax that 
underly modern web development and should be used consistently to prevent deploying deprecated/legacy JavaScript, as well
as to ensure our code scales with further deprecations and the progression of JavaScript as a web/full-stack development
language. ES6 classes, in particular, are used in lieu of Function components to declare React components that are later
rendered in the website UI.

* react
This project uses the core React library for React 'Components', JSX(6/7) support, and rendering logic.

* react-dom
The project uses react-dom to connect the React app and browser Document Object Model (DOM) and is responsible 
for rendering React components into <div id="root">

* react-scripts
This module provides boilerplate like the development server, build tooling, and webpack configuration.

All required dependencies are defined in package.json and installed automatically via: npm install


## Getting Started

1. Fork this git repository
2. Clone this git repository by running the following in your terminal: git clone git@github.com:hncj811/classIntro.git (copied from Code > SSH)
3. Navigate to the root directory hosting the project files, something to the effect of: cd classIntro
4. Execute: 'npm install' on your local machine's install and while still in the working directory
5. Execute: 'npm audit fix' (if necessary to resolve vulnerabilities)
6. Execute: 'npm start' to deploy the React app 
7. You may be redirected to the site in your browser, but if not simply navigate to: https://localhost:3000
8. You may optionally containerize your React application via Docker, so that other may run your app without setting it up themselves: https://www.docker.com/blog/how-to-dockerize-react-app/. For example, you can access this project via Docker by running:
* docker pull pwilson2781/classintro, then
* docker run -p 80:80 pwilson2781/classintro

