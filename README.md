# Exp-09 Write a program to add, retrieve and remove the element from the ArrayList.
# program
```
import java.util.ArrayList;

public class ArrayListOperations {
    public static void main(String[] args) {
        ArrayList<Integer> arrayList = new ArrayList<>();

        arrayList.add(10);
        arrayList.add(20);
        arrayList.add(30);
        arrayList.add(40);

        System.out.println("ArrayList: " + arrayList);

        int elementToRetrieve = arrayList.get(1);
        System.out.println("Retrieved element at index 1: " + elementToRetrieve);

        arrayList.remove(2);
        System.out.println("ArrayList after removing element at index 2: " + arrayList);
    }
}
```
# output
![image](https://github.com/Rohith-AIDS/add_retrive_ARRAY/assets/94980736/3a3bf479-1326-4eaa-893e-a24dbac8b9ac)
