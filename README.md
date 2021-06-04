![img js](https://pluralsight2.imgix.net/paths/images/javascript-542e10ea6e.png)

In this project I learned how to work with CLI commands and execute a non-web server Node.js JavaScript code.

<br>

Here is the code from project 1
```js
/*
 CIT 281 Project 1
 Name: Thomas Guthrie
*/

console.log(["Sunday","Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday"][new Date().getDay()])
```

```js
/*
 CIT 281 Project 1
 Name: Thomas Guthrie
*/

// Returns a random number between min (inclusive) and max (exclusive)
function getRandomInteger(min, max) {
    return Math.floor(Math.random() * (max - min) + min);
}

function getRandomString() {
    let stringLength = getRandomInteger(5,25)
    const randomLetters = 'abcdefghijklmnopqrstuvwxyz';
    let result = '';
    for ( let i = 0; i < stringLength; i++ ) {
        result += randomLetters.charAt(getRandomInteger(0,25));
    }
    return result;
}

console.log(String(getRandomString()));
```
