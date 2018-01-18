npm is most commonly used for managing Node.js modules, but it works for the front-end too when combined with Browserify and/or $ npm dedupe.

Bower is created solely for the front-end and is optimized with that in mind. The biggest difference is that npm does nested dependency tree (size heavy) while Bower requires a flat dependency tree (puts the burden of dependency resolution on the user).

browserify :Browsers don't have the require method defined, but Node.js does. With Browserify you can write code that uses require in the same way that you would use it in Node.

watchify: Update any source file and your browserify bundle will be recompiled on the spot.

UglifyJS: UglifyJS is a JavaScript compressor/minifier written in JavaScript

Gulp: gulp is a toolkit for automating painful or time-consuming tasks in your development workflow

phantomJs: hedless browser with js for testing/screenshoot

ESLint
