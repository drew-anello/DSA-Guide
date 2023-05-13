# Data Structures and Algorithim's 

I've had my fair share of failures in coding interviews, so I've put together a cheat sheet guide on Data Structures and Algorithms. I hope this resource will help you out and inspire you to dive deeper into this subject! There are plenty of excellent **FREE** courses available on DSA, and one that I've been particularly enjoying is [this one](https://frontendmasters.com/courses/algorithms/).


# What is Big O

Big O notation is a way to analyze and describe the efficiency or complexity of an algorithm. It helps us understand how the runtime of an algorithm or the amount of resources it requires (such as time or space) grows as the input size increases.

In Big O notation, we express the complexity of an algorithm using a mathematical expression. The expression describes the upper bound or worst-case scenario of how the algorithm's performance scales with the input size.

For example, if an algorithm has a runtime of O(n), it means that as the input size grows, the runtime of the algorithm also grows linearly. If the input size doubles, the runtime will approximately double as well.

There are different types of Big O notations, such as O(1) (constant time), O(log n) (logarithmic time), O(n) (linear time), O(n^2) (quadratic time), and many more. These notations help us compare and analyze different algorithms to determine which one is more efficient for a given problem.

In summary, Big O notation provides a standardized way to express and compare the efficiency of algorithms, allowing us to make informed decisions about algorithm selection based on the expected growth rate of resources required.

## <u>**Okay so I'm still confused... can you explain in the simpliest way possible?**</u>

Sure!  Imagine you have a box of toys. Big O is like a way to describe how long it takes to find a specific toy in that box.

Let's say you have 10 toys in the box, and you want to find a toy called "Teddy Bear." You start by looking at the first toy. If it's not the Teddy Bear, you move on to the second toy, and so on, until you find it. This is called searching sequentially, or in computer science terms, O(n), where "n" is the number of toys.

Now, imagine you have 100 toys in the box. It might take a little longer to find the Teddy Bear because you have more toys to look through. However, if you're clever, you might use a better strategy, like dividing the toys into groups and narrowing down the search. This is called a binary search, and it is faster. In computer science terms, we call it O(log n), where "log n" means the logarithm of the number of toys.

So, Big O helps us understand how the time it takes to do something grows as the number of things we're dealing with gets bigger. We can use different strategies to make the process faster and more efficient. And that's Big O in a nutshell

