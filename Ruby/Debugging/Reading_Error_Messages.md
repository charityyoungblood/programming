Error messages have 3 parts:

    Example error message:

      lib/a_name_error.rb:3:in `<main>': undefined local variable or method `hello_world' for main:Object (NameError)

1) The location of the error, the "where".

    lib/a_name_error.rb:3:in `<main>':
    
      - lib/a_name_error.rb is the file the error occurred in.
      - 3 is the line of code with the error.
      - <main> is the scope of the error.
      
2) The description, the "why".

    undefined local variable or method `hello_world' for main:Object

      - The interpreter does the best job it can to tell you what it thinks went wrong.

3) The type of error, the "who".

    (NameError) - This is a Ruby Error Type.

    You've solved games of Clue with less information. This is one of the best parts of programming: debugging and fixing errors. It's like you're a detective solving a crime. The only bad thing is that more often than not, you're also the criminal that caused the error in the first place.

    Errors are clues, and reading them is the interpreter telling you what to do to fix the program and move on.
    
There are four common error types in Ruby:

1. NameErrors - caused when a method or variable name is invalid or undefined
2. Syntax Errors - occurs from incorrect syntax (adding a semicolon, missing and end keyword, etc.)
3. Type Errors - trying to operate on data of different types will result in this error (i.e. adding 1 + "1")
4. Division Errors - caused when a given number is divided by 0 

