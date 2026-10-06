
##  Angular AI In Depth (with Cursor and Claude Code) 

This repository is updated to Angular v22.

![Angular AI In Depth (with Cursor and Claude Code)](https://d3vigmphadbn9b.cloudfront.net/course-images/large-images/angular-ai-in-depth.jpg)

# Installation pre-requisites

Please install Node 24 Long Term Support Edition (LTE).
# Installing the Angular CLI

With the following command the angular-cli will be installed globally in your machine:

    npm install -g @angular/cli

# How To install this repository

We can install the master branch using the following commands:

    git clone https://github.com/angular-university/angular-ai-in-depth.git

After cloning, it's recommended that you install using npm ci. This way you will get the exact dependencies of package-lock.json:

    cd angular-ai-in-depth
    npm ci

    npm install 

This should take a couple of minutes. If there are issues, please post the complete error message in the Questions section of the course.

# To Run the Development Backend Server

We can start the sample application backend with the following command:

    npm run server

This is a small Node REST API server.

# To run the Development UI Server

To run the frontend part of our code, we will use the Angular CLI:

    npm start 

or simply:

    ng serve 

The application is visible at port 4200: [http://localhost:4200](http://localhost:4200)


It's also possible to download a ZIP file for a given branch,  using the branch dropdown on this page on the top left, and then selecting the Clone or Download / Download as ZIP button.
