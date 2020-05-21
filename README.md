# Quick-MergeSort


## Class Setup
```
cmake CMakeLists.txt
make
```

To use merge sort:
```
./sort m rand-10k.txt
```
To use quick sort:
```
./sort q rand-10k.txt
```
To use selection sort:
```
./sort s rand-10k.txt
```
To use insertion sort:
```
./sort i rand-10k.txt
```
Note: can switch out different random text files with files that sort a descending listed file i.e. desc-10k.txt 

## About this project
An implementation of selection sort / insertion sort of a linked list with each node holding a key-value pair.  The project also uses these functions:
- add
- remove
- find
- range find
- keys (returns all keys by reference)
- sort (ascending order)
- size

Quick sort and merge sort are much more efficient sorting algorithms relative to selection sort and insertion sort with a random list of objects. However, for a list of objects in descending order that need to be in an ascending order, merge sort has a clear advantage over the other three.

Results:
<img width="626" alt="Screen Shot 2020-05-20 at 6 13 42 PM" src="https://user-images.githubusercontent.com/56742122/82512687-a672d600-9ac5-11ea-9ed3-a575dec04508.png">

<img width="450" alt="Screen Shot 2020-05-20 at 5 25 30 PM" src="https://user-images.githubusercontent.com/56742122/82510280-074ae000-9abf-11ea-8453-8ffa63e5c6ce.png">




Note: Need to have Cmake installed
