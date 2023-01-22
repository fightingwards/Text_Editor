# Text_Editor

## Description

A text editor that runs in the browser, is a single-page app that meets PWA criteria, features data persistence techniques, and functions offline.

## Table of Contents

- [Usage](#usage)
- [Acceptance Criteria](#acceptance-criteria)
- [Installation](#installation)
- [Technologies](#technologies)
- [Credits](#credits)
- [Badges](#badges)
- [Contribute](#how-to-contribute)
- [License](#license)

## Usage

View on [Heroku]

![JATE]

## Acceptance Criteria

```md
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```

## Installation

To run via local environment:

- Clone repository
- Run `npm i` to install dependencies
- Run `npm run start` from the root directory

## Technologies

- Webpack
- Workbox
- Express.js
- Javascript
- Service Worker

## Credits

UT Web Development Bootcamp

## Badges

[![made-with-javascript](https://img.shields.io/badge/Made%20with-JavaScript-1f425f.svg)](https://www.javascript.com)
[![Npm](https://badgen.net/badge/icon/npm?icon=npm&label)](https://https://npmjs.com/)
[![macOS](https://svgshare.com/i/ZjP.svg)](https://svgshare.com/i/ZjP.svg)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-no-red.svg)](https://bitbucket.org/lbesson/ansi-colors)
[![GitHub license](https://badgen.net/github/license/Naereen/Strapdown.js)](https://github.com/Naereen/StrapDown.js/blob/master/LICENSE)

## How to Contribute

[Contributor Covenant](https://www.contributor-covenant.org/)

## License

MIT License

Copyright (c) [2022] [fightingwards]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
