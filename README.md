

### Array Method Questions

Given arrays:

```javascript
const numbers = [5, 12, 8, 130, 44];
const fruits = ["apple", "banana", "cherry", "date", "elderberry"];
const mixedArray = [1, [2, 3], [4, [5, 6]], 7];
const ages = [3, 10, 18, 20, 33];
const colors = ["red", "green", "blue", "yellow"];
```

#### Questions

1. **Using `push()`**  
   - Add `"fig"` to the end of the `fruits` array. What does the updated array look like?

2. **Using `pop()`**  
   - Remove the last item from the `fruits` array. What item was removed, and what does the array look like now?

3. **Using `shift()` and `unshift()`**  
   - Use `shift()` to remove the first item from the `colors` array. Then, add `"purple"` to the start using `unshift()`. What is the final array?

4. **Using `map()`**  
   - Create a new array by doubling each value in the `numbers` array.

5. **Using `filter()`**  
   - Create a new array from `numbers` that includes only values greater than 10.

6. **Using `reduce()`**  
   - Use `reduce()` on `numbers` to find the total sum of all elements.

7. **Using `find()`**  
   - Find the first number in the `ages` array that is greater than or equal to 18.

8. **Using `findIndex()`**  
   - Get the index of the first even number in the `numbers` array.

9. **Using `includes()`**  
   - Check if `"cherry"` is present in the `fruits` array.

10. **Using `some()` and `every()`**  
    - Use `some()` to check if there are any ages greater than 30 in the `ages` array.
    - Use `every()` to check if all numbers in the `numbers` array are positive.

11. **Using `sort()`**  
    - Sort the `colors` array alphabetically. Then sort the `numbers` array in ascending order.

12. **Using `splice()`**  
    - Remove `"banana"` and `"cherry"` from the `fruits` array using `splice()`.

13. **Using `concat()`**  
    - Concatenate `fruits` and `colors` into a single array. What does the combined array look like?

14. **Using `slice()`**  
    - Extract the first two elements from `colors` without modifying the original array.

15. **Using `flat()`**  
    - Flatten `mixedArray` into a single-level array.

16. **Using `forEach()`**  
    - Log each element in the `fruits` array to the console.

17. **Using `join()`**  
    - Create a single string from the `colors` array, with each color separated by a hyphen (`-`).



#1. Array Of Object

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



###2. Array of Objects 

Given the following array:

```javascript
const students = [
  { id: 1, name: "Alice", age: 22, scores: { math: 85, english: 78 } },
  { id: 2, name: "Bob", age: 19, scores: { math: 92, english: 65 } },
  { id: 3, name: "Charlie", age: 23, scores: { math: 88, english: 80 } },
  { id: 4, name: "David", age: 21, scores: { math: 76, english: 95 } },
  { id: 5, name: "Eve", age: 20, scores: { math: 91, english: 83 } }
];
```

#### Questions

1. **Using `map()`**  
   - Create a new array containing only the names of each student.

2. **Using `filter()`**  
   - Filter out all students who are 21 years old or older.

3. **Using `reduce()`**  
   - Calculate the total of all math scores.

4. **Using `find()`**  
   - Find the first student whose English score is above 80.

5. **Using `some()` and `every()`**  
   - Check if any student is younger than 20.
   - Verify if every student has scored above 75 in math.

6. **Using `sort()`**  
   - Sort the `students` array in ascending order by age.

7. **Using `forEach()`**  
   - Log a sentence for each student, like "Alice is 22 years old."

---

### Challenges

1. **Average Math Score Challenge**  
   - Write a function to find the average math score for all students. What is the result?

2. **Top Scorer Challenge**  
   - Write a function to find the student with the highest math score.

3. **English Pass List**  
   - Create a list of student names who scored 80 or above in English.

4. **Age Grouping Challenge**  
   - Group the students into two categories: those who are under 21 and those who are 21 and older. Return an object with two arrays.

5. **Detailed Report Challenge**  
   - Write a function that returns a report on each student in the format:  
     ```javascript
     "Alice, age 22, scored 85 in math and 78 in English."
     ```

6. **Math Improvement Challenge**  
   - Suppose every student improves their math score by 5 points. Use `map()` to create a new array reflecting these improved scores.

7. **Create a Lookup Table**  
   - Create an object where each student’s `id` is a key, and the value is the student’s name. This can be useful for quickly looking up a student’s name by their `id`.

8. **Failed English Challenge**  
   - Write a function that returns the names of students who scored below 70 in English.

9. **Identify Unique Ages**  
   - Use a combination of methods to find all unique ages in the `students` array.

10. **Score Range Finder**  
    - Write a function that takes in a score range (e.g., min = 80, max = 90) and returns a list of students whose math scores fall within that range.


