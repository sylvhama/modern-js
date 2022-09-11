# Road to Modern JavaScript and React

The purpose of this guide is to provide a list of several free ressources (articles :pencil:, books :book:, videos :clapper:) which will help you to learn modern JavaScript and the React library. 

:warning: This guide is not meant to list everything you must know about JavaScript or React. I've tried to list what could be useful if you were totally new to this world based on my experience and the people I've met. If your favorite thing isn't listed there, it doesn't mean I dislike it or disapprove it. For example [TypeScript](http://2ality.com/2018/04/type-notation-typescript.html) or [GraphQL](https://www.howtographql.com/) are great, but I don't think it is mandatory to learn that first **as a beginner**.

## 1) Modern JavaScript 💃

### Tutorials that cover everything:
- [Learn Web Development](https://developer.mozilla.org/en-US/docs/Learn) :book: will also teach you HTML and CSS. 
- [Eloquent JavaScript](http://eloquentjavascript.net/) :book: is perfect to learn JS and general programming concepts.
- [The Modern JavaScript Tutorial](https://javascript.info/) :book: How it's done now. From the basics to advanced topics with simple, but detailed explanations.
- [Learn ES6 (ECMAScript 2015)](https://egghead.io/courses/learn-es6-ecmascript-2015) :clapper: if you used to write JavaScript a while ago and wanna catch up with modern syntaxes.

### Articles and videos I liked:
- [Modern JavaScript Explained For Dinosaurs](https://medium.com/the-node-js-collection/modern-javascript-explained-for-dinosaurs-f695e9747b70) :pencil: you will learn basics about npm, Babel, Webpack etc.. and the history behind it.
- [Understanding Hoisting in JavaScript](https://scotch.io/tutorials/understanding-hoisting-in-javascript) :pencil: if you come from another programming language, you might feel uncomfortable with how we can declare variables in JS. This article will help you to feel better!
- [Get Started with Debugging JavaScript in Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools/javascript/) :clapper: Firefox or Edge also have their own devtools, but I personally prefer using Chrome ones when coding.
- [Functional Programming in Javascript](https://www.youtube.com/playlist?list=PL0zVEGEvSaeEd9hlmCXrk5yUyqUag-n84) :clapper: those videos are made by a former Spotify JS developer. He will teach you essential concepts like Promises, Closures or Higher Order Functions. Those things are essentials in React.
- [Composition over Inheritance](https://www.youtube.com/watch?v=wfMtDGfHWpA) :clapper: At school I had to do a lot of Object Oriented Programming. This video helped me to understand why it's not always necessary. 

### Documentation
Sometimes you will need to search for documentation, for example if you don't know a specific keyword in a codebase or you would like to learn how to use a native function. Of course you can use any search engine or Stackoverflow but I would recommend using the [MDN Web Docs](https://developer.mozilla.org/). 

## 2) React :atom_symbol:

- [What is React: A Visual Introduction For Beginners](https://learnreact.design/posts/what-is-react) :pencil:
- [JavaScript to know for React](https://kentcdodds.com/blog/javascript-to-know-for-react) :pencil:
- The [official doc](https://reactjs.org/docs/getting-started.html) is awesome! They also have a list of [free courses](https://reactjs.org/community/courses.html) (and paid ones).
- [The Beginner's Guide to React](https://egghead.io/courses/the-beginner-s-guide-to-react) :clapper:
- [Progressive React](https://houssein.me/progressive-react) :pencil: tips to make your React site performant. [web.dev](https://web.dev/) also has a lot of articles like that.

### Hooks :vs: Class Components
The hooks are very React specific, I suggest you check [Why React Hooks?](https://ui.dev/why-react-hooks/) :pencil: :clapper: in order to learn more about React history and or why we now use hooks.
You might also want to learn about Class components and some patterns used to share logic between components (before hooks arrival) because there are still present in a lot of codebases:
- Compare the [Hook Flow Fiagram](https://github.com/donavon/hook-flow#flow-diagram) :pencil: with the [Class Component Lifecycle Methods Diagram](http://projects.wojtekmaj.pl/react-lifecycle-methods-diagram/) :pencil:
- [Higher Order Components: A React Application Design Pattern](https://www.sitepoint.com/react-higher-order-components/) :pencil:
- [Render Props](https://reactjs.org/docs/render-props.html) :pencil:

### State management
At some point you might think it would be nice to have access to some kind of global state in any React component in order to avoid passing down props again and again... People might tell you to use Redux or MobX or Apollo or XState or [insert popular library name] to achieve that but it might be overkilled! I would recommend reading the article [React State Management Libraries and How to Choose](https://daveceddia.com/react-state-management) :pencil: to get a nice overview.

## 3) What's next!? 🎓
- Practice React with [create-react-app](https://facebook.github.io/create-react-app/) :computer: or directly in your browser on [codesandbox](https://codesandbox.io/) :globe_with_meridians:
- Subscribe to [React Newsletter](https://ui.dev/newsletters/react/);
- To start a new project: [Vite](https://vitejs.dev/), [Next.js](https://nextjs.org/), [Gatsby](https://www.gatsbyjs.com/), React Native via [Expo](https://expo.io/);
- [10 Interview Questions Every JavaScript Developer Should Know](https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95) :pencil:

## What about styling? 💅
### Some basics
- [Learn CSS](https://web.dev/learn/css/) An evergreen CSS course and reference to level up your web styling expertise. 📝
- [Modern CSS Explained For Dinosaurs](https://medium.com/actualize-network/modern-css-explained-for-dinosaurs-5226febe3525) :pencil:
- [CSS-in-JS or CSS-and-JS](https://johnpolacek.github.io/css-in-js-or-css-and-js/) :pencil:
- [Styling and CSS](https://reactjs.org/docs/faq-styling.html) Official React doc :pencil:
### Libraries you can use to manage your style:
- [CSS Modules](https://github.com/css-modules/css-modules) :pencil:
- [JSS](http://cssinjs.org/) :pencil:
- [Emotion](https://emotion.sh/) :pencil:
- [Styled Components](https://www.styled-components.com/) :pencil: I think they are the best in between choice for those who are used to write "classic" CSS and want to take advantage from mixing it with JavaScript.
### Design systems
Maybe you just want to build an app and avoid spending a lot of time writing CSS and HTML. I suggest you use libraries such as [Material-UI](https://material-ui.com/), [Ant Design](https://ant.design/) or [Polaris](https://polaris.shopify.com/). If you want to build your own design system I would suggest you to read [Atomic Design](https://atomicdesign.bradfrost.com/). 

## What about testing? 🤖
- [But really, what is a JavaScript test?](https://kentcdodds.com/blog/but-really-what-is-a-javascript-test) :pencil: 
- [How to use React Testing Library Tutorial](https://www.robinwieruch.de/react-testing-library) :pencil: Understand Jest and learned how to write automated tests via React Testing Library (there are others testing libraries but RTL is a great one [recommended](https://reactjs.org/docs/testing.html#tools) by the official doc).
- [Understanding Jest Mocks](https://medium.com/@rickhanlonii/understanding-jest-mocks-f0046c68e53c) :pencil: Mocking is a technique to isolate test subjects by replacing dependencies with objects that you can control and inspect.
- [Why Cypress?](https://docs.cypress.io/guides/overview/why-cypress.html#In-a-nutshell) :clapper: a library to write end-to-end tests and more;

## Others tools I default to
- Code editor: [VS Code](https://code.visualstudio.com/);
- Auto code formatter: [Prettier](https://prettier.io/);
- Linter: [ESLint](https://eslint.org/);
- Manage Git via an UI instead of commands: [Sourcetree](https://www.sourcetreeapp.com/) or [VS Code](https://code.visualstudio.com/docs/editor/versioncontrol);
- Build and deploy you app: [Netlify](https://www.netlify.com/);
- Continuous Integration: [Travis CI](https://travis-ci.com/);
- Buy domain name: [Google Domains](https://domains.google/);

## Others libraries I default to
- Routing: [react-router](https://reactrouter.com/);
- Internationalization: [LinguiJS](https://lingui.js.org/);
- Develop your components in isolation and share them to your team via [Storybook](https://storybook.js.org/). Deploy your Storybook and run screenshot tests on each story via [Chromatic](https://www.chromatic.com/);
- API Mocking when testing: [Mock Service Worker](https://mswjs.io/);

## Paid Courses 💸
The ones I recommend after completing them:
- [Wes Bos courses](http://wesbos.com/courses/) :clapper: JavaScript, React, CSS and more; some are even **free**! 
- [Kent C. Dodds courses](https://kentcdodds.com/courses/) :clapper: React, Testing;
