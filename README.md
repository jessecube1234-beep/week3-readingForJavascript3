# week3-readingForJavascript3

## Questions

1. Why is dot notation generally preferred over bracket notation when accessing object properties in JavaScript?
   Because dot notation is cleaner, but doesn't work in all circumstances.
   
2. In what scenarios would you need to use bracket notation instead of dot notation to access a property in an object? Provide an example.
   When you are using variables or properties with spaces in it or numbers at the beginning.
```
Example: "console.log(user["first name"])"

```

3. What does the this keyword reference when used inside a method of an object in JavaScript? Provide an example.
   It refrences the object that owns the function or method being executed.
```
  let car = {
     brand = 'Honda';
     start = function() {
    // "this" is the car object
    console.log(this.brand + ' is starting.');
  }
};

car.start(); // Output: "Honda is starting."

```

4. How does the behavior of the this keyword differ when used in a function inside the global context compared to when it's used inside an object method?
   In the global context, the this references the global object, which is the window object on the web browser or global object on Node.js

5. Multiple choice: An object can contain a function which is called a a. Mini-function b. Method c. Sub-function d. Literal
   B

6. An object factory is a… a. Function that accepts an object as an argument b. For loop that loops exactly once c. Function that returns an object d. Conditional statement that is always true
   C
   
7. What index does an array begin at?
   It begins at index 0. 

8. What is one way to add an item to an array?
   By assigning a value to a new index
```
selectedColors[2] = 'green';
```

9. What property on the array object tells you how many items are in the array?
    The length property.

10. What is the difference between a parameter and an argument?
    Paramater: the name you put inside a function to hold a value
    Argument: the ACTUAL value you give the function when you call that function
