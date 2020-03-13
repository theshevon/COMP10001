# Week 3 Notes

## Data Types

* **Definition:** Classification of data that allows a compiler/ interpreter to determine how to store and process the data, and defines what the programmer can do with it.
<br />
* **Primitive (ie. Basic) Data Types:**
   * **int**
      * Whole numbers, _eg. 1_
   * **float**
      * Numbers with decimals, _eg. 3.14159_
   * **string**
      * A sequence of characters, _eg. "High School Musical is a misunderstood franchise."_
      * Can be defined within single('') or double quotes("")
         * If you've defined your string using double quotes, and want to use double quotes within the string itself, ensure that you use the escape(\\) character.<br/> _eg. <br />sentence = "In a state of utter frustration, Troy screamed, \\"BASKETBALL, OR THEATRE???!!!\\""_ <br />(Try running this on Grok!)
         *  ↑ Vice versa for strings defined using single quotes
      *  Useful functions: len(), isdigit(), isalnum(), isupper(), islower(), print(), input()
   * **bool** _eg. True, False_
<br />
## Operators
* **Definition**: A symbol placed between two values that calculates some results
<br />
* **What does it mean for an operator to be overloaded?**<br />_The operator can work with multiple data types. Its behaviour varies between different data types._
<br />
* **Types of Operators**:
   <br />
   * **\+**
      * Used for: addition
      * Can be used with:
        * int _eg. 2 + 2 = 4_
        * float _eg. 4.0 - 3.0 = 1  #quick_maths_ #sorry_not_sorry,
        * string(concatenation) _eg. "hello " + "world" = "hello world"
        * bool _eg. True + True = 2_
   <br />
   * **\-**
     * Used for: subtraction
     * Can be used with:
       * Same as addition, except for string
   <br />
   * **\\**
     * Used for: division
     * Can be used with:
       * int _eg. 4 / 2 = 2.0_
       * float _eg. 4.0 / 4.0 = 1.0_
     * The data type of the result with *always* be a float
   <br />
   * **%**
     * Used to: calculate modulus, ie. divide two numbers and return the remainder
     * Can be used with:
       * int _eg. 4 % 3 = 1_
       * float _eg. 4.0 % 3.0 = 1.0_
     * If at least one of the data type of one of the values is a float, then the data type of the result will also be a float
   <br />
   * **\\\\**
     * Used to: divide two numbers and floor (ie. round down) the result)
     * Can be used with:
       * int _eg. 5 // 3 = 1_
       * float _eg. 13.0 % 6.0 = 2.0_
     * If at least one of the data type of one of the values is a float, then the data type of the result will also be a float

