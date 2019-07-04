# Basic JavaScript Quiz

The following questions should take you no longer than 1 hour to answer.  

1. What are the primative types in JavaScript?

2. Will the following JavaScript cause a runtime error? If so, how can this be resoved?
```
const name = "";
// sometime later
name = "fred";
```

3.  Will the following JavaScript cause a runtime error? If so, how can this be resoved?
```
const person = {};
person.name = "fred";
```

4. What will the value of `cool` be after the following JavaScript is executed?
```
let cool = false;
const person = {
  name: "fred",
  age: 40
};
if (person.name === "fred" && person.age > 40) {
  cool = true;
}
```

5. Rewrite the following function as an arrow function:
```
function logIt(message) {
  console.log(message);
}
``` 

6. Is it possible to define a string value that spans multiple lines? For example how can a variable be set to the following value?
```
A very very very very
long piece of text
```

7. What is wrong with the following class definition? What can be done to resolve this problem?
```
class Person {
  constructor(firstname, surname) {
    this.firstname = firstname;
    this.surname = surname;
  }
  sayHello() {
    return `Hello ${firstname} ${surname}`
  }
}
```

8. Is it possible to give the `message` parameter a default value of `"It's completed!"` if the parameter is omitted? If so, how?
```
function logCompleted(message) {
  console.log(message);
}
```

9. Rewrite the following function with an implicit return statement
```
const sum = (num1, num2) => {
  return num1 + num2;
}
```

10. Write a function called `firstOrNull` that returns the first element of an array or `null` if the array is empty

11. Write a function called `logArray` that outputs each element separately to the console 

12. Implement a function that outputs "*I'm still here*" every 5 seconds.

13. Rewrite the following function as an arrow function with an implicit return statement with the `if` statements replaced with a ternary expression:
```
function getLevel(score, age) {
  if (score > 8) {
    return "A";
  }
  if (age < 10) {
    return "A";
  } else {
    return "B";
  }
}
```

14. We have some array utility functions in a `array-utils.js` file. The file contains a `firstOrNull` exported function. How would we import this function into a different javascript file in the same folder?

15. Carrying on from the previous question, when we import `firstOrNull` how can we reference it as just `first` in the file that uses the function?

   
🏆🏆🏆   

Send your answers to Carl to get your score and feedback. 



















