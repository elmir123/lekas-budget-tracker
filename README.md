# Lekas Budget Tracker

![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)
![GitHub top language](https://img.shields.io/github/languages/elmir123/lekas-budget-tracker?color=yellow&logo=JavaScript&logoColor=green)
![GitHub language count](https://img.shields.io/github/languages/count/elmir123/lekas-budget-tracker)

## Usage
- npm install
- npm start

## Deployed
Click here to open site:
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://lekas-budget-tracker.herokuapp.com/)


## Description
The app will let you record your charges and expenses
It has a helpfull graph to display your budget

The important feature of this app is that it will keep record of your records even if you are offline.
Records added offline will be collected, the app will wait for the time that your device goes online. At that time it will automaticly sync itself with the server database and permenetly store your records. 

## Dependencies
```js
  "dependencies": {
    "compression": "^1.7.4",
    "express": "^4.17.1",
    "lite-server": "^2.5.3",
    "mongoose": "^5.5.15",
    "morgan": "^1.9.1"
  }
```

## Demo

The following image demonstrates the web application's appearance:

![Password Generater Step Form.](./public/images/budget-tracker.png)

To view the working app use the link below:

https://lekas-budget-tracker.herokuapp.com/
