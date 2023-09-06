# Bubble Sort

Bubble sort is going trough the array, and finding finding if the number is smaller or larger, if the number is larger swap places.

Starting in the 0th position.

largest item at the last spot,

bubble sort is composed of two loops an inner and outer loop,

The outer loop will start like

```typescript
for (let i = 0; i < array.length; i++) {
```

This outer for loop iterates through the array. The variable i starts at 0 and goes up to the length of the array minus 1. This loop ensures that the sorting process is repeated enough times to fully sort the array.

the inner loop will look like

```typescript
for (let j = 0; j < array.length - 1 - i; j ++) {
```

This inner for loop also iterates through the array but stops earlier with each pass of the outer loop (array.length - 1 - i). This is because with each pass of the outer loop, the largest unsorted element "bubbles up" to its correct position, so we don't need to check it again.

an if statement after the inner loop

```typescript
if (array[j + 1] < array[j]) {
```

This if statement checks if the current element (array[j]) is greater than the next element (array[j + 1]). If it is, then they are out of order and need to be swapped.

```typescript
const tmp = array[j];
```

This line stores the value of the current element (array[j]) in a temporary variable named tmp.

```typescript
array[j] = array[j + 1];
```

This line sets the value of the current element (array[j]) to the value of the next element (array[j + 1]), effectively moving the smaller value to the left.

```typescript
array[j + 1] = tmp;
```

This line sets the value of the next element (array[j + 1]) to the value stored in tmp, effectively moving the larger value to the right.

````typescript
return array```
````

return sorted array at the end.
