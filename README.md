# simpleSliderPlugin 
SUPINFO AppFactory Plugin: simpleSliderPlugin

Use this plugin to showcase your images & photos in an image gallery or use it to provide slide-by-slide instructions.

###Install bower and node dependencies
```bash
$ bower install
$ npm install
```

##How to run and test
###Prerequisite are node.js,bower,npm,karma, karma-coverage
```bash
$ npm install -g karma-cli
$ npm install -g karma-coverage
$ npm install -g bower
```

###Run the test cases
```bash
$ npm test
Or
$ karma start --reporters progress
```
###Run the test cases to see coverage
```bash
$ karma start
```

##How to validate js via eslint
###Prerequisite are node.js,bower,npm,karma, karma-coverage
```bash
$ npm install -g gulp
```

###Installnode dependencies
```bash
$ npm install
```
###Run the validate
```bash
$ gulp validate
```