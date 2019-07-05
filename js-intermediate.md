# Intermediate JavaScript Quiz

The following questions should take you no longer than 3 hours to answer.  

1. Is it possible to nest `try` `catch` blocks inside one anoher? i.e. is the following okay?
```
try {
  ...
  try {
    ...
  } catch (ex) {
    ...
  }
} catch (ex) {
  ...
}
```

2. What would be the output to the console when the following JavaScript is executed?
```
const hello = name => {
  const message = `Hello ${name}`
  return () => {
    console.log(message)
  }
}
const helloBob = hello(`Bob`)
const helloJane = hello(`Jane`)
helloBob()
helloJane();
```

3. Write a function called `mapToNames` that maps an array of objects that has the following structure:
```
{firstName: ..., surname: ...}
``` 
to an array of objects that has the following structure:
```
{name: ...}
``` 
where the `name` property is the concatination of the `firstname` and `surname`.

4. We have the following HTML:
```
<div id="buttonContainer">
  <button id="save">Save</button>
  <button id="reset">Reset</button>
</div>
```
Write a **single** event listener for the `click` event that handles both the *save* and *reset* buttons. The event listener should simply output the button text to the console.

5. Using the native JavaScript DOM API, write code that adds a `span` element that contains text *Hello* to the bottom of the documents `body` tag. 

6. Write JavaScript code that uses the `fetch` function to `POST` a comment to a blog. The endpoint is `/api/blogs/{id}/comment`. We have the blog id in a numeric variable called `id` and the comment in a string variable called `comment`. The endpoint expects the request body to be in the following format: `{comment: ...}`

7. Use the spread syntax to copy a variable called `person` to a variable called `personSafe`. The format of the object is `{firstname: ..., surname: ..., age: ...}`

8. Using the native JavaScript DOM API, add a CSS class called "deleted" to all the elements that have the CSS class "selected"

9. The following code returns whether a customer is active or not. The function `getCustomer` calls a web service which retrieves the customer record from a database.
What is wrong with the implementation of the `getWhetherCustomerIsActive` function?
```
function getWhetherCustomerIsActive(id) {
  let isActive = false;
  getCustomer(id).then(customer => {
    isActive = customer.active;
  });
  return isActive;
}
```

10. What would be the output to the console when the following JavaScript is executed?
```
function createCounter() {
  let value = 0;
  function counter() {
    value = value + 1;
    return value;
  };
  return counter;
}

const counter = createCounter();
counter();
const whatsTheCount = counter();
console.log(whatsTheCount);
```

11. Refactor the following function to use the destructuring syntax on the parameter so that the return statement is `return (age * 2) + score;`
```
function calc(args) {
  return (args.age * 2) + args.score;
}
```

12. Implement a function called `multiplyNumbers` whose first parameter is a multiplier with variable number of other parameters that will be multiplied by the multiplier and output to the console.
So, `multiplyNumbers(2, 3)` will output `6` to the console and `multiplyNumbers(2, 3, 4)` will output `6` and `8` to the console.

13. Use the array `reduce` function to create a function called `avg` that returns the average value of an array of numbers.

14. Create an asychronous function called `wait` that simply waits the number of milliseconds passed into it before returning. Implement the function so that it supports the `async` / `await` syntax.

15. Create a generic asynchronous function called `getData` that uses `fetch` to `GET` data from a REST API. The function should accept a single parameter which is the URL for the request. An example call to the function is below:
```
const blog = await getData(`/api/blogs/${id}`);
```


   
🏆🏆🏆   

Send your answers to Carl to get your score and feedback. 



















