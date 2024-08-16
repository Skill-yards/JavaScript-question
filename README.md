# JavaScript-question

const users = [
  { id: 1, name: "Alice", email: "alice@example.com", age: 28, balance: 5000, isActive: true },
  { id: 2, name: "Bob", email: "bob@example.com", age: 34, balance: 3000, isActive: false },
  { id: 3, name: "Charlie", email: "charlie@example.com", age: 22, balance: 7000, isActive: true },
  { id: 4, name: "Diana", email: "diana@example.com", age: 29, balance: 4000, isActive: false },
  { id: 5, name: "Eve", email: "eve@example.com", age: 35, balance: 10000, isActive: true },
];


Questions
Find all active users:

Use the filter method to get a list of users who are active.

Use the reduce method to calculate the sum of the balance property for all users.
Find a user by email:

Use the find method to locate a user with the email "charlie@example.com".
Sort users by age:

Use the sort method to order users from youngest to oldest.
Increase each user's balance by 10%:

Use the map method to create a new array of users with their balance increased by 10%.
Check if any user is under 25:

Use the some method to check if there is at least one user whose age is less than 25.
Check if all users have a balance over 2000:

Use the every method to verify if all users have a balance greater than 2000.
Get a list of user names:

Use the map method to extract just the name property from each user into a new array.
Count users with a balance of at least 5000:

Use the filter method to find users with a balance of 5000 or more, then get the length of the resulting array.
Remove a user by ID:

Use the filter method to create a new array without the user whose id is 3.
