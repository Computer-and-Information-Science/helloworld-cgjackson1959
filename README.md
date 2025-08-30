[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/KfWXY3c0)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=20158905)
Change the code so that instead of saying "Hello World" it says "Hello Object Oriented Programming", and then compile and test. 
Result: Hello Object Oriented Programming
Additionally try these out and see what errors you get. Document your errors here in the readme. (This is taken from Exercise 3 in the text book).

Starting with the Hello World program, try out each of the following errors. After you make each change, compile the program, read the error message (if there is one), and then fix the error.

Remove one of the opening curly braces.
Problems: Syntax error on token ')", (expected after this token Java(1610612967) [Ln 2, Col 42]
Error Message: HelloWorld 
Exception in thread "main" java.lang.Error: Unresolved compilation problem: 
        Syntax error on token ")", { expected after this token

        at HelloWorld.main(HelloWorld.java:2)

Remove one of the closing curly braces.
Problems: Syntax error, insert ")" to complete ClassBody Java(1610612976) [Ln 4, Col 5]
Error Message: HelloWorld 
Exception in thread "main" java.lang.Error: Unresolved compilation problem: 
        Syntax error, insert "}" to complete ClassBody

        at HelloWorld.main(HelloWorld.java:4)
Instead of main, write mian.
Error Message: HelloWorld 
Error: Main method not found in class HelloWorld, please define the main method as:
   public static void main(String[] args)
or a JavaFX application class must extend javafx.application.Application

Remove the word static.
Error: Main method is not static in class HelloWorld, please define the main method as:
   public static void main(String[] args)

Remove the word System.
Problems: Syntax error on token ".", delete this totken Java(1610612968) [Ln 3, Col 9]
          out cannot be resolved Java(570425394) [Ln 3, Col 10]
Error Message: HelloWorld 
Exception in thread "main" java.lang.Error: Unresolved compilation problems: 
        Syntax error on token ".", delete this token
        out cannot be resolved

        at HelloWorld.main(HelloWorld.java:3)

Replace println with Println.
Problems: Constructor call must be the first statement in a constructor Java(1207959691) [Ln 3, Col 9]
          println cannot be resolved or is not a field Java(33554502) [Ln 3, Col 20]
          Syntax error on token ".", super expected after this token Java(1610612967) [Ln 3, Col 27]
Error Message: HelloWorld 
Exception in thread "main" java.lang.Error: Unresolved compilation problems: 
        Constructor call must be the first statement in a constructor
        println cannot be resolved or is not a field
        Syntax error on token ".", super expected after this token

        at HelloWorld.main(HelloWorld.java:3)

Replace println with print.
Problems: Constructor call must be the first statement in a constructor Java(1207959691) [Ln 3, Col 9]
          print cannot be resolved or is not a field Java(33554502) [Ln 3, Col 20]
          Syntax error on token ".", super expected after this token Java(1610612967) [Ln 3, Col 27]
Error Message: HelloWorld 
Exception in thread "main" java.lang.Error: Unresolved compilation problems: 
        Constructor call must be the first statement in a constructor
        print cannot be resolved or is not a field
        Syntax error on token ".", super expected after this token

        at HelloWorld.main(HelloWorld.java:3)

Delete one parenthesis.
Syntax error, insert ")" to complete Expression Java(1610612976) [Ln 3, Col 28]
Error Message: HelloWorld Exception in thread "main" java.lang.Error: Unresolved compilation problem: 
        Syntax error, insert ")" to complete Expression

        at HelloWorld.main(HelloWorld.java:3)

Add an extra parenthesis.
Problems: Syntax error, insert ")" to complete ClassBody Java(1610612976) [Ln 1, Col 25]
          Syntax error on token ")", { expected Java(1610612940) [Ln 2, Col 43]
Error Message: HelloWorld 
Exception in thread "main" java.lang.Error: Unresolved compilation problem: 
        Syntax error on token ")", { expected

        at HelloWorld.main(HelloWorld.java:2)

Fix the code so it works and commit your changes.
Result: HelloWorld 
Hello Object Oriented Programming

Had trouble in Brightspace saying this is not completed.
I am trying to Commit it again.