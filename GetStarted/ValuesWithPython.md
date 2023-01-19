# Values #

This is your first lesson:
- I will first explain a few things, and then
- I will give you a few things to try in the [Playground](https://www.w3schools.com/python/trypython.asp?filename=demo_default).

This lesson is all about *Values*.

Values in a program are important:
* `123` is a value. It is a number of one hundred and twenty three.
* `Jan` is a value. It is my name!
* `2.3` is also a value. Slightly more than two but still less than three.

Your program is going to work with values all the time. In your first program you wrote:

```
print("Hello, World!")
```

The `Hello, World!` part of that program is a value. It means nothing to Python. The computer just use it because you said it should. The computer does not know the difference in meaning between `Hello` and `Goodbye`. The computer also does not know if you made a spelling mistake. The computer only knows they are different, but does not know which one comes first or last - unless you tell it! So they are just *values* and you will tell the computer what to do with all the values you give it.

On the other hand, `print` is not a value. `print` is an _instruction_. Each time your program says `print`, the computer writes something on the screen. What he writes, is the `value`.

Question: How does the computer know the difference betweeh instructions and values?

**The computer looks at the way we write them!**

Any numbers, you can just write like a number:
- `123`
- `1`
- `-2.3`

All of those are numbers also called _numeric values_.

Because they are numbers, the computer can do maths with them. You can also write:
- `123 + 456`
- `6 * 4`
- `20 - 5`
- `55 / 11`

The `/` character means divide and `*` means multiply.

But we also have _textual values_, which is anything else the computer can write on the screen, such as:
- `Hello, World!`
- `My name is Jan`
- `Dear Mommy, I am now 20 years old and I miss your cooked dinners. With all my Love. Christy`

For all your first programs, those are the only types of values you will use:

- `numbers`
- `strings`

_strings_???

The word `string` refers to a line of text.

And the only instruction you will use is `print`.

---

Practice:

Tell the computer to write a few different values. Each time, you must write `print()` and put a value between the brackets.

Write all of this in the [Playground](https://www.w3schools.com/python/trypython.asp?filename=demo_default) the click `[Run>]` to see what they do. Then you can change them and `[Run>]` again...

```
print("Goodbye!")
print("What are you doing???")
print(5+6)
print(12/2)
print(1+2+3+4+5)
```

Note the following:
- When we write a number, it is just the number, e.g. `12` or just the formula `12/2`.
- When we write a string, we put it in quotes `"..."` or `"Hello"`.

That is very important. Quote all values that are not numbers!

---

Practice:

Try to add numbers and add strings with this program in the [Playground](https://www.w3schools.com/python/trypython.asp?filename=demo_default):

```
print("Hello" + "My" + "Friend")
print(1 + 2 + 3)
```

When you add strings, they are just written one after the other.

When you add numbers, they are summed to give you the total value. `1 + 2 + 3` sums to the value of `6`.

Now try to add a number inside quotes:

```
print(1 + 2 + 3)
print("1" + "2" + "3")
```

You will see that a number inside `"..."` is also a string. So that prints `123` and not the summed value of `6`.

Important: anything in `"..."` we say is `in quotes` or a `quoted value` and the computer treats it as a string, not a number, even if it's a quoted number.

---

Practice:

Play with spacing in your print instructions in the [Playground](https://www.w3schools.com/python/trypython.asp?filename=demo_default)

```
print(1+2+3)
print(       1 + 2 + 3          )
print(1            + 2        + 3)
print(       3 + 2 + 1      )
```

All of those will sum the numbers and print 6 like this:
```
6
6
6
```

So the spacing you have inside the `(   )` brackets means nothing to the computer.

Now change that same program and put a `"` after each _opening bracket_ `(` and before each _closing bracket_ `)` like this:
```
print("1+2+3")
print("       1 + 2 + 3          ")
print("1            + 2        + 3")
print("       3 + 2 + 1      ")
```

Now the output is very different because the values are strings and no math calculations were done, AND the space characters inside the quotes were also part of the value and printed:

```
1+2+3
       1 + 2 + 3          
1            + 2        + 3
       3 + 2 + 1      
```

May be that looks simple, but it is important to understand. Try one more the following and see if you can guess what it will print before you run it:

```
print("abc"                 )
print("                 abc")
print(                 "abc")
```

What will that print?

The space inside the `(  )` is ignored, but the space inside the `"  "` is prat of the value and not ignored.

---
Practice:

Here is how it is used:
```
print("|----------------------------------------|")
print("|Invoice: INV0001                        |")
print("|----------------------------------------|")
print("|Item|Description                   |Cost|")
print("|  1 |Cooldrink                     |  10|")
print("|  2 |Chocolate                     |  15|")
print("|                                   +----|")
print("|                             Total:|  25|")
print("|----------------------------------------|")
```

[NEXT: Variables](./ValuesWithPython.md)
