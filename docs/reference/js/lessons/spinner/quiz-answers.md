# spinner quiz answers

a spin the BBC micro:bit game with the input on shake #math #random #docs #shake

## Name

## Directions

Use this activity document to guide your work in the [spinner tutorial](/microbit/lessons/spinner/tutorial).

Answer the questions while completing the tutorial. Pay attention to the dialogues!

## 1. Write the code that stores a random number between 0 and 3 into a local variable named 'random arrow'.

<br/>

```
let randomArrow = Math.random(4)
```

## 2. Write the if statement that will display this down arrow from your code. Hint- This occurs if the local variable 'random arrow' returns 1. 

![](/static/mb/lessons/spinner-0.png)

<br/>

```
if (randomArrow == 1) {
    basic.plotImage(`
. . # . .
. . # . .
# # # # #
. # # # .
. . # . .
`)
}
```

## 3. Write the if statement that will display this right arrow. Hint- This occurs if the local variable 'random arrow' returns 2. 

![](/static/mb/lessons/spinner-1.png)

<br />

```
if (randomArrow == 2) {
    basic.plotImage(`
. . # . .
. . # # .
# # # # #
. . # # .
. . # . .
`)
}
```
