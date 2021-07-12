[<img src="assets/images/su-logo.png" alt="Skills Union Logo" height="80px" />](https://www.skillsunion.com/)

# JavaScript Functions: Study

Use [DuckDuckGo](https://duckduckgo.com/) or your preferred search engine along with the provided resources to research and answer the [questions below](#questions).

## Required Reading

- [MDN: Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions)

  Read till the [The function expression (function expression)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions#the_function_expression_function_expression) section, skip every section afterwards.

- [MDN: Function declaration](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/function)
- [MDN: Function expression](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/function)
- [Function Declarations vs. Function Expressions](https://javascriptweblog.wordpress.com/2010/07/06/function-declarations-vs-function-expressions/)

## Optional Reading

- [JavaScriptInfo: Functions](https://javascript.info/function-basics)
- [QuirksMode: Functions](https://www.quirksmode.org/js/function.html)

## Questions

1. What is a function?

   ```
   A function is a block of code that can be called, accept, and return values.
   ```

2. What is the difference between function declaration and function expression?

   ```
   A function declaration is a defined object, declared with 'funtion' and a name. A declared function can be called before it is declared as the funtion object is hoisted to the top of the script.

   A function expression cannot be hoisted and must be used after the function variable has been created. The funtion expression is created as a defined variable and can be annoymous (unamed).
   ```

3. Write an example function declaration:

   ```js
   console.log(Input("Steve"));

   function Input(name) {
     return "Hello " + name;
   }
   ```

4. Write an example function expression:

   ```js
   let hello = function (name) {
     return "Hello " + name;
   };

   console.log(hello("Sean"));
   ```

5. Using a "Fist to Five", what is your comfort and clarity level?

   ```
   Comfort: 3

   Clarity: 3
   ```

### Response Guidelines

Please follow these guidelines as you answers these questions:

- Cite any relevant sources consulted during your research
- Do not reply using direct quotes from the source material
- Provide an answer using your own words and voice
