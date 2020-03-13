# Week 3 - Data Types & Operators

## Data Types

* **Definition:** Classification of data that allows a compiler/ interpreter to determine how to store and process the data, and defines what the programmer can do with it.<br/><br/>
* **Primitive (ie. Basic) Data Types:**<br/><br/>
   * **int**
      * Whole numbers
      * `1`<br/><br/>
   * **float**
      * Numbers with decimals
      * `3.14159`<br/><br/>
   * **string**
      * A sequence of characters
      * `"High School Musical is a misunderstood franchise."`
      * Can be defined within single `''` or double quotes `""`
         * If you've defined your string using double quotes, and want to use double quotes within the string itself, you can escape it using the escape character `\`.<br/>
         `sentence = "In a state of utter frustration, Troy screamed, \"BASKETBALL, OR THEATRE???!!!\""`<br/>
         `# (Try running this on Grok!)`
         *  ↑ Vice versa for strings defined using single quotes
      *  Useful functions: `len()`, `isdigit()`, `isalnum()`, `isupper()`, `islower()`, `print()`, `input()`<br/><br/>
   * **bool**
      * A truth value
      * `True`, `False`<br/><br/>
## Operators
* **Definition**: A symbol placed between two values that calculates something and produces a result<br/><br/>
* **Types of Operators**:<br/><br/>
   * `+`
      * Used for: addition
      * Can be used with:
        * int `2 + 2 = 4`
        * float `4.0 - 3.0 = 1.0  #quick_maths`
        * string(concatenation) `"hello " + "world" = "hello world"`
        * bool  `True + True = 2`
      * If at least one of the data type of one of the values is a float, then the data type of the result will also be a float<br/><br/>
   * `-`
     * Used for: subtraction
     * Can be used with:
       * Same as addition, except for string<br/><br/>
   * **Note:** You can't mix strings and numeric types for addition and subtraction. Doing so will produce a `TypeError`.<br/><br/>
   * `*`
     * Used for: multiplication
     * Can be used with:
       * int `7 * 4 = 28`
       * float `12.0 * 4 = 48.0`
       * bool `True * False = 0`
     * If at least one of the data type of one of the values is a float, then the data type of the result will also be a float
     * You can also multiply strings by **int**s: `"ha" * 3 = "hahaha"`<br/><br/>
   * `/`
     * Used for: division
     * Can be used with:
       * int `4 / 2 = 2.0`
       * float `4.0 / 4.0 = 1.0`
     * The data type of the result with **always** be a float<br/><br/>
   * `%`
     * Used to: calculate modulus, ie. divide two numbers and return the remainder
     * Can be used with:
       * int `4 % 3 = 1`
       * float `4.0 % 3.0 = 1.0`
     * If at least one of the data type of one of the values is a float, then the data type of the result will also be a float<br/><br/>
   * `//`
     * Used to: divide two numbers and floor (ie. round down) the result
     * Can be used with:
       * int `5 // 3 = 1`
       * float `13.0 // 6.0 = 2.0`
     * If at least one of the data type of one of the values is a float, then the data type of the result will also be a float<br/><br/>
* **What does it mean for an operator to be overloaded?**<br />It means that the operator can work with multiple data types. Its behaviour varies between different data types (eg. With numeric types, `+` results in addition, but with strings, it results in concatentation)
