input.onGesture(Gesture.LogoDown, function () {
    while (true) {
        for (let X = 0; X <= 4; X++) {
            led.plot(X, 0)
            led.plot(0, 4 - X)
            led.plot(4 - X, 4)
            led.plot(4, X)
            basic.pause(100)
            led.unplot(X, 0)
            led.unplot(0, 4 - X)
            led.unplot(4 - X, 4)
            led.unplot(4, X)
            basic.pause(100)
        }
    }
})
input.onButtonPressed(Button.AB, function () {
    while (true) {
        for (let Outer = 0; Outer <= 4; Outer++) {
            reverse = 4 - Outer
            for (let inner = 0; inner <= 4; inner++) {
                led.plot(Outer, reverse)
                basic.pause(Speed)
                led.plot(reverse, Outer)
                basic.pause(Speed)
                led.plot(reverse - inner, reverse)
                basic.pause(Speed)
                led.plot(reverse, reverse - inner)
                basic.pause(Speed)
            }
        }
        for (let Outer2 = 0; Outer2 <= 4; Outer2++) {
            reverse = 4 - Outer2
            for (let inner2 = 0; inner2 <= 4; inner2++) {
                led.unplot(Outer2, reverse)
                basic.pause(Speed)
                led.unplot(reverse, Outer2)
                basic.pause(Speed)
                led.unplot(reverse - inner2, reverse)
                basic.pause(Speed)
                led.unplot(reverse, reverse - inner2)
                basic.pause(Speed)
            }
        }
    }
})
input.onGesture(Gesture.LogoUp, function () {
    for (let X = 0; X <= 4; X++) {
        led.plot(0, 2)
        led.plot(1, 2)
        led.plot(2, 0)
        led.plot(3, 2)
        led.plot(4, 2)
        basic.pause(500)
        led.unplot(0, 2)
        basic.pause(500)
        led.unplot(1, 2)
        led.plot(0, 2)
        basic.pause(500)
        led.unplot(2, 0)
        led.plot(1, 2)
        basic.pause(500)
        led.unplot(3, 2)
        led.plot(2, 0)
        basic.pause(500)
        led.unplot(4, 2)
        led.plot(3, 2)
        basic.pause(500)
    }
})
input.onGesture(Gesture.Shake, function () {
    while (true) {
        basic.showLeds(`
            # # . . .
            . # . . .
            . # # # .
            . # . # .
            . # . # .
            `)
        basic.showLeds(`
            # # . . .
            . # . . .
            . # # # .
            # . . . #
            . . . . .
            `)
        basic.showLeds(`
            # # . . .
            . # . . .
            . # # # .
            . # . # .
            . # . # .
            `)
        basic.showLeds(`
            # # . . .
            . # . . .
            . # # # .
            # . . . #
            . . . . .
            `)
    }
})
input.onButtonPressed(Button.A, function () {
    if (true) {
        while (true) {
            for (let X = 0; X <= 4; X++) {
                led.plot(0, 2)
                basic.pause(100)
                led.plot(1, 2)
                basic.pause(100)
                led.plot(2, 2)
                basic.pause(100)
                led.plot(3, 2)
                led.unplot(0, 2)
                basic.pause(100)
                led.plot(4, 2)
                led.unplot(1, 2)
                basic.pause(100)
                led.unplot(2, 2)
                basic.pause(100)
                led.unplot(3, 2)
                basic.pause(100)
                led.plot(3, 2)
                basic.pause(100)
                led.plot(2, 2)
                basic.pause(100)
                led.plot(1, 2)
                led.unplot(4, 2)
                basic.pause(100)
                led.unplot(3, 2)
                led.plot(0, 2)
                basic.pause(100)
                led.unplot(2, 2)
                basic.pause(100)
                led.unplot(1, 2)
                basic.pause(100)
            }
        }
    } else {
        led.stopAnimation()
        basic.clearScreen()
    }
})
input.onButtonPressed(Button.B, function () {
    led.stopAnimation()
    basic.clearScreen()
    basic.showstring(Hello!)
})
let reverse = 0
let Speed = 0
Speed = 10
