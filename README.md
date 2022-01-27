
# Time Complexity 
As data grows is important to also know the best algorithm.
Time complexity is a measure of the time required to run an algorithm as the input increases.


## Scalability
- Execution and memory usage as the input size increases. 

## Big O Notation: Excution time and memory usage

- Constant Time O(1)
------------
Same running time regardless of size in input. 
As input data increases the amount of time the algorithm take does not change. 




```swift
  func checkFirst(names: [String]) {
     if let first = names.first {
      print(first)
      } else {
      print("no names")
     }
  }
```
 - The size of the  names array has no eefect on the running time of this function. 
 - weather the input has ten items or 10 million items , this function only checks the first element of the array 
