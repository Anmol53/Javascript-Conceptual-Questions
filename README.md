1.  ## What are the primitive data types in JS?

    There are 6 primitive data types:

    1. string
    2. number
    3. bigint
    4. boolean
    5. undefined
    6. symbol

    ***

2.  ## What's the difference between a variable that is: null, undefined or undeclared?

    **`undefined`** is a variable that has been declared but no value exists and is a type of itself ‘undefined’.

    **`null`** is a value of a variable and is a type of object.

    A variable is **`undeclared`** when it does not use the var keyword. It gets created on the global object, thus it operates in a different space as the declared variables.

    ***

3.  ## What is the difference between while and do-while loops in JavaScript?

    In _**While** `(Entry Control)`_ loop, the condition tested at the beginning of the loop, and if the condition is True, statements inside the loop will execute. It means the While loop executes the code block only if the condition is True.

    In _**Do While** `(Exit Control)`_ loop, the condition is tested at the end. So, Do While executes the statements in the code block at least once even if the condition Fails.

    ***

4.  ## What language constructions do you use for iterating over object properties and array items?

    For iterating over array :-

    - for loop
    - forEach
    - every
    - some
    - map
    - filter
    - reduce<br><br>

    For iterating object properties :-

    - for...in
    - Object.getOwnPropertyNames()

    ***

5.  ## What are the promises and how do they work?

6.  ## What are IIFEs and explain with an example where they can be used?

7.  ## Explain event delegation.

8.  ## Explain how this works in JavaScript.

- ### Can you give an example of one of the ways that working with this has changed in ES6?

9.  ## Explain how prototypal inheritance works.

10. ## What is a closure, and how/why would you use one?

11. ## Can you describe the main difference between the Array.forEach() loop and Array.map() methods and why you would pick one versus the other?

    The <span style="color:#ff2e63;">_Array.forEach()_</span> method receives a function as an argument and executes it once for each array element. It returns _`undefined`_.

    The <span style="color:#ff2e63;">_Array.map()_</span> method receives a function as a argument. Then it applies it on each element and returns an _`entirely new array`_ populated with the results of calling the provided function.

12. ## What's a typical use case for anonymous functions?

13. ## What's the difference between host objects and native objects?

14. ## Explain the difference between: function Person(){}, var person = Person(), and var person = new Person()?

15. ## Explain the differences on the usage of foo between function foo() {} and var foo = function() {}

16. ## Can you explain what Function.call and Function.apply do? What's the notable difference between the two?

    Both <span style="color:#ff2e63;">Function.prototype.call</span> and <span style="color:#ff2e63;">Function.prototype.apply</span> are used to set the value of _`this`_ explicitly. While call takes a list of arguments in comma separated format, apply takes an array with list of arguments.

17. ## Explain Function.prototype.bind.

    <span style="color:#ff2e63;">Function.prototype.bind</span> is used to set _`this`_ explicitly. It returns a function with given this context that can be called later.

18. ## What's the difference between feature detection, feature inference, and using the UA string?

19. ## Explain "hoisting".

20. ## Describe event bubbling.

21. ## Describe event capturing.

22. ## What's the difference between an "attribute" and a "property"?

23. ## What are the pros and cons of extending built-in JavaScript objects?

24. ## What is the difference between == and ===?

    > **==** abstract equality operator<br> **===** strict equality operator

    The **==** operator will compare for equality after doing any necessary type conversions. The **===** operator will not do the conversion, so if two values are not the same type === will simply return false. Both are equally quick.

    ***

25. ## Explain the same-origin policy with regards to JavaScript.

26. ## Why is it called a Ternary operator, what does the word "Ternary" indicate?

    **_Ternary_** means operands with three parameter. This is a one-line shorthand for an if-else statement. It is also called a conditional operator.

    `conditional ? truethy_block : falsey_block`

    ***

27. ## What is strict mode? What are some of the advantages/disadvantages of using it?

28. ## What are some of the advantages/disadvantages of writing JavaScript code in a language that compiles to JavaScript?

29. ## What tools and techniques do you use debugging JavaScript code?

30. ## Explain the difference between mutable and immutable objects.

    - ### What is an example of an immutable object in JavaScript?
    - ### What are the pros and cons of immutability?
    - ### How can you achieve immutability in your own code?

31. ## Explain the difference between synchronous and asynchronous functions.

32. ## What is an event loop?

    - ### What is the difference between call stack and task queue?

33. ## What are the differences between variables created using let, var or const?

34. ## What are the differences between ES6 class and ES5 function constructors?

35. ## Can you offer a use case for the new arrow => function syntax? How does this new syntax differ from other functions?

36. ## What advantage is there for using the arrow syntax for a method in a constructor?

37. ## What is the definition of a higher-order function?

38. ## Can you give an example for destructuring an object or an array?

39. ## Can you give an example of generating a string with ES6 Template Literals?

40. ## Can you give an example of a curry function and why this syntax offers an advantage?

41. ## What are the benefits of using spread syntax and how is it different from rest syntax?

42. ## How can you share code between files?

43. ## Why you might want to create static class members?
