# Homework assignment

Before we conclude today's lecture, let's discuss the homework assignment for the week. This assignment is designed to give you hands-on experience with Sets and Maps in Java, allowing you to apply the advanced concepts and best practices we've covered. The assignment is divided into two parts.

## Part 1: Working with Sets

### Objective:

Create a Java program that simulates a simple tagging system for a blogging platform.

1. Each blog post can have multiple tags.
2. A tag can be associated with multiple blog posts.

### Requirements:

1. Use a `HashSet` to store tags for each blog post.
2. Use another `HashSet` to store all unique tags across all posts.
3. Implement functionality to add and remove tags from posts.
4. Implement functionality to display all posts associated with a specific tag.

### Bonus:

1. Implement a feature that suggests similar tags. For instance, if there are tags "Java" and "Java8", and a new post is tagged with "Java", the system should suggest "Java8" as a similar tag.

## Part 2: Working with Maps

### Objective:

Create a Java program that simulates a simple inventory management system.

1. The system should keep track of products and their quantities.
2. Implement features to add, remove, and modify products.

### Requirements:

1. Use a `HashMap` where the key is the product name (String) and the value is the quantity (Integer).
2. Implement methods to add new products to the inventory, remove products, and update quantities.
3. Implement a feature to display the current inventory sorted by product name. For this, you may use a `TreeMap`.

### Bonus:

1. Implement a feature to display products that are low in stock (quantity < 5) to alert the inventory manager.

---

This assignment aims to deepen your understanding of Sets and Maps while giving you practical experience in using them for common scenarios. You have one week to complete this assignment. Please submit your code through GitHub Classroom as usual.
