# Algorithms

- its good practice to get into being able to visualize the problem, discuss it witht eh boxes and arrows and then program it.


## **<u>Linear Search</u>** 

this is searching throught he index, for example using the ```indexOf``` method. 


simplist example of this is the needle in the haystack example, 


```typescript 

function linearSearch(haystack: number, needle: number): boolean {

    for (let i = 0; i < haystack.length; i++) {
        if (haystack[i] === needle) {
            return true
        }
    }
        return false
}
```
the complexity for this is O(N) btw


## **<u>Binary Search</u>**

this is a bit of a doosy, but its definently a basis for other algorithms we'll encounter 

## Always ask yourself is it Ordered? 

how can we search this array? 
