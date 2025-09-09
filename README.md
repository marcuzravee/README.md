# ReverseApp

## Compilation & Run
javac StackX.java Reverser.java ReverseApp.java
java ReverseApp

Features
- Reverse entire string
- Reverse each word in place
- Palindrome checker (ignores case, spaces, punctuation)
- Balanced brackets validator

Enhancements Implemented
- CLI Menu
- Palindrome checker with cleanup (ignores spaces/punctuation)

Sample I/O

csharp

Enter string: racecar
Palindrome? true

Enter string: [()]{}{[]}
Brackets are balanced.


Enter string: [()]{}{[]}
Brackets are balanced.

Time & Space Complexity
- Reverse: O(n) time, O(n) space (stack + output)
- Reverse words: O(n) time, O(n) space
- Palindrome: O(n) time, O(n) space
- Brackets validator: O(n) time, O(n) space
