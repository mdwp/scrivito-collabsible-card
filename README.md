# Scrivito Collapsible Card
[![CMS: Scrivito](https://img.shields.io/badge/CMS-Scrivito-brightgreen.svg)](https://scrivito.com) [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

A collapsible card React component/Scrivito widget for the Scrivito CMS.

## Screenshot

![Screenshot](https://raw.githubusercontent.com/mdwp/scrivito-collapsible-card/master/collapsible-card-screenshot.png)


## Installation

Open your terminal.

`$ cd` to your Scrivito project

```shell
$ npm install scrivito-collapsible-card
```

Import the widget in your javascript (e.g. in `index.js` or `Widgets/index.js`).

Add this line to your index.js:

```js
import "scrivito-collapsible-card";
```

Also add the styling of the widget to your app. This can be done by either loading it via `css-loader` (e.g. in `index.js` or `Widgets/index.js`):

```js
import "scrivito-collapsible-card/index.css";
```

Or by including the styling to your style sheets (e.g. in `index.scss`):

```scss
@import "~scrivito-collapsible-card/index.css";
```

## Features
The Collapsible Card Widget renders a card with a header and a collapsible body. You can put any widget into the body.

## Widget properties

In the widget properties you can set:
- Card header image