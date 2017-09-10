Dynamic Programming
String
2-dimension state： 1st for start pos of string, 2nd for end pos of string
state transfer: divide string into 2 substr, the result is the sum of the two substr
•	664. Strange Printer: don’t forget to treat empty substr(otherwise state array overflow for the length = 0)
state transfer: traverse substring from short to long, result is affected by the short substring
•	647. Palindromic Substrings

1-dimension state: the pos of the string
state transfer: the result is the sum/multiplication of a substr starting at the beginning
•	650. 2 Keys Keyboard
state transfer: current state relies on two previous states
•	639. Decode Ways II
•	


Array
1-dimension state: the pos of the array
state transfer: current state relies on all previous states
•	646. Maximum Length of Pair Chain: 1-dimension->3 elements, for the current state only depend on previous two states.
Map: 1st element is the array with the size of all dimension, 2nd element is the target value
•	638. Shopping Offers

