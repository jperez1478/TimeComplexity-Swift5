
# Time Complexity 
As data grows is important to also know the best algorithm.
Time complexity is a measure of the time required to run an algorithm as the input increases.


## Big O Notation: Excution time and memory usage
## Scalability
- Execution and memory usage as the input size increases. 


# Constant Time O(1)
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


--------
# Linear Time Complexity O(N)

```swift
  func checkFirst(names: [String]) {
     for name in names {
      print(name)
     }
  }
```
- function checkfirst will print out the names in String array. As the input array increases in size
- number of iterations that the for loop makes increases by the same amount 


Conclusion  Big O(N)  in linear time is something that can cause lower algorithms causing to miss constant that may be repaeated in O(2n+6) having two for lopps 
