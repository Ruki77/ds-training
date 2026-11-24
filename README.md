# ds-training

A collection of Java data-structures and algorithms exercises from a June training session. Each file focuses on one problem and uses its own class.

## Navigate the exercises

Open `DSA(6th-13th June)_25/`. The `searching` folder includes search-insert position, and `two pointers` includes merging sorted arrays and removing elements.

## Running an exercise

Open the desired Java file in a JDK-enabled IDE. Run a class with a `main` method directly. For solution-only classes such as `problem88`, call the solution method from a small driver with sample arrays.

`problem35.java` needs a correction before it compiles: its static `main` calls the instance method `searchInsert` without creating an instance.
