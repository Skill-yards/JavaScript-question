# Array Methods Practice

This repository provides practice questions to help users become familiar with JavaScript array methods. The exercises are based on an array of user account objects, each representing a user with properties such as `id`, `name`, `email`, `age`, `balance`, and `isActive`.

## Sample Data

Here is the sample data you will use for the exercises:

```javascript
const users = [
  { id: 1, name: "Alice", email: "alice@example.com", age: 28, balance: 5000, isActive: true },
  { id: 2, name: "Bob", email: "bob@example.com", age: 34, balance: 3000, isActive: false },
  { id: 3, name: "Charlie", email: "charlie@example.com", age: 22, balance: 7000, isActive: true },
  { id: 4, name: "Diana", email: "diana@example.com", age: 29, balance: 4000, isActive: false },
  { id: 5, name: "Eve", email: "eve@example.com", age: 35, balance: 10000, isActive: true },
];

```

## Questions

1. **Find all active users:**
   - Use the `filter` method to get a list of users whose `isActive` property is `true`.

2. **Get the total balance of all users:**
   - Use the `reduce` method to calculate the sum of the `balance` property for all users.

3. **Find a user by email (`"charlie@example.com"`):**
   - Use the `find` method to locate a user with the email `"charlie@example.com"`.

4. **Sort users by age:**
   - Use the `sort` method to order users from youngest to oldest.

5. **Increase each user's balance by 10%:**
   - Use the `map` method to create a new array of users with their `balance` increased by 10%.

6. **Check if any user is under 25:**
   - Use the `some` method to check if there is at least one user whose `age` is less than 25.

7. **Check if all users have a balance over 2000:**
   - Use the `every` method to verify if all users have a `balance` greater than 2000.

8. **Get a list of user names:**
   - Use the `map` method to extract just the `name` property from each user into a new array.

9. **Count users with a balance of at least 5000:**
   - Use the `filter` method to find users with a balance of 5000 or more, then get the length of the resulting array.

10. **Remove a user by ID (`3`):**
    - Use the `filter` method to create a new array without the user whose `id` is `3`.

Feel free to modify and extend this README with additional exercises or details as needed. Happy coding!
```

This version includes only the questions, making it a good starting point for users to practice their skills with JavaScript array methods. Let me know if there's anything else you'd like to add or change!
