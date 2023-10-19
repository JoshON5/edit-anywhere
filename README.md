# Edit Anywhere

[![License Badge](https://img.shields.io/badge/License-Apache-purple)](https://www.apache.org/licenses/LICENSE-2.0)

## Table of Contents

- [Visuals](#visuals)
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [Contact](#contact)

  ## Visuals
    - <a href="https://shrouded-peak-56169-cbb834107b17.herokuapp.com/">Edit Anywhere deployment site</a>

    <img src='./assets/2023-10-18 23.13.25.gif'>

  ## Description

  This application is PWA (Progressive Web Application) for a text editor that you can install on your local hardware to work offline with it, utilizing service workers and cachable assets.

  ## Installation

  This application needs `concurrently` to run client and servers scripts simutaneously and `express` for the routes in the server folder installed using `npm i` to have it work and also nodemon is added into the `package.JSON` to help with having the server run with hot changes and you can use it by running `npm run start:dev`. Also `babel` is utilized here because of ES6 syntax is used with our async/await functions to run in browsers that are still running ES5.

  ## Usage

  To use the application you will need to first run a `npm run start:dev` and go to `localhost:3000` or to the deployed website as well. Once it's launched you can open up Chrome dev tools and click the `Application` tab to see what is in the `indexedDb` and also the `manifest.json`. Also in the dev tools you can go to cache stroage to see what is being pre-cached. You can then choose to install the application so you can run it on your local device and have it sync once online back to the same database. 
    
  ## Credits

  Joshua Nichols

  UTSA Bootcamp Module 19

  ## License

  For more info about this License go to https://www.apache.org/licenses/LICENSE-2.0

  ## Contact

  You can contact me through:

  Email: [n/a](mailto:n/a)

  GitHub: [PROFILE](https://github.com/JoshON5)
