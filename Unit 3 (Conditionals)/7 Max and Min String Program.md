Write a program that reads in four strings and prints the lexicographic minimum and lexicographic maximum.  Hint:  Use the compareTo method from the string class to find the lexicographic max and min (alphabetical order)

 

compareTo()  Compares strings to determine alphabetic location.  Returns a zero if the two strings are equal, a negative if the first string is alphabetically before the compared string, and a positive if the first string is alphabetically after the compared string.
    Example:
   ```java
    String subject = "mathematics";
    boolean answer;
    answer = subject. compareTo ("biology"); // returns is a positive
    answer = subject. compareTo("philosophy"); // answer is negative
    answer = subject.compareTo (" mathematics"); //answer is zero
   ```

`StringComparerTest class`

    use Scanner to read the inputs from the console (not a file)
    to read the strings using Scanner, call the next method four times

Sample Output

Enter 4 strings: flower marble door garage

 

The lexicographic minimum is door

The lexicographic maximum is marble

