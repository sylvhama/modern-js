# Road to Modern JavaScript and React

*"ES6 is JavaScript"* (from [How to learn ES6](https://medium.com/javascript-scene/how-to-learn-es6-47d9a1ac2620))

The purpose of this guide is to provide a list of several free ressources (articles :pencil:, books :book:, videos :clapper:) which will help you to learn ECMAScript 6 (also known as ES6 or ES2015) and the framework React.  

:warning: This guide is not meant to list everything you must know about JavaScript or React. I've tried to list what could be useful if you were totally new to this world based on my experience and the people I've met. If your favorite thing isn't listed there, it doesn't mean I dislike it or disapprove it. For example [TypeScript](http://2ality.com/2018/04/type-notation-typescript.html) or [GraphQL](https://www.howtographql.com/) are great, but I don't think it is mandatory to learn that first **as a beginner**.

## 0) ES5 foundations and others basics
Before digging into ES6, let's make sure that we understand some ES5 common concepts:
- [Eloquent JavaScript](http://eloquentjavascript.net/) :book: is the perfect reminder to learn JS and review some general programming concepts.
- [Understanding Hoisting in JavaScript](https://scotch.io/tutorials/understanding-hoisting-in-javascript) :pencil:, if you come from another programming language, you might feel unconfortable with how we can declare variables in JS. This article will help you to feel better!
- [Prototypes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Inheritance_and_the_prototype_chain) :pencil:, it's nice to understand prototypes in JavaScript since ES6 class is only syntactical sugar, JavaScript remains prototype-based. However I would only learn this for your general culture, it's not something you might use on a daily base.
- [But really, what is a JavaScript test?](https://www.javascriptjanuary.com/blog/but-really-what-is-a-javascript-test) :pencil:, what ever the language you use, it's always important to write automatic tests!
- [Get Started with Debugging JavaScript in Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools/javascript/) :clapper: Firefox or Edge also have their own devtools, but I personnaly prefer using Chrome ones when coding.
- [Functional Programming in Javascript](https://www.youtube.com/playlist?list=PL0zVEGEvSaeEd9hlmCXrk5yUyqUag-n84) :clapper:, those videos are made by a former Spotify JS developer. He will teach you essential concepts like Promises, Closures or Higher Order Functions. Those things are essentials in React.

## 1) ES6 / ES2015
- [Modern JavaScript Explained For Dinosaurs](https://medium.com/the-node-js-collection/modern-javascript-explained-for-dinosaurs-f695e9747b70) :pencil:, you will learn basics about npm, Babel, Webpack etc.. and the history behind it.
- [The Modern JavaScript Tutorial](https://javascript.info/) :pencil: How it's done now. From the basics to advanced topics with simple, but detailed explanations.
- [Understanding ECMAScript 6](https://leanpub.com/understandinges6/read) :book:
- [Learn ES6 (ECMAScript 2015)](https://egghead.io/courses/learn-es6-ecmascript-2015) :clapper:
- [Composition over Inheritance](https://www.youtube.com/watch?v=wfMtDGfHWpA) :clapper: this is not directly realted to ES6 but he uses ES6 syntax.

## 2) React :atom_symbol:

The [official doc](https://reactjs.org/docs/getting-started.html) is awesome! However if you need different point of views / styles then you can look at the following links:

##### To start
- [Road to React](https://leanpub.com/the-road-to-learn-react/) :book: it also covers some ES6 features, you can "buy" it for free.
- [Start Learning React](https://egghead.io/courses/start-learning-react) :clapper:
- [Jest Getting Started](https://facebook.github.io/jest/docs/en/getting-started.html) :pencil: automated tests in React
- [Progressive React](https://houssein.me/progressive-react) :pencil: tips to make your React site performant

##### Hooks :vs: Class Components
The [Hooks](https://reactjs.org/docs/hooks-intro.html) :pencil: offer a different approach to use state and others React features outside of classes. I believe you should still learn about Class components and some patterns used to share logic between components because you might still encounter them:
- [React Lifecycle Methods Diagram](http://projects.wojtekmaj.pl/react-lifecycle-methods-diagram/) :pencil:, this will help you to understand how a Class component lives and dies. 
- [Higher Order Components: A React Application Design Pattern](https://www.sitepoint.com/react-higher-order-components/) :pencil:
- [Render Props](https://reactjs.org/docs/render-props.html) :pencil:

##### State management
At some point you might think it would be nice to have access to some kind of global variable in any React component in order to avoid passing down props again and again... People might tell you to use [Redux](https://redux.js.org/) :pencil: or [MobX](https://mobx.js.org/) :pencil: to achieve that but it might be overkilled! I recommend reading the article [You might not need Redux](https://medium.com/@dan_abramov/you-might-not-need-redux-be46360cf367) :pencil: first. Plus React now has a stable [Context API](https://medium.com/dailyjs/reacts-%EF%B8%8F-new-context-api-70c9fe01596b) :pencil: that will help you to share data across components without a third party.  

So you've learned about pros and cons about MobX or Redux but you're not sure which one is better? As always it will depend of your taste, your personality, your experience, your team, the project you are working on etc... There isn't a bad choice.

If you want to learn more about Mobx or Redux then I would recommend their official docs and those links (you will notice that there are much more Redux links because I kinda prefer it :see_no_evil:):
- [Manage Complex State in React Apps with MobX](https://egghead.io/courses/manage-complex-state-in-react-apps-with-mobx) :clapper:
- [React, Redux and JavaScript Architecture](https://jrsinclair.com/articles/2018/react-redux-javascript-architecture/) :pencil:
- [Understanding Redux: The World’s Easiest Guide to Beginning Redux](https://medium.freecodecamp.org/understanding-redux-the-worlds-easiest-guide-to-beginning-redux-c695f45546f6) :pencil:
- [Getting Started with Redux](https://egghead.io/courses/getting-started-with-redux) :clapper:
- [Building React Applications with Idiomatic Redux](https://egghead.io/courses/building-react-applications-with-idiomatic-redux) :clapper:
- [Presentational and Container Components](https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0) :pencil:

## 3) Are you ready!?
- [10 Interview Questions Every JavaScript Developer Should Know](https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95) :pencil:
- Create your first React App: on [your machine](https://facebook.github.io/create-react-app/) :computer: or within [your browser](https://codesandbox.io/) :globe_with_meridians:
- [More links](https://github.com/markerikson/react-redux-links) :pencil:

##### Special Mention
You really should have a look to [Wes Bos courses](http://wesbos.com/courses/) :clapper:, they aren't all free but they worth the investment! 

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
