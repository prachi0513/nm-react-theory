Q1. WHAT IS EMMET ?
ANS.Emmet is a toolkit for web developers that enables fast and efficient HTML and CSS coding through the use of abbreviations, which are expanded into full code snippets.

Q2.Difference between a Library and Framework?
ANS.Think of a library as a toolbox and a framework as a blueprint for building a house.

Library: A library provides a set of functions or components that you can use in your code to perform specific tasks. It's like borrowing tools from a toolbox when you need them. You have control over when and how to use these tools.

Framework: A framework, on the other hand, dictates the structure of your application and provides a set of rules or guidelines to follow. It's like following a blueprint when building a house. The framework provides pre-defined components and dictates how your code should be organized and interact with these components. You build your application within the framework's structure.
In summary, with a library, you call its functions or components when you need them, while with a framework, your code is built within its structure and follows its rules.

Q3.What is CDN? Why do we use it?
ANS:Imagine you want to share a cool video with your friends. Instead of sending it to each friend individually, you upload it to a central location where everyone can access it. A CDN works similarly for websites.

When you visit a website using a CDN, the content (like images, scripts, and videos) is stored on servers that are closer to you geographically. This means when you request a webpage, the content is delivered from a nearby server, which is faster than fetching it from a faraway server.

In simple terms, CDNs make websites faster and more reliable by storing and delivering content from servers closer to you.

Q4.Why is React known as React?
ANS.React got its name because of the way it works: it reacts to changes in data. When the data in a React application changes, React efficiently updates the user interface to reflect those changes without reloading the entire page. This reactive behavior is fundamental to how React operates, hence the name "React".

Q5. What is crossorigin in script tag?
ANS.The `crossorigin` attribute in a `<script>` tag is used to specify how the browser should handle requests made to load the script file from a different origin (i.e., a different domain, protocol, or port). It's commonly used when loading scripts from a different domain to control how the browser handles any potential CORS (Cross-Origin Resource Sharing) issues.

Q6.What is diference between React and ReactDOM.
ANS.In React, React and ReactDOM serve different purposes:

React: This is the core library for building user interfaces using components. It provides the logic and APIs for creating and managing components, handling state, and rendering UI elements.
ReactDOM: This library specifically deals with the interaction between React and the DOM (Document Object Model). It provides methods for rendering React components into the DOM, updating them when their data changes, and handling events.
In simple terms, React is the engine that powers the components and manages their behavior, while ReactDOM handles the rendering of those components into the browser's DOM.

Q7.What is difference between react.development.js and react.production.js files via CDN?
ANS.react.development.js: This file is larger and includes additional debugging tools and warnings to aid developers during development.

react.production.js: In contrast, this file is optimized for production use. It's smaller and removes debugging tools and warnings to improve performance and reduce file size.

In summary, react.development.js is for development with debugging features, while react.production.js is for production with optimized performance.

Q8.What is async and defer?
ANS.async and defer are attributes used in the <script> tag to control how scripts are loaded and executed in HTML documents.

async: When you include the async attribute in a <script> tag, it tells the browser to load the script asynchronously while continuing to parse the HTML document. This means that the script can be downloaded in the background, and the HTML parsing and rendering won't be blocked by the script's download or execution. However, the order of execution of asynchronous scripts is not guaranteed, so scripts may execute out of order.

defer: The defer attribute, on the other hand, also tells the browser to download the script asynchronously, but it defers the execution of the script until after the HTML document has been fully parsed and loaded. Scripts with the defer attribute will be executed in the order they appear in the document. This can be useful when you want to ensure that scripts are executed in the correct order, especially when they depend on elements in the HTML document.

In summary, async loads and executes scripts asynchronously, potentially out of order, while defer loads scripts asynchronously but ensures they are executed in order after the HTML document has been parsed.
