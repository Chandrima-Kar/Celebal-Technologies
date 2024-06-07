# Week 3 assignment:
## **Refactor an existing piece of code that uses callbacks for async operations to use Promises and Async/Await for better readability and error handling.**

#### In this example:
### Callback version(:
We have a callback version where:
1. Each asynchronous function accepts a callback function as an argument to handle the results or errors.
2. The callback hell pattern is evident, where each function call is nested within the callback of the previous function, making the code harder to read and maintain.
3.We also have a handleError function to handle errors in a centralized way.

#### functions used:
a) fetchUserData that simulates fetching user data from an API.
b) processUserData simulates processing the fetched user data.
c) fetchProcessAndDisplayUserData that combines these operations.
d) fetchProcessAndDisplayUserData to run the entire process.

### Refactoring it to use Promises and Async/Await.
