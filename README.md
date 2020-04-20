# java-basics-hw07

This is a homework for the Java Loops

## IntelliJ IDEA project configuration
1. Clone this project to your local environment

    ```git clone https://github.com/kermek/java-basics-hw07.git``` 
2. Import in IntelliJ IDEA using `File -> New -> Project from Existing Sources...`.
3. Select the directory that you cloned to.
4. Go through the `Import Project` wizard by clicking `Next`.
5. On `Please select project SDK` point it to your Java 1.8 JDK.
6. Press `Ctrl+Alt+Shift+S` and check that in your `Project Structure`.
    value of `Project language level` is set to `8 - Lambdas, type annotations et.`.
7. Open test class, put your cursor on `@Test` annotation, press `Alt+Enter` 
    and choose `Add 'testng' to classpath`.  
8. Set the value to `org.testng:testng:6.14.3` and mark checkbox `Download to`.
9. Complete all TODO tasks in the SumAverage class.
10. Execute tests. 
11. Add 2 more tests for each method by adding more test data.

## SumAverage assignment

Implement methods in the SumAverage class.
Arguments: lower bound, upper bound, and numbers array are valid integers.
Lower bound is always less than or equals to upper bound.
All test should pass.
Add 2 more tests for each method by adding more test data.

## Unit testing
There are number of different ways to run your unit tests, e.g.:
* In test class put your cursor on its definition, right click and choose `Run ...`
* Right click on a little green triangle near the class definition and choose `Run ...`
* In test class put your cursor on its definition and press `Ctrl+Shift+F10`
* Once you executed your test you could re-run it again by pressing `Shift+F10`
