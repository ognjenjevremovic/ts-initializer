# TypeScript project starting point
A bit opinionated TypeScript linting and compiler rules, that suite my needs and help me ***keep the code clean and consistent***, aswell as ***maintain the code structure*** across all of my projects.

Feel free to use the rules in your own projects, modify them, tweak them arround or completely discard them - *it's up to you!*

# Usage
First things first, you'll need to initialize your project to use TypeScript.
In order to do that, you'll need to install TypeScript either globaly (this is my recommendation and the approach I take) or install it localy as a dev dependancy in your Node project.

&nbsp;

### Installing TypeScript
To install TypeScript globaly, run the command from your terminal/shell
```sh
$ npm install -g typescript
```
&nbsp;

To install TypeScript localy in your project (as a dev dependancy), run the command from your terminal/shell
```sh
$ npm install typescript --save-dev
```
&nbsp;

*Reason to install TypeScript as a dev dependancy instead of a production dependancy module (when installing it locally), is that you'll only be needing TypeScript during development and for compilation of your .ts files.*

&nbsp;

### Initializing TypeScript Project
To initialize a new TypeScript project, you'll need a TypeScript compiler configuration file - ***tsconfig.json***.

You can either:
 1. initialize it on your own by running the command from your terminal/shell (in your project directory):
 ```sh
$ tsc --init
```

or

 2. copy the compiler configuration from this repo (*tsconfig.json* file content) and paste it in your *tsconfig.json* project file.

&nbsp;

### Setting up the linting rules
Next up, you'll want to setup linting rules for you (and your team mates/co-workers/other developers) to follow.

You can either:
 1. initialize it on your own by running the command from your terminal/shell (in your project directory):
 ```sh
$ tslint --init
```

or

 2. copy the linting configuration from this repo (*tsconfig.json* file content) and paste it in your *tslint.json* project file.

&nbsp;

### License
Copyright (c) 2017 [Ognjen Jevremović](https://github.com/ognjenjevremovic)

Licensed under the [MIT](https://github.com/ognjenjevremovic/pretty-easy-date-check/blob/master/LICENSE) License.
