# yeoman-expressjs-generator-demo

A demo illustrating the usage of [YEOMAN](http://yeoman.io) scaffolding tool generator for basic Node/Express application using [generator-galvanize-express](https://github.com/gSchool/generator-galvanize-express)

## Install prerequisites

Make sure you have NodeJS and npm installed. You can check if you have Node and npm installed by typing:

```
node --version && npm --version
```

Once you’ve got Node installed, install the Yeoman toolset:

```
npm install --global yo
```

Verify Yeoman installation:

```
yo --version
```

Install the generator:

```
npm install -g generator-galvanize-express
```

Install gulp:

```
npm install -g gulp
```

## Install

Once you have installed all the dependencies, create the project directory:

```
mkdir yeoman-expressjs-generator-demo && cd yeoman-expressjs-generator-demo
```
This folder is where the generator will place your scaffolded project files.


Run yeoman command to see all installed generators:

```
yo
```
Or, run yeoman command to create the project structure using the generator specified:

```
yo galvanize-express
```
Configure the generator by specifying the values to the promts presented by the genrator.
At the end of this step, Yeoman will automatically scaffold out your app in the current directory. Take a look at the project struture generated.

Then, install the project dependencies:
```
npm install
```

## Running the application

Use gulp to start the application:
```
gulp
```
This would execute all the gulp tasks configured in [gulpfile.js] and start the server on localhost:35729.

Or, you can run the express server directly:

```
npm start
```
This would start the server on localhost:3000.
