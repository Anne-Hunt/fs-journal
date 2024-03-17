# Intro to JavaScript
01. Which keywords are used to declare a variable in JavaScript?

    > | var, let, const: "var" is no longer in common use and is only used for older browsers. "var" was capable of being used either in the block it was declared or in the entire window of the code depending one where it was declared, and can be re-declared in a different context or block/function, taking the second value in order as its value in that context. It was limited compared to using separate,  newer variables, "let" and "const", for the same purposes. "const" is used as a constant, as a variable that won't be changed and is the same. "let" is a variable that can be altered or redefined. The two split the previous use of var into different applications, allowing code to contain both constant and changing variables. Further, "let" can be updated, meaning its value can be changed, but it can't be redeclared unless it's used in a different scope, as in a specific block, a function. Even if "let" is initially declared and hoisted to the top of the code, it can be redeclared in a function because that's a different scope. "const", however, doesn't allow itself to be redeclared, updated, or used outside of the block in which it was declared. They also differ in how they are initialized, or the order in which their values are acknowledged and assigned. "var" can be declared and initialized as "undefined", allowing its value to be clarified later. "let" and "const" aren't initialized until they're used. They have to be declared before they are used, but only "const" must be initialized at the same time as well. |

02. What is the definition of a function?

    > | A function is an object that, pardon the pun, performs a function or sub-program of the program. It performs a job, a duty, and returns a result. If it doesn't return a result, it returns undefined. To be used it must be requested, known as "invoking". Their declarations are always hoisted, even when not placed at the top of the code with hoisted variables. Values, knowns as parameters, can be "passed" into them, meaning assigned to be used in the function. When they are used, they become arguments. |

03. What are the `SOLID` principles?

    > | SOLID is an acrostic for "Single responsibility, Open/Closed classes, Liskov substitution, Interface segregation, and Dependency inversion." S means that a class should only be responsbile for one thing. Too much responsibility means that if it stops working, multiple things stop. It also means that it isn't focused on doing one thing well. O means that classes, open and closed, should be extended but not modified.  They can be used beyond what was intended but not changed to do so. They should be open to being extended, but not require modification to do so (the closed part). L means that when possible, the parent class of a subclass should be able to be swapped in without breaking the function. So if a function calls for a Toyota Corolla, you should be able to substitute general cars without breaking the function. If it calls for a square, you should be able to use a parallelogram or rectangle. I means that no code should require methods it doesn't need. Having functions specific to their use rather than general functions that require more methods beyond the scope of the current use is problematic. D means that we should have a level of abstraction between different functions, rather than something that changes. Focus on the abstraction, not the detail. |

04. Given this array: How could you remove the `pineapple`?

    ```js
    let fruit = ['apple', 'banana', 'pineapple', 'orange', 'strawberry']
    ```

    > | for (let i = 0; i < fruit.length; i++) {
  if (fruit[i] === 'pineapple') {
    let deletePineapple = fruit.splice(i, 1);
  }
} |

05. Given these two objects: How could you add each to the others friends arrays?

    ```js
    let you = {
        name: "You",
        hair: true,
        friends: []
    }
    let them = {
        name: "Them",
        hair: false,
        friends: []
    }
    ```

    > | ANSWER HERE |

06. Give an example of a JavaScript `Conditional`:

    > | Conditional are functions that depend on the conditions of the declaration or function, so "if" or "if else if" statements. They work similarly to sorting or making choices about when to perform a function or return a result, based on what data is put in. Ternary operators are another example. They compare the input to the data requested and if it meets the result, they perform an action and return a result. |

07. What is the main difference between `parameters` and `arguments`?

    > | Parameters are what goes into a function when it is declared. Arguments are what is used in a function after it is declared. |

08. Instead of writing everything to the console, what is a better way to debug your code?

    > | ANSWER HERE |

09. What is the difference between a `primitive` value and a `reference` value?

    > | Reference values refer to structures or objects within Javascript, like objects, arrays, and functions. Primitive values refer to data that is not unique to Javascript in form, like numbers, boolean values, and undefined/null results. |

10. Demonstrate a loop that prints the numbers between -100 and 100?

    > | for(i= -100; i <= 100; i++) {
    console.log(i)} |
