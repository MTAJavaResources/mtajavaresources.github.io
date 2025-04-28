# Array Lists
Array Lists are an import from `java.util`. The best way to setup the import is as so:
```Java
import java.util.*;
//imports all librarys of java.util
public class ArrayListNotes{
  public static void main(String[] args){
    ArrayList<{DataType}> MyArray = new ArrayList<>();
  }//main
}//class ArrayListNotes
```
## Wrappers
Array Lists don't use primatives-- instead they used Wrappers. Wrappers are a bit different, in the way they have a different way of decleration.
### Wrappers Names
| primative | Wrapper |
|-----------|---------|
| int       | Integer |
| double    | Double  |
| byte      | Byte    |
| boolean   | Boolean |
Strings weren't primative to begin with, so there is no change in their names.

### Declaring a Wrapper
You declare a wrapper as so:
`Double myDouble = new Double(1.00);

## Methods
All without a . before hand you would put `{ArrayName}.` before.
### Size
`size()`
Gets the length of the array list.
### Add
`add(value)`
Adds a value to a list.
`add(value, index)`
Inserts a value at a spesific index.
### Get
`get(index)`
Returns a value from an index.
### Remove
`remove(value)`
Remove the first occurance of a value.
`remove(index)`
Removes an item at a spesific index.
### Contains
`contains(value)`
Returns true or false if a list contains a value.
### Index Of
`indexOf(value)`
Returns a value at a spesific index.
### Clear
`clear()`
Removes everything from an array list.
### Add All
`addAll()`
Adds everything from a seperate array list to the bottom.
### Sort
`Collections.sort(array)`
Sorts the list and changes the list to be sorted.
