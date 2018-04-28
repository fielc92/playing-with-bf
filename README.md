# First brainfuck script.

There's no such thing as _difficult_, only lack of understanding.

## Mechanics of brainfuck.
[brainfuck wiki](https://en.wikipedia.org/wiki/Brainfuck)


| character | action |
| :------------- | :------------- |
| > | increment data pointer |
| < | decrement data pointer |
| + | increment byte at data pointer |
| - | decrement byte at data pointer |
| . | output byte at data pointer |
| , | accept one input byte, storing value in byte at data pointer |
| [ | if the byte at the data pointer is zero, then instead of moving the instruction pointer forward to the next command, jump it forward to the command after the matching ] command. |
| ] | if the byte at the data pointer is nonzero, then instead of moving the instruction pointer forward to the next command, jump it back to the command after the matching [ command. |

[brainfuck commands](https://en.wikipedia.org/wiki/Brainfuck#Commands)
