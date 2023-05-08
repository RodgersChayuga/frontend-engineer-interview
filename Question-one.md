# FRONTEND ENGINEERING ROLE - INTERVIEW QUESTIONS.

### Q1. Can you explain how the box model works in CSS?
### Q2. How do you optimize website performance?
### Q3. Can you describe how you would implement responsive design on a website?
### Q4. How do you handle cross-browser compatibility issues?
### Q5. Can you walk us through how you would build a responsive navigation menu using HTML, CSS, and JavaScript?
### Q6. Can you explain how you would debug an issue on a website?
### Q7. How do you ensure accessibility for users with disabilities on a website?
### Q8. Can you describe a time when you had to optimize a website for SEO?
### Q9. Can you walk us through your process for testing and debugging frontend code?
### Q10. Write a function that takes in an array of numbers and returns the sum of all the even numbers in the array.
### Q11. Write a function that takes in an array of numbers and returns the sum of all the even numbers in the array.
### Q12. Implement a function that takes in a string and returns the number of vowels in the string.
### Q13. Write a program that generates a multiplication table for a given number up to a specified limit. For example, if the input is 3 and 5, the output should be:

```Javascript
3 x 1 = 3
3 x 2 = 6
3 x 3 = 9
3 x 4 = 12
3 x 5 = 15

```
### Q14. Given an array of objects with `name` and `age` properties, write a function that returns the name of the oldest person in the array.
### Q15. Implement a function that takes in a string and reverses the order of the words in the string. For example, if the input is "hello world", the output should be >"world hello".
### Q16. Write a program that generates the first `n` Fibonacci numbers. The Fibonacci sequence is defined as follows: the first two numbers are 0 and 1, and each subsequent number is the sum of the previous two. For example, if the input is 
### Q17. the output should be:
```Javascript
0 1 1 2 3 5

```
### Q18. Given an array of strings, write a function that returns the longest string in the array.
### Q19. Implement a function that takes in a string and checks if it is a palindrome (i.e., reads the same forward and backward). For example, if the input is "racecar", the output should be true.
### Q20. Write a program that generates the first n prime numbers. A prime number is a number that is only divisible by 1 and itself. For example, if the input is 5, the output should be:

```Javascript
2 3 5 7 11

```
### Q21. Given two arrays of numbers of the same length, write a function that returns an array with the sum of the corresponding elements of the two arrays. For example, if the input is `[1, 2, 3]` and `[4, 5, 6]`, the output should be `[5, 7, 9]`.
### Q22. Write a function that takes in a nested object and flattens it into a single-level object. For example, if the input is:

```Javascript
{
  name: "John",
  age: 30,
  address: {
    street: "123 Main St",
    city: "Anytown",
    state: "CA",
    zip: "12345"
  },
  hobbies: ["reading", "running"],
  friends: [
    { name: "Jane", age: 28 },
    { name: "Bob", age: 35 }
  ]
}

```

The output should be:

```Javascript
{
  name: "John",
  age: 30,
  "address.street": "123 Main St",
  "address.city": "Anytown",
  "address.state": "CA",
  "address.zip": "12345",
  hobbies: ["reading", "running"],
  "friends.0.name": "Jane",
  "friends.0.age": 28,
  "friends.1.name": "Bob",
  "friends.1.age": 35
}

```

Note that the keys of nested objects and arrays are concatenated with a dot (.) separator in the output object.
### Q23. Explain the differences between CSS Grid and Flexbox. When would you use one over the other?
### Q24. How do you optimize the performance of a web application? Discuss different techniques you've used in the past.
### Q25. Explain the event loop in JavaScript. How does it work and why is it important?
### Q26. What are some of the advantages and disadvantages of using a JavaScript framework like React or Angular? When would you choose to use a framework versus vanilla JavaScript? 
### Q27. Explain how you would implement server-side rendering (SSR) in a web application. What are some benefits of using SSR?
### Q28. What is your process for debugging complex issues in a web application? How do you go about finding and fixing the issue?
### Q29. Discuss different strategies for managing state in a complex web application. When would you use a state management library like Redux or MobX?
### Q30. Describe your experience with accessibility (a11y) in web development. What are some best practices for creating accessible websites?
### Q31. Explain how you would optimize a web application for SEO. What are some key factors to consider?
### Q32. Discuss your experience with testing in frontend development. What are some best practices
### Q33. Given a binary tree, write a function that prints the nodes in breadth-first search (BFS) order. For example, if the input tree is:

```Javascript
      1
    /   \
   2     3
  / \   / \
 4   5 6   7
```

The output should be: `1 2 3 4 5 6 7`

### Q34. Given a graph represented as an adjacency list, write a function that prints the nodes in depth-first search (DFS) order. For example, if the input graph is:

```Javascript
{
  1: [2, 3],
  2: [4],
  3: [4, 5],
  4: [6],
  5: [],
  6: []
}

```

The output should be: `1 2 4 6 3 5`

Note that in this example, there are multiple valid DFS orders, as there are multiple nodes with the same depth.
