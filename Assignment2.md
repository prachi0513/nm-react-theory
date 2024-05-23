Q1.- What is `NPM`?
Ans: It manages packages , it is used to install packages written for our use and we install them by configuring npm in our project and we can us ethem accordingly.
NPM automatically handles the dependencies of the packages you install, making sure all required packages are also installed.
Managing packages for Node.js.

Q2.What is `Parcel/Webpack`? Why do we need it?
And: Parcel is a bundler we need for development and production too , it has so many dependencies that we neeed for our project it minifies the code , chunking , optimize the code make it production and many more.It host our locally for smooth develpoment experience giving out the functionality of Hot module reload.
In summary, Parcel and Webpack are essential tools for modern web development, helping streamline the development workflow, optimize performance, and manage dependencies effectively.

Q3. What is `.parcel-cache`
Ans. Parcel has watching algorithm which is written in c++ it keeps watching our file and if there is any chnage in any fike it keeps track of the changes and changes it using HMR and that using the parcel-cache. This directory helps Parcel optimize subsequent builds by storing compiled assets, dependency information, and other temporary data.It speeds up the build process by avoiding unnecessary recompilation of unchanged files.

Q4.● - What is `npx` ?
Ans. This is used to execute the packges like - (npx parcel index.html\_).
npx is a command-line tool that comes with Node.js, allowing users to execute Node.js packages directly, without installing them globally or locally. It's particularly useful for running packages that are not installed or used frequently.'

Q5.What is difference between `dependencies` vs `devDependencies`
Ans.In Node.js projects, dependencies are packages required for the application to run, while devDependencies are packages only needed for development and testing purposes. Dependencies are typically essential for the application's functionality, while devDependencies include tools like testing frameworks, build tools, and code linters. They're not required for the application to function in a production environment but are necessary for development workflows.

Q6. What is Tree Shaking?
Ands.Tree shaking, in the context of Parcel, refers to the process of eliminating unused code or dead code from the final bundle. It's a form of optimization that helps reduce the size of the JavaScript bundle produced by Parcel. This optimization ensures that only the code that is actually used in the application is included in the bundle, resulting in smaller file sizes and faster load times for the web application.

Q7.what is HMR?
Ans.Hot Module Replacement (HMR) is a feature in Parcel that allows developers to update modules in the application without requiring a full page refresh. When a module is modified during development, Parcel automatically injects the updated module into the running application, preserving the application's state. This enables developers to see changes reflected in the browser instantly, speeding up the development process and improving productivity.

Q8.- List down your favourite 5 superpowers of Parcel and describe any 3 of them in your
own words.
Ans.Hot Module Reload,Minification,optimization,differential bundling,diagnostics,Tree shaking and code splitting.

Q9.● - What is `.gitignore`? What should we add and not add into it?
Ans.gitignore is used to ignore those files which we do not intend to push in our git branch becuase it can take unnecessary space in our repo, so what are those files , the files we can regenerate again those files do not need to pushed in our main branch.
for example;nodemodules because we can regenrate them but we should push package.json and packge.lock.json with the help of these files we can regenrate our node modules.

Q10.● - What is the difference between `package.json` and `package-lock.json`
And. Package.json is made when we configure npm in our project it has name of our project and commands but in packge-lock.k=json it has integrity and hash of all the downloaded packges an dexact version we have downloaded at that time.

Q11.Why should I not modify `package-lock.json`?
And because ,it has exact version pf packges we have downloaded which is required for production.The package-lock.json file is automatically generated and updated by npm or Yarn to lock down the exact versions of dependencies and their sub-dependencies used in your project. Modifying it manually can lead to inconsistencies between what is specified in the lock file and what is actually installed, potentially causing issues with dependency resolution and project stability.

Q12.What is `node_modules` ? Is it a good idea to push that on git?
Ans. No , because we can regenrate node modules by just running a single command npm install because we package.json with the help of that we can download them again and it a huge file so its not a good idea to put them on git.

Q13.● - What is the `dist` folder?
Ans. this is made by Parcel bundler it has build files when we have dev build and if we want to make our production build it has production ready files in this folder.
In Parcel, the dist folder is the default output directory where the bundled and optimized files for production are placed after the build process. It typically contains the final version of your project ready for deployment, including minified and concatenated JavaScript files, optimized images, and any other assets required for the application to run.

Q14.- What is `browserlists`
Ans.Browserslist is a configuration file or entry in the package.json used by various front-end tools like Autoprefixer, Babel, and PostCSS to determine which browser versions to support with CSS and JavaScript features. It allows developers to specify a list of target browsers, enabling these tools to automatically add vendor prefixes, polyfills, or transpile JavaScript code to ensure compatibility with the specified browsers.

Q15.Read about dif bundlers: vite, webpack, parcel
Ans.Development Experience: Vite and Parcel prioritize fast development and offer instant feedback through HMR, while Webpack's configuration flexibility allows for more fine-grained control but may require additional setup.

Optimization: Vite and Parcel focus on optimized builds out of the box, while Webpack requires additional configuration and optimization plugins to achieve similar results.

Community and Ecosystem: Webpack has a mature ecosystem with a wide range of loaders, plugins, and integrations, while Vite and Parcel are newer but rapidly growing with their own ecosystems.

Q16.● Read about: ^ - caret and ~ - tilda
And.The caret (^) and tilde (~) symbols are used in package.json files to specify version ranges for dependencies.
**Caret (^):**
The caret symbol allows npm to update the dependency to the latest minor or patch version within the specified major version range.
For example, if a dependency is specified as "^1.2.3", npm can update it to any version within the 1.x.x range, such as 1.3.0 or 1.4.5, but not 2.0.0.

**Tilde (~):**
The tilde symbol restricts npm to update the dependency only to the latest patch version within the specified minor version range.
For example, if a dependency is specified as "~1.2.3", npm can update it to any version within the 1.2.x range, such as 1.2.4 or 1.2.9, but not 1.3.0.
