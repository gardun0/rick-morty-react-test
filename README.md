# React Skills Test
----

This is only to prove your skills, try harder, be smarter and think _out-of-the-box_ 🤓, the test is intend to measure your skills so besides the code, you have to follow some standards described below.

> The reason why i'm writing this test in english is because you have to be familiar with it, the best documentation is written in English. (Also i'm doin' it to practice 🙄).

----

![](https://media.giphy.com/media/WVudyGEaizNeg/giphy.gif)

----

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
- **put some creativity from you...**


## Technology

To get all the information from Rick and Morty, we will use and HTTP API that already exists called [The Rick and Morty API](https://rickandmortyapi.com/), this is where you will be able to retrieve characters, locations, images, episodes, etc.

Like it's obvious we're using [React](https://reactjs.org/) as our main goal, i'm starting to give you the technology and standards that you MIGHT use:

> **Note:** Just the technology marked with * is a MUST, otherwise remember to think _out-of-the-box_.

----

#### Base
- [Standard](https://standardjs.com/)*: You have to install it and configure it in your editor/project. It's the standard we use for JavaScript code.
- [Create React App](https://facebook.github.io/create-react-app/)*: You might  initialize your app with this CLI app made by Facebook (React's creators). It'll make your life easier and it implements everything that you will need.
- [Redux](https://redux.js.org/)*: It's a framework which use [Flux](https://facebook.github.io/flux/) architecture made by Facebook open source. It let you store an state for your application and handle changes by actions that might change your state.
- [Duck pattern](https://github.com/erikras/ducks-modular-redux): It's a modular redux pattern, which will make your app scalable and easy to read while you can use redux as LEGO's pieces.
- [React Router](https://reacttraining.com/react-router/web/guides/quick-start)*: DOM Bindings to handle the routes of your application, this is useful when your application is not a [SPA](https://en.wikipedia.org/wiki/Single-page_application).

###### Nice additional stuff
- [Redux Devtools](https://github.com/zalmoxisus/redux-devtools-extension): As you have use Redux, it may be helpful to have a debugger and a state viewer for Redux.
- [Redux Sagas](https://github.com/redux-saga/redux-saga): Library extension for Redux which let you handle the side effects from your application with [generators](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Sentencias/function*), you can compose, combine and above with the helpers it contains. (It works with duck pattern to).
- [Redux Cycles](https://github.com/cyclejs-community/redux-cycles): Library extension for Redux which let you handle side effects in a pure functional way, minimizing errors and make your app even more composable. (It works with duck pattern to).
- [Connected React Router](https://github.com/supasate/connected-react-router): library which let you connect your router with redux, just think a little bit about it, sounds awesome!

> **Recommendation:** use on of the side effects redux handler from above.

----

#### UI/UX

- [Material UI](https://material-ui.com/):  React components that follows Material Design from Google, they're complete and ready to production. Support theming and [CSS in JS](https://cssinjs.org/?v=v10.0.0-alpha.12).
- [Styled Components](https://www.styled-components.com/): Library Helper for react which let you build modular and styled components, it's flexible and the API is simple.
- [Grommet](https://v2.grommet.io/): Another series of components for React which use their own design guidelines, it has a lot of useful and gorgeous components, it also supports theming.
- [Reflexbox](http://jxnblk.com/reflexbox/): Flexbox grid system to position and space components in React, it has a simple and clean API.

----

**Note: Like i said, you could use whatever you want, but remember to stick with the idea of the project.**


## Tips & Tricks

- React has a file standard according to the use of JSX, the files which contains JSX syntax MUST end with _.jsx_, otherwise with _.js_.
- I'm truly believer of [K.I.S.S](https://es.wikipedia.org/wiki/Principio_KISS) pattern, check it out!
- React is based on functional principles, the functional saying is about to split your code into small pieces of functions so later you can compose them. Do the same with React, create components as you wish, but don't forget to fit in the definition of reusability. [(Here is an article about it)](https://hackernoon.com/the-three-types-of-reusable-react-components-37a6bf7c2d69)
- Do as many files you want for your project, **try to split** into pieces and name them (files, variables) with a name for it's purpose.
- Name the things accordingly to their use, e.g. A component which centers a Box might be named as _CenteredBox_ **DO NOT** use names like ~~x, y, z~~.
- Do not forget to remember that your code might be used for others, so don't be selfish and write readable code 😐 (this tip is an extension from the previous tip).
- **Before** you start, i recommend you to check the documentation of the libraries/frameworks/technology you will use.

## Points to consider in this test

1. Document your code. Besides you will try to write readable code (i hope so 🙌🏻).
2. You MUST use an UI Library described in [Technology](#technology) section, but you still have to design your app structure, so be intelligent about it.
3. BE FUCKING CREATIVE IN EVERY POSSIBLE SITUATION.
4. Despite you have some limitations 🙃, you have the ability to refute the points in this test and prove yours (just don't forget what's about this application).
5. The time to develop this web application is maximum **2 weeks**. Less time is equal to better performance :)

[HERE YOU HAVE A GOOD REACT RESOURCE LIST](https://github.com/enaqx/awesome-react) 😇

# Good luck and have fun!

----

With ❤️ by Jorge Garduño.