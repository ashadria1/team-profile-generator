# Template Engine - Team Profile Generator

I have built a Node CLI that takes in information about employees and generates an HTML webpage that displays summaries for each person. Since testing is a key piece in making code maintainable, I will also be ensuring that all unit tests pass.

## Functionality

This application will prompt the user for information about the team manager and then information about the team members. The user can input any number of team members, and they may be a mix of engineers and interns. When the user has completed building the team, the application will create an HTML file that displays a nicely formatted team roster based on the information provided by the user.

## User Story

```
As a manager
I want to generate a webpage that displays my team's basic info
so that I have quick access to emails and GitHub profiles
```

## How

How did I build this? I used the [Inquirer npm package](https://github.com/SBoudrias/Inquirer.js/) to prompt the user for their email, id, and specific information based on their role with the company. I used [File System npm package](https://github.com/OptimalBits/fs.js) to build the HTML page with data input by the user. I used the npm package [Jest 🃏 Delightful JavaScript Testing](https://www.npmjs.com/package/jest) to run unit tests. The demo video demonstrates the process of installing all these npm packages and running unit tests with npm run test.

### User input

The app will prompt the user to build an engineering team. An engineering
team consists of a manager, and any number of engineers and interns.

### Roster output

The app will generate a `team.html` page in the `output` directory, that displays a nicely formatted team roster. Each team member will display Name, Role, ID, and a Role-specific property (School, link to GitHub profile, or office number).

## Relevant links:

![Screenshot of unit tests in action!](Develop\Assets\Unit-Tests-Pass.PNG?raw=true "Screenshot of unit tests in action!")

- The URL of the GitHub repository:

https://github.com/ashadria1/Team-Profile-Generator

- A video demonstrating the entirety of the app's functionality:

https://github.com/ashadria1/Team-Profile-Generator/blob/main/Develop/Assets/Team-Profile-Generator-Demo.wmv

![Screenshot of Unit Tests passing](Assets\Unit-Tests-Pass.PNG "Screenshot of Unit Tests passing")


