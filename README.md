# budget-tracker app

PWA (Progressive web apps): Online/Offline Budget Trackers

![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)
![npm](https://img.shields.io/npm/v/npm?color=orange&logo=npm)
![GitHub top language](https://img.shields.io/github/languages/top/TatyanaYarush/budget-tracker?color=yellow&logo=JS&logoColor=yellow)
![GitHub language count](https://img.shields.io/github/languages/count/TatyanaYarush/budget-tracker)
![GitHub last commit](https://img.shields.io/github/last-commit/TatyanaYarush/budget-tracker?color=orange)


Click here to open site:

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://salty-lowlands-18483.herokuapp.com/)

 ## Table of Contents
- [Introduction](#introduction)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Installation](#installation)
- [Screenshots](#screenshots)
- [Dependencies & Technologies](#Dependencies-&-technologies)
- [Resource](#information_source-resource)
- [Author](#raising_hand-author)
- [Questions](#questions)

## Introduction
The budget tracker app allows the user to add expenses and deposits to their budget with or without an internet connection. When entering transactions offline, they should populate the total when brought back online. This application uses IndexDB, Service workers, and Web Manifest for offline functionality and is deployed on Heroku.

## User Story

```md
AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling
```
## Acceptance Criteria

```md
GIVEN a user is on Budget App without an internet connection
WHEN the user inputs a withdrawal or deposit
THEN that will be shown on the page, and added to their transaction history when their connection is back online.
```
## Installation
Install the packages/dependencies by hitting following command on your terminal console:

```
npm i
npm init
npm i express
npm i morgan
npm i mongoose
npm install --save
npm i compression

```

## Screenshots
Budget Tracker App:
![Budget Tracker App](https://user-images.githubusercontent.com/70031550/125373312-e4c6f680-e352-11eb-9740-03c2e0d24b62.JPG)

Manifest
![screenshot_ManifestIcons](https://user-images.githubusercontent.com/70031550/125373329-ef818b80-e352-11eb-86e6-e1a2d0203cc4.JPG)

 - YouTube Video: [DemoVideo](https://www.youtube.com/watch?v=lpOAFKDPH8U)

## Dependencies & Technologies

<p>
<img alt="GitHub" src="https://img.shields.io/badge/github-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white"/>
<img alt="JavaScript" src="https://img.shields.io/badge/javascript-%23323330.svg?&style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/>
<img alt="Markdown" src="https://img.shields.io/badge/markdown-%23000000.svg?&style=for-the-badge&logo=markdown&logoColor=white"/>
<img alt="Express.js" src="https://img.shields.io/badge/express.js-%23404d59.svg?&style=for-the-badge"/>
<img alt="Heroku" src="https://img.shields.io/badge/heroku-%23430098.svg?&style=for-the-badge&logo=heroku&logoColor=white"/>
<img alt="Visual Studio Code" src="https://img.shields.io/badge/VisualStudioCode-0078d7.svg?&style=for-the-badge&logo=visual-studio-code&logoColor=white"/>
</p>

```md
 "dependencies": {
    "compression": "^1.7.4",
    "express": "^4.17.1",
    "mongoose": "^5.13.2",
    "morgan": "^1.10.0",
    "nodemon": "^2.0.9"
  },
  "devDependencies": {
    "webpack": "^5.42.1",
    "webpack-cli": "^4.7.2"
  }
}
```

### :information_source: Resource 
- [PWAs](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps)
- [Measure performance with the RAIL model](https://web.dev/rail/)
- [IndexedDB](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API)
- [Webmanifest](https://developer.mozilla.org/en-US/docs/Web/Manifest)
- [Google Offline Cookbook](https://web.dev/offline-cookbook/)
- [Google Lighthouse](https://developers.google.com/web/tools/lighthouse/)
- [Audit the Performance of Your Web Application](https://developers.google.com/web/fundamentals/performance/audit/)
- [Set Up MongoDB Atlas](https://carleton.bootcampcontent.com/carleton-university/carl-ott-fsf-pt-02-2021-u-c/blob/master/18-NoSQL/04-Important/MongoAtlas-Setup.md)
- [Deploy with Heroku and MongoDB Atlas](https://carleton.bootcampcontent.com/carleton-university/carl-ott-fsf-pt-02-2021-u-c/blob/master/18-NoSQL/04-Important/MongoAtlas-Deploy.md)

## :raising_hand: Author 
Written by Tatyana Yarushin student in full stack web development in the Coding Bootcamp course at Carleton University

**I hope you found something interesting!** :scroll:

## Questions
:question: For any additional information or questions find me at:

 - Email: [tatyana.yarushin@gmail.com](mailto:tatyana.yarushin@gmail.com)
 
 - Github: [TatyanaYarush](https://github.com/TatyanaYarush)
