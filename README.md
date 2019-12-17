# Hearts

## Introduction
Anyone up for a game of Hearts?

## Objective
Using what you learned about loops and conditional statements, create a standard deck of cards and deal out all the cards to the four players. 

## Requirements
The following requirements must be met in order to complete the assignment successfully:

### Step 1 
Clone this repository from GitHub. **Aside from this README file, there are NO starter files for this assignment.** 

### Step 2 
Create an `index.html` file with the standard HTML5 structure. Add the provided `script.js` file to the `index.html` file using the `<script></script>` tag.

### Step 3 
Using the provided `suits` and `ranks` arrays and nested loops, create an array of objects. Each object will contain `suit` and `rank` property representing each card in a standard deck of cards.

*The computed array of objects should look something like this*
```js
[
  {"suit":"clubs","rank":2},
  {"suit":"clubs","rank":3},
  {"suit":"clubs","rank":4},
  {"suit":"clubs","rank":5},
  {"suit":"clubs","rank":6},
  ...
  {"suit":"spades","rank":"J"},
  {"suit":"spades","rank":"Q"},
  {"suit":"spades","rank":"K"},
  {"suit":"spades","rank":"A"}
]
```

### Step 4
Using the provide `shuffle()` function, shuffle the newly created deck of cards (Refer to the Shuffle Function section below). Store the results of the `shuffle()` to a new variable. 

### Step 5
Using the shuffled deck and players object, deal out a card to each player one card at a time until every card has been dealt. Each player should have 13 cards.

### Step 6
Using loops, find the player that is holding the Queen of Hearts and display a message to the console.

## Shuffle Function
The following screencast shows how to use the provided `shuffle()` function.

[A Custom Shuffle Function](https://scrimba.com/c/cR3EJaTk)

## Rubric

| Task | Points |
| ---  | :---:  | 
| Creates a full deck of cards | 3 |
| Shuffles the deck of cards | 1 |
| Deal out the cards to each player properly  | 3 |
| Finds the player with Queen of Hearts | 3 |
| **Total** | **10** | 


## Submission
When the assignment is completed, follow the steps below to submit for grading:

1. Create a commit with the message "Completes the Hearts assignment"
2. Push all commits to GitHub.
3. Submit the URL to your GitHub repository to the **Hearts** assignment on BrightSpace.  