# Road to Modern JavaScript and React

The purpose of this guide is to provide a list of several free ressources (articles :pencil:, books :book:, videos :clapper:) which will help you to learn modern JavaScript and the React library.  

:warning: This guide is not meant to list everything you must know about JavaScript or React. I've tried to list what could be useful if you were totally new to this world based on my experience and the people I've met. If your favorite thing isn't listed there, it doesn't mean I dislike it or disapprove it. For example [TypeScript](http://2ality.com/2018/04/type-notation-typescript.html) or [GraphQL](https://www.howtographql.com/) are great, but I don't think it is mandatory to learn that first **as a beginner**.

## 1) Modern JavaScript

### Tutorials that cover everything:
- [Eloquent JavaScript](http://eloquentjavascript.net/) :book: is perfect to learn JS and some general programming concepts.
- [The Modern JavaScript Tutorial](https://javascript.info/) :pencil: How it's done now. From the basics to advanced topics with simple, but detailed explanations.
- [Learn ES6 (ECMAScript 2015)](https://egghead.io/courses/learn-es6-ecmascript-2015) :clapper: if you used to write JavaScript a while ago and wanna catch up with modern syntaxes.
- [Learn Web Development](https://developer.mozilla.org/en-US/docs/Learn) :book: you will even learn HTML and CSS with that one. 

### Articles and videos I liked:
- [Modern JavaScript Explained For Dinosaurs](https://medium.com/the-node-js-collection/modern-javascript-explained-for-dinosaurs-f695e9747b70) :pencil: you will learn basics about npm, Babel, Webpack etc.. and the history behind it.
- [Understanding Hoisting in JavaScript](https://scotch.io/tutorials/understanding-hoisting-in-javascript) :pencil: if you come from another programming language, you might feel uncomfortable with how we can declare variables in JS. This article will help you to feel better!
- [Get Started with Debugging JavaScript in Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools/javascript/) :clapper: Firefox or Edge also have their own devtools, but I personally prefer using Chrome ones when coding.
- [Functional Programming in Javascript](https://www.youtube.com/playlist?list=PL0zVEGEvSaeEd9hlmCXrk5yUyqUag-n84) :clapper: those videos are made by a former Spotify JS developer. He will teach you essential concepts like Promises, Closures or Higher Order Functions. Those things are essentials in React.
- [Composition over Inheritance](https://www.youtube.com/watch?v=wfMtDGfHWpA) :clapper: At school I had to do a lot of Object Oriented Programming. This video helped me to understand why it's not always necessary. 

## 2) React :atom_symbol:

- [JavaScript to know for React](https://kentcdodds.com/blog/javascript-to-know-for-react) :pencil:
- The [official doc](https://reactjs.org/docs/getting-started.html) is awesome! They also have a list of [free courses](https://reactjs.org/community/courses.html) (and paid ones).
- [The Beginner's Guide to React](https://egghead.io/courses/the-beginner-s-guide-to-react) :clapper:
- [Progressive React](https://houssein.me/progressive-react) :pencil: tips to make your React site performant

##### Hooks :vs: Class Components
The hooks are very React specific, I suggest you to check [Why React Hooks?](https://ui.dev/why-react-hooks/) :pencil: :clapper: in order to learn more about React history and or why we now use hooks.
You might also want to learn about Class components and some patterns used to share logic between components (before hooks arrival) because there are still present in a lot of codebases:
- [React Lifecycle Methods Diagram](http://projects.wojtekmaj.pl/react-lifecycle-methods-diagram/) :pencil: this will help you to understand how a Class component lives and dies. 
- [Higher Order Components: A React Application Design Pattern](https://www.sitepoint.com/react-higher-order-components/) :pencil:
- [Render Props](https://reactjs.org/docs/render-props.html) :pencil:

##### State management
At some point you might think it would be nice to have access to some kind of global state in any React component in order to avoid passing down props again and again... People might tell you to use Redux or MobX or Apollo or XState or [insert popular libray name] to achieve that but it might be overkilled! I recommend reading the article [You might not need Redux](https://medium.com/@dan_abramov/you-might-not-need-redux-be46360cf367) :pencil: first. Plus React now has a stable [Context API](https://kentcdodds.com/blog/reacts-new-context-api) :pencil: that will help you to share data across components without a third party library.  

If you want to learn more about Redux then I would recommend its [official doc](https://redux.js.org/) :pencil: and those links:
- [React, Redux and JavaScript Architecture](https://jrsinclair.com/articles/2018/react-redux-javascript-architecture/) :pencil:
- [Understanding Redux: The World’s Easiest Guide to Beginning Redux](https://medium.freecodecamp.org/understanding-redux-the-worlds-easiest-guide-to-beginning-redux-c695f45546f6) :pencil:
- [Getting Started with Redux](https://egghead.io/courses/getting-started-with-redux) :clapper:
- [Building React Applications with Idiomatic Redux](https://egghead.io/courses/building-react-applications-with-idiomatic-redux) :clapper:
- [Presentational and Container Components](https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0) :pencil:
- [Redux Toolkit](https://redux-toolkit.js.org/introduction/quick-start) :pencil: The official, opinionated, batteries-included toolset for efficient Redux development;

## 3) What's next!?
- [10 Interview Questions Every JavaScript Developer Should Know](https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95) :pencil:
- Create your first React App via: [create-react-app](https://facebook.github.io/create-react-app/) :computer: or directly in your browser on [codesandbox](https://codesandbox.io/) :globe_with_meridians:
- Have a look to [Next.js](https://nextjs.org/), [Gatsby][https://www.gatsbyjs.com/] and React Native via [Expo](https://expo.io/);
- [More links](https://github.com/markerikson/react-redux-links) :pencil:

## What about styling?
##### Some basics
- [Modern CSS Explained For Dinosaurs](https://medium.com/actualize-network/modern-css-explained-for-dinosaurs-5226febe3525) :pencil:
- [CSS-in-JS or CSS-and-JS](https://johnpolacek.github.io/css-in-js-or-css-and-js/) :pencil:
- [Styling and CSS](https://reactjs.org/docs/faq-styling.html) Official React doc :pencil:
##### Libraries you can use to manage your style:
- [CSS Modules](https://github.com/css-modules/css-modules) :pencil:
- [JSS](http://cssinjs.org/) :pencil:
- [Emotion](https://emotion.sh/) :pencil:
- [Styled Components](https://www.styled-components.com/) :pencil: I think they are the best in between choice for those who are used to write "classic" CSS and want to take advantage from mixing it with JavaScript.

## What about testing?
- [But really, what is a JavaScript test?](https://www.javascriptjanuary.com/blog/but-really-what-is-a-javascript-test) :pencil: 
- [How to use React Testing Library Tutorial](https://www.robinwieruch.de/react-testing-library) :pencil: Understand Jest and learned how to write automated tests via React Testing Library (there are others testing libraries but RTL is a great one [recommended](https://reactjs.org/docs/testing.html#tools) by the official doc).
- [Understanding Jest Mocks](https://medium.com/@rickhanlonii/understanding-jest-mocks-f0046c68e53c) :pencil: Mocking is a technique to isolate test subjects by replacing dependencies with objects that you can control and inspect.
- [Why Cypress?](https://docs.cypress.io/guides/overview/why-cypress.html#In-a-nutshell) :clapper: a library to write end-to-end tests and more;

## Paid Courses
The ones I recommend after completing them:
- [Wes Bos courses](http://wesbos.com/courses/) :clapper: JavaScript, React, CSS and more; some are even **free**! 
- [Kent C. Dodds courses](https://kentcdodds.com/courses/) :clapper: React, Testing;
