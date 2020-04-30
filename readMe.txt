PROGRAM OVERVIEW
My program will compare 5 sorting algorithms: selection sort, insertion sort, heapsort,
merge sort, and quicksort. The program will be sorting words/strings by lexicographic order.
For each algorithm, the program will count the number of comparisons taken, and record time
spent in milliseconds for each sorting algorithm. Only direct comparisons among words are to be
counted.


INPUT:
The input format of this program is that the first line will be an integer indicating the number
of words to be sorted. Then, beginning from the second line, words are listed, and each line only
contains one word


CLASS BREAKDOWN
Project5.java:
This is the entrance to the program. All classes containing sorting algorithms get called from this
class. The Project5.java class also handles the timing of runtime of each individual algorithm.
All outputs are handled in this class.

SelectionSort.java:
The SelectionSort.java class implements Selection Sort on a string array. Selection Sort runs in O(n^2) time.
It contains the selectionSort Method and the swap method. SelectionSort handles comparisons and swap handles
the movement within the array.

InsertionSort.java:
The InsertionSort.java class implements Insertion Sort on a string array. Insertion Sort runs in O(n^2) time.
InsertionSort includes the insertionSort method. This method handles the comparisons and relabeling of items in array.


MergeSort.java:
The MergeSort.java class implements Merge Sort on a string array. Merge Sort runs in O(n log n ) time.
MergeSort includes the merge and mergeSort methods. MergeSort is a recursive method which itself, and once
sorting is completed it is merged with the merge method.

QuickSort.java:
The QuickSort.java class implements Quick Sort on a string array. Quick Sort runs in O(n log n) time.
QuickSort includes the sorting method and the swap method. The sorting method does the comparisons between
elements, and swap does the changing of positions.

HeapSort.java:
The HeapSort.java class implements Heap Sort on a string array. Heap Sort runs in O(n log n ) time.
HeapSort includes the heapSort method, build Heap and heapForm. This is also a comparison based
algorithm.

