# Dicee

A game based on javascript DOM(Document Object Model) manipulation to create two dice animated game. It Creates two dice, with each of its sides having random value and checks if one player has won or its a draw.

## Technology used 
1. HTML
2. CSS
3. JavaScript
4. Google font family

## Code Example

```javascript
 //If player 1 wins
if (randomNumber1 > randomNumber2) {
  document.querySelector("h1").innerHTML = "🚩 Play 1 Wins!";
}
else if (randomNumber2 > randomNumber1) {
  document.querySelector("h1").innerHTML = "Player 2 Wins! 🚩";
}
else {
  document.querySelector("h1").innerHTML = "Draw!";
}
```

## How to run

Open index.html in any modern browser and run the code.

## Screenshots

![alt text](./images/Screenshot%202022-11-23%20at%2012.39.17%20PM.png)


