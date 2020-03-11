# React Glossary

### npm
A command line tool for handling packages of reusable JavaScript code designed to be shared.

### package.json
A list of dependencies, or what packages are required for a given js application. You can check for its presence by running “npm test” which will return “hotdog”. Running npm init  will create or edit an existing package.json file.

### npm install
Reads the package.json file and downloads the packages from npmjs.com where they are hosted. Will likely result in a dependency tree because the packages have dependencies, which have dependencies etc. To install a package in our local JSON file, run npm install followed by the package name.

### node
A JS runtime, allowing JavaScript to be run locally on your computer, instead of in a browser. A runtime is the period in which a computer is executing or software designed to support the execution of computer programs.

### framework
A standardized way of creating and deploying web applications.

### React
A JS framework with a specific way for designing and structuring a JS app, it offers both performance and composition benefits through its virtual DOM and JS extension, JSX.

### virtual DOM


### Babel
A transpiler that converts JSX into vanilla JS.

### Webpack


### JSX
An extension of vanilla JS similar to html, it follows a declarative writing structure meaning you can express what you want the UI to look like and JSX will take care of the rest.

### declarative vs. imperative(style of programming)
To write imperative code is to write how something is done in detail(written *explicit* steps). Declarative means you write what you would *like* to do. Most vanilla JS is imperative. React is considered declarative because you can create the structure of the UI without giving it the explicit commands necessary for DOM manipulation in traditional JS.


### modular code
Code that is separated into separate files with each module being responsible for a single feature or functionality. Reasons you would want to separate your code into modules:
- adhere to the single responsibility principle
- easier to navigate
- easier to debug
- produces clean and DRY code (DRY - Don’t Repeat Yourself vs. WET - Write Everything Twice)

### component
Components modularize both functionality and presentation in our code, letting us split the UI into independent, reusable pieces, freeing us to think about each piece in isolation.

### component chain
The practice of linking files through importing and exporting.

### export default
We export to allow other files to import a files contents. Export default lets us denote that whatever follows that statement is the main thing we want to export.

### dynamic vs static components


### props
Props - short for "properties" - are reusable values that are passed down from a parent component to a child component. Props can be any datatype.

### default props
A prop value assigned by the component responsible for rendering the props in the case that the props it receives are not what is expected and/or wanted. Default props should be used in the child component as opposed to conditional logic in the parent component passing the props to adhere to the single responsibility principle.

### callback function


### the recursive component


### arrow functions in React


### the ternary in React


### state


### initial state


### this.setState()


### previous state


### synthetic events


### event pooling


### supported events


### event bubbling vs capturing


### controlled form


### onChange


### onSubmit
