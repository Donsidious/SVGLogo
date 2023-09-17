# SVG Logo Maker

## Week-10 Challenge

## Table of Contents

1. [Description](#description)
2. [Screenshots](#screenshots)
3. [Technologies Used](#technologies-used)
4. [Installation](#installation)
5. [Features](#features)
6. [Usage Information](#usage-information)
7. [Contribution Guidelines](#contribution-guidelines)
8. [Test Instructions](#test-instructions)
9. [License](#license)
10. [Questions](#questions)

---

## Description

This application allows freelance web developers to create simple logos for their clients and projects, eliminating the need to hire a graphic designer. It utilizes Inquirer to prompt users within the command line for logo customization options, including text content (up to 3 characters), text color, logo shape (triangle, square, or circle), and shape color. Once the user answers these prompts, the application generates an SVG file based on their selections. The SVG file is then saved to the root directory of the application. The user can then open the SVG file in their browser to view the logo.


This project also marks the first implementation of unit testing within the applications. It includes one test suite with three tests, verifying that the codebase delivers correct shapes and colors. Building this application provided insights into what back-end developers can achieve without a user interface. It emphasizes the value of unit testing, which can be scaled for larger codebases and is essential for collaborative projects. Additionally, the application incorporates error handling, preventing logo generation if the user enters more than three characters.

Future development for this application could include enhanced error handling for SVG colors, additional unit testing, and the addition of more polygons and font styles for users to choose from. The application could also be expanded to include a front-end user interface, allowing users to view their logo in real-time as they make selections. This would require the use of front-end technologies such as React, HTML, and CSS.

#/# Screenshots

https://github.com/Donsidious/SVGLogo/issues/1#issue-1899810938



### Examples of Generated Logos

<img width="226" alt="Screenshot4-week-10-challenge" src="https://user-images.githubusercontent.com/120127903/232142654-9a5a9937-e831-4838-86a1-4323c7b9cc39.png">

<img width="245" alt="Screenshot5-week-10-challenge" src="https://user-images.githubusercontent.com/120127903/232142705-29cd92d9-1c12-46ce-a81a-64893ac15a00.png">

<img width="214" alt="Screenshot6-week-10-challenge" src="https://user-images.githubusercontent.com/120127903/232142727-5c9ce441-1ca7-443a-bb5f-391b3f0003cf.png)

## Technologies Used

- Node.js v16
- Inquirer v8.2.4 (Node Package Manager)
- File system module (Node Package Manager)
- Jest v29.5.0 (Node Package Manager) for unit testing

## Installation

1. Clone the repo:
   ```
   git clone https://github.com/rmessett15/SVG-Logo-Maker.git
   ```

2. Open in VS Code. If you do not have VS code, you must install it.

3. Using the terminal, install Node.js v16. If you have Homebrew, the command should look like the following (`brew install node@16`), however, this may vary, and the documentation should be consulted.

4. Once Node.js v16 is installed, in the terminal, utilize the command `npm init -y` to initialize and create a package.json where project files will be stored.

5. Next, use the terminal to run the command `npm i` to install the dependencies associated with this application. Developers may need to install Inquirer and Jest directly from the command line. To do so, the command for Inquirer will be `npm i inquirer@8.2.4` to install v8.2.4 of Inquirer, and `npm i jest` to install the latest version of Jest.

6. To run the application, within the terminal, type the command `node index.js`.

## Features

Features of this application include the user's ability to generate logos quickly and easily through the use of SVG files, entirely from the command line. No UI (user interface) needed, and no front-end tools needed.

## Usage Information

To run this application: 

1. Use the command line to navigate to the directory of the application.
2. Install all dependencies by running: `npm install`.
3. Type the command: `node index.js`.
4. Answer a series of questions. Once all questions are answered correctly, a message will indicate that your logo has been generated. Find your new logo in the newly generated SVG file.

For unit testing instructions, please refer to the [Test Instructions](#test-instructions) section.

## Contribution Guidelines

Open to collaboration. If you choose to do so, open an issue and modify any changes you would like to see on a feature branch and wait for approval before merging to the main branch.

## Test Instructions

To run unit testing, open the terminal and use the command `npm run test`.

As of now, there is one test suite with three tests. The test suite checks for a `render()` method to return a string for the corresponding SVG file with the given shape color.



![Screenshot8-week-10-challenge](https://user-images.githubusercontent.com/120127903/232142745-dfe8aab8-4da0-4e8f-89b6-d153f2024825.png)

![Screenshot9-week-10-challenge](https://user-images.githubusercontent.com/120127903/232142780-b9158992-dced-4da8-be89-e828b81f6023.png)

## License

NOTICE: This application is covered under the MIT License

