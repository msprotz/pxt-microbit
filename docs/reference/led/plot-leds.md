# Plot LEDs

Display an [Image](/reference/images/image) on the BBC micro:bit's [LED screen](/device/screen). NOTE: `basic -> plot image` has been replaced by `basic -> show leds`.

```sig
basic.plotLeds(`
. . . . .
. # . # .
. . # . .
# ; . . #
. # # # .
`)
```

### Parameters

* leds - a series of LED on/off states that form an image (see steps below)

### Example: simley

```blocks
basic.plotLeds(`
. . . . .
. # . # .
. . # . .
# ; . . #
. # # # .
`)
```

### See also

[show animation](/reference/basic/show-animation), [image](/reference/images/image), [show image](/reference/images/show-image), [scroll image](/reference/images/scroll-image)

