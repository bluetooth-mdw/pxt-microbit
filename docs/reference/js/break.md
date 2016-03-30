# Break

Break statement; exit a for or while loop. #docs #break #language #loop #for #while

### @parent js/language
 

Exit a [while](/microbit/js/while) or [for](/microbit/reference/loops/for) loop before the loop is complete.

### Touch Develop syntax

**break**

### Example: count to a random number

The following example counts from 0 to a random number from 0-9. When the for loop counter equals the random number (`i = x`), the `break` statement exits the loop:

```
let x = Math.random(10)
for (let i = 0; i < 10; i++) {
    if (i == x) {
        break
    } else {
        basic.showNumber(i, 0)
        basic.pause(500)
    }
}
```

### Lessons

[jailbreak](/microbit/lessons/jailbreak)

### See also

[for](/microbit/reference/loops/for), [while](/microbit/js/while)
