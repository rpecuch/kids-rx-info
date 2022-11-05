# Kids-RX: Pediatric Electronic Health Records

  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

  ![HTML](https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![MUI](https://img.shields.io/badge/MUI-%230081CB.svg?style=for-the-badge&logo=mui&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)

![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Apollo-GraphQL](https://img.shields.io/badge/-ApolloGraphQL-311C87?style=for-the-badge&logo=apollo-graphql)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)

## Description

The purpose of this application is to provide an electronic system to keep track of patient records in a healthcare environment.

### Providers

Like other electronic health record (EHR) systems, features include appointment scheduling, creating patient charts, writing medical record notes, logging vital signs, and logging vaccination records. What makes Kids-RX different is that it is specifically designed for use in pediatrics and includes features that were implemented with children in mind. Additional functionalities that we would like to add in the near future include increasing the number of different calendar views, implementing electronic prescriptions, and adding more editing abilities. We also plan on making the patient charts much more detailed.

### Patients

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

![homepage of application](./public/img/readme/homepage.png)

 Select "Staff Login" to login as a provider, or the user may create a new account.

 ![create account page](./public/img/readme/createacc.png)

 ![login page](./public/img/readme/login.png)

 Once the user is logged in, they will be taken to the dashboard. They may choose to view the schedule, view current patients, view the vaccination page, or view resources.

![staff dashboard page](./public/img/readme/dash.png)

The schedule page displays a list of appointments for the current day. The status may be changed when the patient arrives. To add a new appointment to the schedule, fill out the form at the top of the page.

![schedule page](./public/img/readme/schedule.png)

The patients page displays a list of the first 25 patients in the system alphabetically. To view a specific patient, use the search bar at the top of the page. 

![list of patients](./public/img/readme/pt-list.png)

The following information is contained in each patient chart: basic information (name, date of birth, etc), allergies, medical history, medications, vaccinations, guardian information, recent vital signs, upcoming appointments, and medical reports. The user may add a new medication, vaccination, appointment, medical report, or set of vital signs using the corresponding button. On the patient's birthday, click the corresponding button for a special surprise! In the future, we would like to implement the ability for the user to be able to customize this birthday message.

![patient chart](./public/img/readme/ptchart.png)

To add a new patient, click "Add a New Patient" to be directed to the correct page. Fill out the form to add a new patient chart..

![form to add new patient](./public/img/readme/add-pt.png)

The vaccination page contains animations that can be shown to the patient while they receive their vaccination. In the future, we would like to implement the ability for the user to be able to choose animations that they would like to include. After administering the vaccination, click the button on the bottom of the page to log the information.

![vaccinations page](./public/img/readme/vaccines.png)

The resources page contains information about common childhood illness, as well as some fun facts about the human body! Click on either of the buttons to generate a random informational card or fun fact.

![resources page](./public/img/readme/resources.png)

The user may view their account profile at any time by visiting the navigation bar.

The user may log out at any time by visiting the navigation bar.

### Patients

## Collaborators

- [Rita Pecuch](https://github.com/rpecuch)
- [Nick Stevens](https://github.com/stezzzy)
- [Kevin Crespo](https://github.com/kcrespo15)

## Credits

This project was built using the following Node.js packages: dotenv, express, express-session, connect-session-sequelize, generate-unique-id, mysql2, party-js, path, and sequelize. 

The following third-party APIs were also utilized: Tailwind CSS, Bootstrap, Google Fonts, Moment.js.

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

  If you have any questions or would like to provide feedback, do not hesitate to contact any of the collaborators. 
  - Clarence Go: cmarie.go97@gmail.com
  - Rita Pecuch: rpecuch@comcast.net
  - Nick Stevens: nickyapril123@gmail.com
  - Kevin Crespo: KevinCrespo15@gmail.com
