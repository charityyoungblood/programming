1. What is a variable?

  - Variables are a way for us to store data; they are the memory locations which hold data to be used by any program
  - Professional definition: a variable is a storage location (identified by a memory address) paired with an associated symbolic name (an identifier), which contains some known or unknown quantity of information referred to as a value

2. Variable Naming 

  - lower cased letters
  - Snake Case is used to name variables in Ruby (i.e. make_music, i_love_shrimp)
  - A Ruby variable cannot start with a number, be a Ruby reserved word, or have punctuation or space characters.
  - if you are creating a variable without an initial value, set variable to nil (i.e. songs = nil)

3. Variables hold "types" of data. There are 6 data types in Ruby: 

  - Booleans: represents a return value of true or false
  - Symbols: these are used to represent other objects 
  - Integers and Floating Point Numbers: Fixnums (whole numbers) and Floats (decimals)
  - Strings: represents textual data; Strings are represented as a sequence of characters enclosed in double or single quotes
  - Arrays: ordered list of a collection of objects; array index starts at 0
  - Hashes: a dictionary-like collection of unique key:value pairs 
  
  ***REMEMBER: you can call the .class method on any object to see what data type it is***

4. Variables are assigned with a variable name and an assignment operator (the equal sign) (i.e. fashion_designer = "Christian Siriano")

5. To re-assign variables, just delete the origin variable value and insert new value

  - Ex: fashion_designer = "Christian Siriano"
        fashion_designer = "Aquazzura"
        return fashion_designer
  This will re-assign fashion_designer value and return Aquazzura