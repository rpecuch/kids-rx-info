# Kids-RX: Pediatric Electronic Health Records

  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

  ![HTML](https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![Font Awesome](https://img.shields.io/badge/Font_Awesome-339AF0?style=for-the-badge&logo=fontawesome&logoColor=white)

![MUI](https://img.shields.io/badge/MUI-%230081CB.svg?style=for-the-badge&logo=mui&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Apollo-GraphQL](https://img.shields.io/badge/-ApolloGraphQL-311C87?style=for-the-badge&logo=apollo-graphql)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)

![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=for-the-badge&logo=Sequelize&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

## Description

The purpose of this application is to provide an electronic system to keep track of patient records in a healthcare environment.

### Provider Login

Like other electronic health record (EHR) systems, features include appointment scheduling, creating patient charts, writing medical record notes, logging vital signs, and logging vaccination records. What makes Kids-RX different is that it is specifically designed for use in pediatrics and includes features that were implemented with children in mind. Additional functionalities that we would like to add in the near future include increasing the number of different calendar views, implementing electronic prescriptions, and adding more editing abilities. We also plan on making the patient charts much more detailed.

### Patient Login

Like other EHR patient portals, features include viewing upcoming and past appointments, medications, vaccines, and vital signs. Patients can also send and recive messages from their physician. What makes Kids-RX different is that it is specifically designed for use in pediatrics and includes features that were implemented with children in mind, including games for them to play while in a waiting room. Additional functionalities that we would like to add in the near future include more games that are higher complexity, as well as a platform that accepts donations to a children's hospital.

### Future Development

This application was built in two weeks, with our development team spending one week on the provider login and one week on the patient login. Because each login was built to meet the requirements of a different class project, different technologies were used in each. In the coming weeks a comprehensive application will be set up that combines both the provider and patient login.

## Table of Contents

  - [Installation](#installation)
  - [Usage](#usage)
    - [Providers](#providers)
    - [Patients](#patients)
  - [Collaborators](#collaborators)
  - [Credits](#credits)
  - [License](#license)
  - [Contributing](#contributing)
  - [Tests](#tests)
  - [Questions](#questions)

## Installation

  N/A

## Usage

### Providers

To access this application, visit the following URL: [https://kids-rx-emr.herokuapp.com/](https://kids-rx-emr.herokuapp.com/). Browse the homepage for business information, or select one of the options in the navigation bar at the top of the page

![homepage of application](./images/provider/homepage.png)

 Select "Staff Login" to login as a provider, or the user may create a new account.

 ![create account page](./images/provider/createacc.png)

 ![login page](./images/provider/login.png)

 Once the user is logged in, they will be taken to the dashboard. They may choose to view the schedule, view current patients, view the vaccination page, or view resources.

![staff dashboard page](./images/provider/dash.png)

The schedule page displays a list of appointments for the current day. The status may be changed when the patient arrives. To add a new appointment to the schedule, fill out the form at the top of the page.

![schedule page](./images/provider/schedule.png)

The patients page displays a list of the first 25 patients in the system alphabetically. To view a specific patient, use the search bar at the top of the page. 

![list of patients](./images/provider/pt-list.png)

The following information is contained in each patient chart: basic information (name, date of birth, etc), allergies, medical history, medications, vaccinations, guardian information, recent vital signs, upcoming appointments, and medical reports. The user may add a new medication, vaccination, appointment, medical report, or set of vital signs using the corresponding button. On the patient's birthday, click the corresponding button for a special surprise! In the future, we would like to implement the ability for the user to be able to customize this birthday message.

![patient chart](./images/provider/ptchart.png)

To add a new patient, click "Add a New Patient" to be directed to the correct page. Fill out the form to add a new patient chart..

![form to add new patient](./images/provider/add-pt.png)

The vaccination page contains animations that can be shown to the patient while they receive their vaccination. In the future, we would like to implement the ability for the user to be able to choose animations that they would like to include. After administering the vaccination, click the button on the bottom of the page to log the information.

![vaccinations page](./images/provider/vaccines.png)

The resources page contains information about common childhood illness, as well as some fun facts about the human body! Click on either of the buttons to generate a random informational card or fun fact.

![resources page](./images/provider/resources.png)

The user may view their account profile at any time by visiting the navigation bar.

The user may log out at any time by visiting the navigation bar.

### Patients

To access this application, visit the following URL: [http://my-kids-rx.herokuapp.com/](http://my-kids-rx.herokuapp.com/). Browse the homepage for business information, or select one of the options in the navigation bar at the top of the page.

Select "Patient Login" to login as a patient, or the user may create a new account.

![login page](./images/patient/login.png)

![create account page](./images/patient/create.png)

Once the user is logged in they may choose from the following options: view profile, view medical information, view appointments, view imaging results, view lab results, play games, view resources, and send/view messages.

The profile page will show account information and basic medical information, along with the options to change password and delete account. In order to carry out either of these options, the user must enter their current password correctly.

![profile page](./images/patient/profile.png)

The appointments page shows upcoming appointments as well as reports from previous appointments.

![appointments page](./images/patient/appt.png)

The imaging results page shows imaging results that are on file with their physician.

![imaging results page](./images/patient/imaging.png)

The lab results page shows lab results that are on file with their physician.

![lab results page](./images/patient/lab.png)

The games page has a few of options for the user to choose from: Matching, Tic-Tac-Toe, and Operation. Click on the corresponding button to be directed to a specific game.

![game options page](./images/patient/games.png)

![operation page](./images/patient/op.png)

![tic tac toe page](./images/patient/ttt.png)

![matching game page](./images/patient/match.png)

The resources page will show a randomly generated childhood illness from our database, as well as a randomly generated fun fact.

![resources page](./images/patient/resources.png)

The messages page will display messages that the user previously sent to their physician. They can also send out a new message by filling out the form.

![messaging page](./images/patient/message.png)

The user may log out at any time by visiting the navigation bar.

## Collaborators

- [Clarence Go](https://github.com/cmariego97)
- [Nick Stevens](https://github.com/stezzzy)
- [Kevin Crespo](https://github.com/kcrespo15)

## Credits

This provider login was built using the following Node.js packages: dotenv, express, express-session, connect-session-sequelize, generate-unique-id, mysql2, party-js, path, and sequelize. 

The patient login was built using the following Node.js packages: apollo-server-express, dotenv, express, graphql, jsonwebtoken, mongoose, apollo/client, emotion/react emotion/styled, fontsource/roboto, font awesome, material-ui, mui, jwt-decode, moment, react, react-dom react-external-link, react-scripts, and react-scroll.

The following third-party APIs were also utilized in creating the provider login: Tailwind CSS, Bootstrap, Google Fonts, Moment.js.

The [Mayo Clinic](https://www.mayoclinic.org/diseases-conditions) website was used to build our database of childhood illness information.

The [National Geographic Kids](https://www.natgeokids.com/uk/discover/science/general-science/15-facts-about-the-human-body/) website was used while building our database of human body fun facts.

  ## License

  This application is covered under the MIT License.
  To view a description of this license type, refer to the repo or click [here](https://opensource.org/licenses/MIT).

  ## Contributing

  Ways to contribute include suggesting bug fixes and ideas for new features.
  
  ## Tests

  N/A

  ## Questions

  For inquiries or to provide feedback, do not hesitate to contact any of the collaborators. 
  - Rita Pecuch: rpecuch@comcast.net
  - Clarence Go: cmarie.go97@gmail.com
  - Nick Stevens: nickyapril123@gmail.com
  - Kevin Crespo: KevinCrespo15@gmail.com
