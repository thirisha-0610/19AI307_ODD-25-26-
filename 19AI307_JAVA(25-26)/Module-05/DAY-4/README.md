# Ex.No:5(D) THREAD PRIORITY

## QUESTION:
Write a java program for determine the priority and name of the current thread.

Note : Read the threadname from the User

## AIM:

To read a thread name from the user and display the current thread’s name and priority.
## ALGORITHM :
1.Read the thread name from the user.
2.Get the reference of the current thread using Thread.currentThread().
3.Set the name of the current thread using setName().
4.Retrieve the thread’s name and priority using getName() and getPriority().
5.Display both values.





## PROGRAM:
 ```
/*
Program to implement a Thread Priority Concept using Java
Developed by: THIRISHA A
RegisterNumber: 212223040228
*/
```

## SOURCE CODE:


```
import java.util.Scanner;

public class ThreadInfoExample {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Read thread name from user
        String threadName = scanner.nextLine();

        // Create a thread with the given name
        Thread t = new Thread(() -> {
            // Thread work can go here if needed
        }, threadName);

        // Display priority and name
        System.out.println("Priority of Thread: " + t.getPriority());
        System.out.println("Name of Thread: " + t.getName());

        // Display full thread info (toString())
        System.out.println(t);

        scanner.close();
    }
}
```




## OUTPUT:

<img width="1313" height="265" alt="512472093-f363db08-7cdb-4761-a39c-556870905f3c" src="https://github.com/user-attachments/assets/329562be-451c-4bdc-a04d-36b90ec058ca" />


## RESULT:
The program successfully reads the thread name from the user and displays the current thread’s name and priority.
