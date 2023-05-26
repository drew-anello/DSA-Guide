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

Binary Search there are only two possible states, either 0 | 1


Not really scanning anything more so looking at a value dividing in half, lookig at val dividing in half etc 


## **Psudo Code sense**

we have a function that has a search that takes in array it has a low and a high. This is the space we need to look into

we could do a loop where one condition happens which would be a comparison between a low and the high

## **This is under the assumption that the array is sorted btw**

we'll say midpoint = m 

to find m we'll use 




``` search(arr, lo, hi)n```

``` m = [lo + (hi - lo) / 2] ```

``` val = arr[m]```


```typescript if val = n 
return true 

else if val > n
    // adjust lo (m + 1)
else 
    hi = m
 do while (lo < hi) 
    return false
 ```  
