## A1 | Importing
You can import all from java.util by writing `import java.util.*;`.

## A2 | Initialization
### Steps
1. Import
2. Create stub
3. Initialize array list
4. for loop
5. print names

### Code
```
import java.util.*;
public class ArrayListsA2{
  public static void main(String[] args){
    ArrayList<> namesJ = new ArrayList<>(String);
    namesJ.add("John");
    namesJ.add("Jay");
    //add the rest here
    for(String content : namesJ){
      System.out.println(current);
    }
  }
}
```
## A3 | Non-Primative
`String` does not have a primative.

## A4 | Methods
1. `size()` gets the length/len of the Array List.
2. `remove(value)` removes the first instance of the given value, while `remove(index)` removes a spesific index.
3. `contains()`

## A5 | Write Code
```
import java.util.ArrayList;
import java.util.List;

public class CountByFives {
    public static void main(String[] args) {
        // Create a list of numbers
        List<Integer> numbers = new ArrayList<>();
        
        // Add numbers counting by fives up to 50
        for (int i = 5; i <= 50; i += 5) {
            numbers.add(i);
        }
        
        // Print all numbers that end with 5
        for (int number : numbers) {
            if (number % 10 == 5) {
                System.out.println(number);
            }
        }
    }
}
```
***
mtajavaresources.github.io is licensed with the [MIT License](/LICENSE).

[< Back to Answers](/exercises/answers)
