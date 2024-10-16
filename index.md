##  I am smaller
# I am bigger.

![FreeTube Logo](https://github.com/user-attachments/assets/fb1cf81f-bfa4-40ff-9f2e-31d46fbdf980)
### A Random Piece of Code from my Pong Clone in 6502 Nes Assembly:
``` assembly
giveplayer1ball:
    LDA #$00
    STA ballright
    LDA #$01
    STA ballleft
    JSR GAMEENGINEDONE
```
