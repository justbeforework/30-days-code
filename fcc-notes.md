These are notes I made from freecodecamp.com javascript course

- Comments are ignored

      // this is a single line comment

      /* this is multi-line comment*/
  
- 7 types of javascript data: undefined, null, object, boolean, number, symbol, string

- Variables allow computers to store data.

- Must not start with a number.

- Can initialize a variable to value when it's created:

    var myVar = 'value';
  
- Variables have initial value of `undefined`.

- Math on `undefined` = `NaN`

- "string" + `undefined` = "undefined" //contatenation is what this is called

- Variables are case sensitive.

- Use `camelCase` to name variables.

- Adding:
      `1` `+` `2`
      `1 - 2`
      `1 * 2`
      `1 / 2`
     
- Increment is the same as `i++` equivalent of `i = i+1;`

- Decrement: `i--;`

- Decimal numbers are floating point numbers:

        var myDecimal = 5.7;
        
- % is remainder operator, gives remainders of division:

        var remainder = 11 % 5;
        // return 1, can be used to check whether number is odd or even
        17 % 2 = 1; // is odd
        44 % 2 = 0; // is even
        
        //this is kinda cool
        
- compound assignment:
            
            myVar = myVar + 5;
            myvar += 5; // same for subtraction and multiplication and division
            
- string literal is zero or more characters enclosed in ""
            
        myVar = "this is a string literal";
        
- escaping literal quotes in strings:

        var strLit = "this is in \"double quotes\"."; // i can imagine this coming up often
        
- strings can be written in 'single' or "double" quotes. Can also escape a lot of characters:

        \n  // is new line
        \'  // is single quote
        \r  // return carraige ? what this, enter?
        \t // is tab
        \b // is backspace
        \f // is formfeed ?? dunno
        
- concatanation: adding strings:

        my Str = "this" + "this"; //"thisthis"
        //can even use +="this";
        
- Find the length of a string:

        var len = "some string".length;
        
- Most languages start counting at zero, called zero-based index. Can use bracket notation to a certain character at that index.
    
        var firstLetter = "";
        var str  = "some string";
        var firstLetter = str[0];
        
- String values are immutable, so cannot be changed once created (don't really get this):

        var str = "string";
        str[0] = "i"; // cannot change the s to an i, no this way
        
        // the only way to change is to create a new string:
        
        var str = "itring";
        
- using bracket notation to find last letter in string

        // subtract 1 from the strings length
        var myStr = "8 length";
        
        var length = myStr[mystr.length-1];
        
        // can do this to get nth last character
        
        
        
