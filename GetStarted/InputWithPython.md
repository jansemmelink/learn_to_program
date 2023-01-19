# Ask the User Some Questions #

When the computer asks you to enter a value, we say it is asking for _user input_.

The question it writes on the screen is called a _prompt_.

We also say the computer _promp_ you for _input_.

In normal English, that means the computer asks a question, then it waits for you to enter the answer, and then it proceeds with the rest of the program.

Your program will look like this:

```
name = input("Enter your name: ")

print(f"Hello {name}. What a lovely day!")
```

That program actually fails when I try it in the playground, but it is a valid program.

I think it fails in the playground because the school is afraid of security when hackers are allowed to enter anything into such playground programs.

So do not bother to run it there. You will get to run it soon on your own computer or when I find a playground where it works.

All it does is to ask the question:

```
Enter your name: 
```

Then you can type in your name, like I would type `Jan` then press `[enter]` and then the program continues to print:

```
Hello Jan. What a lovely day!
```

Important things to note:

```
name = ...
```

says the answer is stored in the variable called `name`.

```
= input("Enter your name: ")
```

is the instruction to ask the question `Enter your name: `

Note the space at the end of the question string value. If you do not put a space in there, it will still work, but it does not look as pretty when the user starts typing directly after the question...

If you can run the program, try it with and without the space to see what difference it makes.
