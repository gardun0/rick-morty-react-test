# React Skills Test 
------

This is only to prove your skills, try harder, be smarter and think _out-of-the-box_ 🤓, the test is intend to measure your skills so besides the code, you have to follow some standards described below.

::The reason why i'm writing this test in english is because you have to be familiar with it, the best documentation is written in English. (Also to practice 🙄).::

------

## Introduction

In this test, we're going to build a [PWA](https://developers.google.com/web/progressive-web-apps/) with React, for funny and entertainment situation we're building a Rick and Morty's fan site.

This application must accomplish some features:

- Search bar (it might search for episodes and characters).
  - It might have search filers like described in [RMAPI](https://rickandmortyapi.com/documentation/#filter-characters)
- Recent characters and episodes (main page).
- Character profile.
- Episode information.
- Search results must have pagination.
- The application must be mobile-friendly.


## Technology

Like it's obvious we're using [React](https://reactjs.org/) as our main goal, i'm starting to give you the technology and standards that you MIGHT use:

::**Note:** Just the technology marked with * is a MUST, otherwise remember to think _out-of-the-box_.::

----

#### Base
- [Standard](https://standardjs.com/)*: You have to install it and configure it in your editor/project. It's the standard we use for JavaScript code.
- [Create React App](https://facebook.github.io/create-react-app/)*: You might  initialize your app with this CLI app made by Facebook (React's creators). It'll make your life easier and it implements everything that you will need.
- [Redux](https://redux.js.org/)*: It's a framework which use [Flux](https://facebook.github.io/flux/) architecture made by Facebook open source. It let you store an state for your application and handle changes by actions that might change your state.
- [Duck pattern](https://github.com/erikras/ducks-modular-redux): It's a modular redux pattern, which will make your app scalable and easy to read while you can use redux as LEGO's pieces.

###### Nice additional stuff
- [Redux Devtools](https://github.com/zalmoxisus/redux-devtools-extension): As you have use Redux, it may be helpful to have a debugger and a state viewer for Redux.
- [Redux Sagas](https://github.com/redux-saga/redux-saga): Library extension for Redux which let you handle the side effects from your application with [generators](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Sentencias/function*), you can compose, combine and above with the helpers it contains. (It works with duck pattern to).
- [Redux Cycles](https://github.com/cyclejs-community/redux-cycles): Library extension for Redux which let you handle side effects in a pure functional way, minimizing errors and make your app even more composable. (It works with duck pattern to).

::**Recommendation:** use on of the side effects redux handler from above.::

----

#### UI/UX

- [Material UI](https://material-ui.com/):  React components that follows Material Design from Google, they're complete and ready to production.
- [Styled Components](https://www.styled-components.com/): Library Helper for react which let you build modular and styled components, it's flexible and the API is simple.