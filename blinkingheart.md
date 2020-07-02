# My Tutorial

## Step 1

Draw a heart

```blocks
basic.forever(function () {
    basic.showIcon(IconNames.Heart)
})
```

## Step 2

Add a second frame to flash the heart

```blocks
basic.forever(function () {
    basic.showIcon(IconNames.Heart)
    basic.showLeds(`
    . . . . .
    . . . . .
    . . . . .
    . . . . .
    . . . . .
    `)
})
```

## Step 3

Add a block to play a ``||music:sound||``!

```blocks
basic.forever(function () {
    basic.showIcon(IconNames.Heart)
    basic.showLeds(`
    . . . . .
    . . . . .
    . . . . .
    . . . . .
    . . . . .
    `)
    music.playTone(Note.C, music.beat())
})
```