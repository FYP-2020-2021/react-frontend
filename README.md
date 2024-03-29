# Dokumental
<p align="center">
  <img src="src/res/images/Dokumental_Logo.png" alt="Logo" width="100" height="100">
</p>

<h4 align="center">A responsive web app made using <a href="https://reactjs.org/" target="_blank">React.js</a>.</h4>

## How to run 
Type `yarn` to install and update project
Type `yarn start` to start the react project 

## About The Project
Dokumental is the front-end component of the document classification project for Monash's Final Year Project. 
It serves as the landing page for users to submit .txt, .pdf or .docx files to the server which hosts a neural network classifier.
Once the readability for the documents have been ascertained, the server sends back the results to the web app which shows them to the users.

Currently it has the following screens:

- Home/Upload Page
- How It Works Page
- Results Page
- About Page

Almost all of the UI components are made from scratch without external CSS libraries.
Animations are powered by React Spring.

## Screenshots
### Home Page
<img src="src/res/images/home_page.png" alt="Home Page" height="500">

### Document Dropzone
<img src="src/res/images/drop_zone.png" alt="Document Dropzone">

### Results Page
<img src="src/res/images/results.png" alt="Results Page" height="500">

## Core Libraries

- [React.js](https://reactjs.org/)
- [React Redux](https://react-redux.js.org/)
- [Redux Saga](https://redux-saga.js.org/)
- [React Spring](https://www.react-spring.io/)
- [React Dropzone](https://react-dropzone.js.org/)


### Updates
1. Website accept: pdf, docx, txt
