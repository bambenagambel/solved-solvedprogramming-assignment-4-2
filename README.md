Download Link: https://assignmentchef.com/product/solved-solvedprogramming-assignment-4-2
<br>
This assignment makes use of the files contained in this zip file.

This assignment is based on the material from Sections 5.2 and 5.3 from the course textbook.

You are to implement a generic Pair class. Your Pair class should be defined as Pair&lt;T1, T2 and it should contain two (private) instance fields called first (of type T1) and second (of type T2). Your Pair class should contain three constructors. There should be a default constructor that sets both fields to null. There should be a two item constructor that takes references to objects of type T1 and T2 and points the two instance fields at these two objects. And there should be a one item constructor that takes a reference to a Pair object of the same type as the one being constructed and points the instance fields of the item being constructed at the two objects contained in the given Pair object.

Your Pair class should contain appropriate getFirst(), setFirst(), getSecond() and setSecond() methods. The setFirst() and setSecond() methods should not be void methods, they should return a reference to the current object (so that other method calls can be chained).

There should be a method called transpose() that returns a reference to a new Pair object of type Pair&lt;T2,T1 where the objects in the new Pair are the same as the objects in the current pair, but in the opposite order.

Write a method called replaceFirst() that takes a single argument that is a reference to an object and returns a new Pair object where the first item in the new pair is the argument object and the second item in the new pair is the second item from the this object. This method will be a “generic method” (Section 5.2 of the textbook) in that it will need its own “local” type parameter (a type parameter different from the T1 and T2 type parameters at the beginning of the Pair class). Write a similarly defined replaceSecond() method.

Have your Pair&lt;T1,T2 class override the

public boolean equals(Object o)method from the Object class. Your version of equals() should return true when the argument o is not null and the argument o is a Pair object and the items in o are equal to the items in the this pair.

Your Pair class should also contain an appropriate toString() method.

In the zip file along with this file there is a program TestPairs.java that tests your implementation of the Pair class. Do not make any changes to the TestPairs.java file. The TestPairs.java program will compile correctly when you have completed your implementation of the Pair class. If the TestPairs.java program does not compile correctly, then you need to fix something in your implementation of Pair. When the TestPairs.java program runs, it should produce output like that contained in the file output.txt.

When you have finished implementing the Pair class, in a text file called Explanation.txt write an explanation of exactly what the statement on line number 32 from TestPairs.java does. In particular, explain how many objects are created by that line of code and what happens to each one. Also write an explanation of what the statement on lines numbered 36-37 does. Your two explanations should explain in detail what every part of each statement does.

Turn in a zip file called CS275Hw4Surname.zip (where Surname is your last name) containing your version of Pair.java and your text file Explanation.txt containing explanations of the two statements from TestPair.java.