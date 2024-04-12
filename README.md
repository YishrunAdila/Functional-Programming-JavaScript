"There are several styles of coding, also known as paradigms. A common style is called functional programming, or FP for short.

In functional programming, we use a lot of functions and variables. When writing FP code, we keep data and functionality separate and pass data into functions only when we want something computed. In functional programming, functions return new values and then use those values somewhere else in the code.

To summarize this point, we can say that the Functional Programming paradigm works by keeping the data and functionality separate. Its counterpart, OOP, works by keeping the data and functionality grouped in meaningful objects. There are many more concepts and ideas in functional programming. Here are some of the most important ones:
           First-class functions
           Higher-order function
           Pure functions and side effects
There are many other concepts and principles in functional programming, but for now, let's stick to these three.
      First-class functions:
It is often said that functions in JavaScript are “first-class citizens”. What does that mean?
It means that a function in JavaScript is just another value that we can:
        pass to other functions
        save in a variable
        return from other functions
In other words, a function in JavaScript is just a value - from this vantage point, almost no different than a string or a number.
        Higher-order functions:
A higher-order function is a function that has either one or both of the following characteristics:
            It accepts other functions as arguments
            It returns functions when invoked
There's no "special way" of defining higher-order functions in JavaScript. It is simply a feature of the language. The language itself allows me to pass a function to another function, or to return a function from another function.
      Pure functions and side-effects: 
Another concept of functional programming is pure functions. A pure function returns the same result as long as it's given the same values.
