# Week 3 assignment:
## **Refactor an existing piece of code that uses callbacks for async operations to use Promises and Async/Await for better readability and error handling.**

#### In this example:
### Callback version(functionUsingCallback.js):
**You can run the code in the terminal using 'node functionUsingCallback.js'**

We have a callback version where:
1. Each asynchronous function accepts a callback function as an argument to handle the results or errors.
2. The callback hell pattern is evident, where each function call is nested within the callback of the previous function, making the code harder to read and maintain.
3.We also have a handleError function to handle errors in a centralized way.

#### functions used:
a) fetchUserData that simulates fetching user data from an API.
b) processUserData simulates processing the fetched user data.
c) fetchProcessAndDisplayUserData that combines these operations.
d) fetchProcessAndDisplayUserData to run the entire process.



### Refactoring it to use Promises and Async/Await(refactored_code.js)
**You can run the code in the terminal using 'node refactored_code.js'**
In this we have refactored the code using promises and async/await

a)We have an asynchronous function fetchUserData that simulates fetching user data from an API.
b)Another asynchronous function processUserData simulates processing the fetched user data.
c)displayUserData displays the processed user data.
d)We have an async function fetchProcessAndDisplayUserData that combines these operations and executes them sequentially using await.
e)Finally, we call fetchProcessAndDisplayUserData to run the entire process.

When you run this code using Node.js, it will fetch user data, process it, display it, and then output a success message.
