# Welcome

This is a sample documentation page created with mkdocs.

Here are some blocks: 

```blocks
basic.showString("Hello world")
```

and more blocks:


```blocks
basic.forever(() => {
    basic.showLeds(`
        . # . # .
        # . # . #
        # . . . #
        . # . # .
        . . # . .
        `)
    basic.showLeds(`
        . # . # .
        # # # # #
        # # # # #
        . # # # .
        . . # . .
        `)
})
```

For more information, go to [Microsoft/pxt-mkdocs-sample](http://github.com/Microsoft/pxt-mkdocs-sample).