# Study Guide Webpage

## Description

This Study Guide is designed to help learners to find information quickly and easily.The application eases the studying process and helps students gain confidence and to progress in web development faster.
The _Study Guide Webpage_ project provided me with an understanding how to work with GitHub and how to use Git flow. This project gave me an idea of how applications are developed in the real world.

## Installation

N/A

## Usage

####HTML

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Prework Study Guide</title>
    <link rel="stylesheet" href="./assets/style.css" />
  </head>
  <body>
    ....
  </body>
</html>
```

```html
<script src="./assets/script.js"></script>
```

####CSS

```css
.selector,
.selector-secondary {
  ...;
}
```

####JavaScript

```js

var topics = ['HTML', 'CSS', 'Git', 'JavaScript'];

var randomTopic = topics[Math.floor(Math.random() * topics.length)]


function listTopics() {
 for(let x = 0; x < topics.length; x++) {
  console.log(topics[x]);
 }
}

function selectTopic ()  {
  ...
}
selectTopic()
```

## Credits

N/A

## License

The _Study Guide Webpage_ project is released under the
[MIT license](https://opensource.org/licenses/MIT).
