# unit-3-code-analysis-practice

Using markdown, identify what the following code block does and explain how the `forEach` function works.

```js
function forEach(arr, action) {
  for (let i = 0; i < arr.length; i++) {
    action(arr[i]);
  }
}

forEach(['a', 'b', 'c'], console.log);
```

**Guiding Questions:**
* What does the code do (what does it print? are any variable reassigned? etc...)
The following code prints a b c to the console. For each loop iteration the variable is `array[i]` is being reassigned to the indiviual values in the array.

* What are the expected data types for each of the parameters?
The expected data types for each of the parameters is
1. Array
2. Object because technically functions are objects.

* When the function is invoked, what value are provided as arguments?
When the forEach function is invoked, the array ['a', 'b', 'c'] is passed as the first argument, and console.log is passed as the second argument. In other words the array ['a', 'b', 'c'] replaces the parameter arr and console.log replaces the parameter action.

* How does `forEach` use the provided arguments?

**Key Terms to use**: parameters, arguments, invoke/invocation, iterate, "element of the array", increment,  

<hr>

Your explanation here...
