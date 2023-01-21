
<!-- omit in toc -->
# Redux-Store

<!-- omit in toc -->
## Table of Contents
- [Overview](#overview)
- [What's so great about Redux?](#whats-so-great-about-redux)
- [Technologies Used](#technologies-used)
- [Screen Capture](#screen-capture)
- [Live Application](#live-application)
- [Installation](#installation)
- [Usage](#usage)

## Overview
An e-commerce platform that allows users to create an account, view items available for sale, add the items to their shopping cart, and purchase items using Stripe.  

## What's so great about Redux?
Redux elegantly handles complex state interactions that are hard to express with React’s component state. It is essentially a message-passing system, like the kind seen in Object-Oriented programming, but implemented as a library instead of in the language itself. As in OOP, Redux inverts the responsibility of control from caller to receiver — the UI doesn’t directly manipulate the state but rather sends it a message for the state to interpret.

The inversion of control described above ensures that the UI doesn’t need to be updated if the implementation of state transitions changes. Adding complex features like logging, undo or even time travel debugging are almost trivial. Integration tests are just a matter of testing that the right action is dispatched; the rest can be unit-tested.

## Technologies Used
<div style="display: inline_block"><br>
  <img height="40" align="center" alt="Chris-Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img height="40" align="center" alt="Chris-React" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg">
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img height="40" align="center" alt="Chris-Redux" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redux/redux-original.svg">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 <img height="40" align="center" alt="Chris-Node" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg">
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 <img height="40" align="center" alt="Chris-Express" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original.svg">
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 <img height="40" align="center" alt="Chris-MongoDB" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg">
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 <img height="40" align="center" alt="Chris-GraphQL" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/graphql/graphql-plain.svg">
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img height="40" align="center" alt="Chris-HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img height="40" align="center" alt="Chris-CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</div>
  
</br>

## Screen Capture
![](https://github.com/c1flores/Redux-Store/blob/main/client/public/assets/Walkthrough.gif)

## Live Application
* [Link](https://reduxx-storee.herokuapp.com/)

## Installation
  1. Fork and clone repository to local machine. 
  2. Open integrated terminal in personal IDE.
  3. Run ```npm install``` in the highest level of the root directory to install all the necessary dependencies. 
   
## Usage  
  1. Open integrated terminal in personal IDE.
  2. Run ```npm run develop``` to start a local development server and to compile required static assets. 
