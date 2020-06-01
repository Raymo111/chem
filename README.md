# Snakes & Ladders
HTML5 E-Learning game on basis of Multiple Choice Questions. Upon reaching certain squares, a question will be asked to the player. If they get the question right, the marker will ascend the ladder. Otherwise, they will slide down the snake. What are you waiting for? Let's play!

Original author: [Ashok Shah](https://www.shahnashok.com)
Chemistry adaptation: [Raymond Li](https://raymond.li)
[DEMO](https://raymond.li/chem)

## Browser Support
- IE 10+
- Chrome
- Safari
- Firefox

## Disclaimer
I in no way wrote all this code in 2 weeks. Since Ashok's repo was licensed under the MIT license, I forked it and made it chem stuff.

## Questions
Questions were taken from past IB HL Chem Paper 1s. They were painstakingly inserted into `js/sl.config.js`. These questions are then selected randomly to appear in the game.

Sample question format (In case I forget or you want to add more):
```
{
  level:"1",
  theme: "Chem",
  question: "Why?",
  answers: ["life", "code", "chem", "language"],
  correct: 3
},
```
