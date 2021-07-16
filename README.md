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

3.  ## What are the differences between variables created using let, var or const?

    ***

4.  ## What is the difference between == and ===?

    > **==** abstract equality operator<br> **===** strict equality operator

    The **==** operator will compare for equality after doing any necessary type conversions. The **===** operator will not do the conversion, so if two values are not the same type === will simply return false. Both are equally quick.

    ***

5.  ## Why is it called a Ternary operator, what does the word "Ternary" indicate?

    **_Ternary_** means operands with three parameter. This is a one-line shorthand for an if-else statement. It is also called a conditional operator.

    `conditional ? truethy_block : falsey_block`

    ***

6.  ## Can you give an example of generating a string with ES6 Template Literals?

    ***

7.  ## What are the benefits of using spread syntax and how is it different from rest syntax?

    ***

8.  ## Can you give an example for destructuring an object or an array?

    Destructuring is a JavaScript expression that makes it possible to unpack values from arrays, or properties from objects, into distinct variables.

    Below is the example of Array Destructuring.

        let array = ["Javascript", "is", "awesome", "😍"];
        let [firstEle, secondEle] = array;

        console.log(firstEle);//"Javascript"
        console.log(secondEle);//"is"

    Below is the example of Object Destructuring.

        let car = {
            name: "Model S",
            brand: "Tesla",
            type: "e-Vehicle"
        };

        let {name, brand, type} = car;

        console.log(name);//"Model S"
        console.log(brand);//"Tesla"
        console.log(type);//"e-Vehicle""

    ***

9.  ## What language constructions do you use for iterating over object properties and array items?

    For iterating over array :-

    -   for loop
    -   forEach
    -   every
    -   some
    -   map
    -   filter
    -   reduce<br><br>

    For iterating object properties :-

    -   for...in
    -   Object.getOwnPropertyNames()

    ***

10. ## Can you describe the main difference between the Array.forEach() loop and Array.map() methods and why you would pick one versus the other?

    The <span style="color:#ff2e63;">_Array.forEach()_</span> method receives a function as an argument and executes it once for each array element. It returns _`undefined`_.

    The <span style="color:#ff2e63;">_Array.map()_</span> method receives a function as a argument. Then it applies it on each element and returns an _`entirely new array`_ populated with the results of calling the provided function.

    ***

11. ## What is the difference between while and do-while loops in JavaScript?

    In _**While** `(Entry Control)`_ loop, the condition tested at the beginning of the loop, and if the condition is True, statements inside the loop will execute. It means the While loop executes the code block only if the condition is True.

    In _**Do While** `(Exit Control)`_ loop, the condition is tested at the end. So, Do While executes the statements in the code block at least once even if the condition Fails.

    ***

12. ## What is the definition of a first-class function?

    A programming language is said to have **First-class functions** when functions in that language are treated like any other variable. In such a language, a function can be assigned as a value to a variable, can be passed as an argument to other functions, and can be returned by another function. Javascript supports First-class functions, In JavaScript functions are a _special type of object_.

    ***

13. ## What is the definition of a higher-order function?

    A **higher-order function** is a function that accepts functions as parameters and/or returns a function.

    Read this article [Understanding Higher-Order Functions in JavaScript](https://blog.bitsrc.io/understanding-higher-order-functions-in-javascript-75461803bad) for deep understanding.

    ***

14. ## What are IIFEs and explain with an example where they can be used?

    ***

15. ## Describe event bubbling and event capturing.

    This article [JavaScript - Event order](https://www.quirksmode.org/js/events_order.html) on quirksmode is a very good resource to understand event bubbling and capturing in detail.

    ***

16. ## Explain event delegation.

    **Event delegation** allows us to add event listeners to the parent instead of having to add event listeners individually for each child. It uses _`event bubbling`_, where the event on the child is bubbled up to the parent. When the event bubbles up to the parent element, we can check the event object's target property to gain a reference to the actually clicked child element. This becomes more handy when child elements are frequently added and removed from the parent element.

    ***

17. ## Explain "hoisting".

    ***

18. <h2> Explain how <code>this</code> works in JavaScript.
        <h3>
            <ol type="a">
                <li>Can you give an example of one of the ways that working with <code>this</code> has changed in ES6?</li>
            </ol>
        </h3>
    </h2>

    ***

19. ## What's a typical use case for anonymous functions?

    ***

20. ## What is a closure, and how/why would you use one?

    ***

21. ## Can you explain what Function.call and Function.apply do? What's the notable difference between the two?

    Both <span style="color:#ff2e63;">Function.prototype.call</span> and <span style="color:#ff2e63;">Function.prototype.apply</span> are used to set the value of _`this`_ explicitly. While call takes a list of arguments in comma separated format, apply takes an array with list of arguments.

    ***

22. ## Explain Function.prototype.bind.

    <span style="color:#ff2e63;">Function.prototype.bind</span> is used to set _`this`_ explicitly. It returns a function with given this context that can be called later.

    ***

23. ## What are the promises and how do they work?

    ***

24. ## Explain how prototypal inheritance works.

    ***

25. ## What's the difference between host objects and native objects?

    ***

26. ## Explain the difference between: function Person(){}, var person = Person(), and var person = new Person()?

    ***

27. ## Explain the differences on the usage of foo between function foo() {} and var foo = function() {}

    ***

28. ## What's the difference between feature detection, feature inference, and using the UA string?

    ***

29. ## What's the difference between an "attribute" and a "property"?

    ***

30. ## What are the pros and cons of extending built-in JavaScript objects?

    ***

31. ## Explain the same-origin policy with regards to JavaScript.

    ***

32. ## What is strict mode? What are some of the advantages/disadvantages of using it?

    ***

33. ## What are some of the advantages/disadvantages of writing JavaScript code in a language that compiles to JavaScript?

    ***

34. <h2> Explain the difference between mutable and immutable objects.
        <h3>
            <ol type="a">
                <li>What is an example of an immutable object in JavaScript?</li>
                <li>What are the pros and cons of immutability?</li>
                <li>How can you achieve immutability in your own code?</li>
            </ol>
        </h3>
    </h2>

    ***

35. ## Explain the difference between synchronous and asynchronous functions.

    ***

36. <h2> What is an event loop?
        <h3>
            <ol type="a">
                <li>What is the difference between call stack and task queue?</li>
            </ol>
        </h3>
    </h2>

    ***

37. ## What are the differences between ES6 class and ES5 function constructors?

    ***

38. ## Can you offer a use case for the new arrow => function syntax? How does this new syntax differ from other functions?

    ***

39. ## What advantage is there for using the arrow syntax for a method in a constructor?

    ***

40. ## Can you give an example of a curry function and why this syntax offers an advantage?

    ***

41. ## How can you share code between files?

    ***

42. ## Why you might want to create static class members?

    ***
