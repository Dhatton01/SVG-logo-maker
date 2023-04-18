# svg-logo-maker
![License Badge](https://img.shields.io/badge/license-MIT-brightgreen)

## User Story
As a freelance web developer, I want to generate a simple logo for my projects, so that I dont have to pay a graphic designer. (You really should hire a graphic designer if you want a professional designed logo)

## Description
* This is a command-line application, which will generated a logo svg file. This app will prompt the user for text (up to 3 characters long), a text colour and a background colour for the logo. All colour must be a css named value or in hex code. The user can choose from circle, triangle or square as the shape of the logo.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [How to Contribute](#how-to-contribute)
- [Questions](#questions)
- [License](#license)

## Installation
* In the root directory you want to run "npm i" to install all the required packages.

## Usage
* User can type "npm start" or "node index.js" to start the user prompt in the root directory.
* The user must pass all the requirements of making the svg logo, otherwise it will prompt a corresponding error message.
* Upon finishing all the questions, a svg file will be generated called logo.svg in the dist folder.

* This project uses the npm inquirer, is-css3-color and jest for testing.

## Tests
* Its been tested for correct user input, logo text must not exceed 3 characters and must contain atleast 1 character.
* It must be a vaild CSS named value or hex code to set the text colour of the logo and the background colour of the logo.
* These tests must be passed in order for the logo.svg file to be generated.

