# console.log-alias

##### a minimal lightweight console.log() alias for those who prefer to write this feature in their preferred language of choice (print, printf, echo...)

## Installation

-   ##### on the terminal, using npm:
-   `npm i console.log-alias --save`
-   ##### then, in Node.js

-   load the package:
    `const print = require('console.log-alias');`
-   now you can write print() instead of console.log()
    `print('hi');`
    `// hi`

#### OR, Install locally:

-   Clone this repository or download this .zip
-   Copy "index.js" to the root of your project folder, you can rename the file if you want.
-   load the package in your js file, this time by referencing the downloaded file:
-   don't forget the dot and forward slash before the file-name ./
    `const print = require('./index.js);`

## Features

-   By changing the name of the require variable, you can pretty much assign any name to the console.log function:

##### // Python, Swift, Perl, Logo..

`const print = require('console.log-alias')`

##### // Java, Kotlin, Rust, Julia

`const println = require('console.log-alias')`

##### // C

`const printf = require('console.log-alias')`

##### // C++

`const cout = require('console.log-alias')`

##### // C#

`const WriteLine = require('console.log-alias')`

##### // Bash, PHP

`const echo = require('console.log-alias')`

##### // Ruby

`const puts = require('console.log-alias')`

##### // Go

`const Println = require('console.log-alias')`

##### // R

`const cat = require('console.log-alias')`

##### // MATLAB

`const disp = require('console.log-alias')`

##### // Pascal

`const WriteLn = require('console.log-alias')`

##### // COBOL, ALGOL

`const DISPLAY = require('console.log-alias')`

##### // Fortran

`const write = require('console.log-alias')`

##### // Objective-C

`const NSLog = require('console.log-alias')`

##### // AppleScript

`const say = require('console.log-alias')`

##### // VBScript

`const MsgBox = require('console.log-alias')`

##### // BASIC

`const PRINT = require('console.log-alias')`

##### // JS short

`const log = require('console.log-alias')`

##### // JS Lazy

`const l = require('console.log-alias')`

## Basic template:

```
const echo = require('console.log-alias');

echo('hi');

```

## License

MIT

**Enjoy!**
