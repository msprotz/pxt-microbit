# On Button Pressed

Register an [event handler](/microbit/reference/event-handler) that will execute whenever an input button (A, B, or A and B together) is pressed during program execution. When [running code](/microbit/js/simulator) with this function in a web browser, click an on-screen input button - labelled A or B.

```sig
input.onButtonPressed(Button.A, () => {})
```

### Example: count button clicks

This example counts how many times the left or right input button is pressed. Each time a button is pressed, the global count variable is increased by 1 and displayed on the screen.

```blocks
let count = 0
basic.showNumber(count)
input.onButtonPressed(Button.A, () => {
    count++;
    basic.showNumber(count);
})
```

### Example: roll a dice

This example generates a random number when you press the B input button, and then displays a random die image:

```blocks
input.onButtonPressed(Button.B, () => {
    let dice = Math.random(6)
    basic.showNumber(dice)
})
```

### Lessons

[smiley](/microbit/lessons/smiley), [answering machine](/microbit/lessons/answering-machine), [screen wipe](/microbit/lessons/screen-wipe), [rotation animation](/microbit/lessons/rotation-animation)

### See also

[button is pressed](/microbit/reference/input/button-is-pressed), [forever](/microbit/reference/basic/forever)
