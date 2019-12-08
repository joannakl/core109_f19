---
layout: exam
title: Exam 2 Practice Problems
---


# Topics covered

Here is a quick outline of what will be covered on the final exam. You should use it in conjunction with the review material for the [first exam](midterm1_sample_questions.html) and for the [second exam](midterm2_sample.html).

Here is a quick summary of math topics that you should be reviewing for
the final exam.

2.  Percentages
    -   group sizes as percentage of a whole
    -   pay increases (one+ trick)
    -   discounts
    -   finding what percent of one amount is another amount
    -   inflation - what is your money worth tomorrow
3.  Averages
    -   calculating GPA
    -   calculation other average values
4.  Linear growth
    -   calculating distance traveled within particular time
    -   currency exchange
    -   electricity bills (base pay)
    -   bonus calculation
    -   car rental fees
5.  Exponential growth
    -   interest calculations
    -   significance of doubling: rice and chessboard story, toilet
        paper and the Moon
    -   credit card payments
    -   retirement savings
6.  Probabilities
    -  enumerating all possible outcomes of an experiment
    -  determining the number of all possible outcomes
    -  calculating probabilities of a given outcome
7.  Statistics
    -   calculating mean, median and mode - what kind
        of information they reveal
    -   analyzing data distribution based on a histogram
    -   working with real data sets




Here is a quick summary of Python topics that you should be reviewing
for the final exam.

1.  Programming Mechanics
    -   Variables (what are they, creating them, using them, naming
        rules, etc)
    -   Reading input from the keyboard with the input() function
2.  Math Expressions
    -   Writing math expressions
    -   Evaluating math expressions
    -   Storing & printing the results of math expressions
3.  Data Types
    -   Strings
    -   Numeric data types
        -   Integers (int)
        -   Floating point numbers (float)
    -   The Boolean data type
    -   The List data type
    -   Mixed type expressions
    -   Type conversion (string to int, int to strings, etc)
4.  Basic String Manipulation
    -   Combining two strings (concatenation)
    -   Multiplying a string (x = 'hi' \* 5)
    -   Case manipulation (ex., `x = str.lower('JaSOn')` converts the string
        literal 'JaSOn' to 'jason)
    -   Calculating string length using the len() function
    -   Searching for substrings in a string
5.  Selection statements
    -   The structure of an `if` statement (`if` keyword, condition, colon, indentation)
    -   Writing a condition for an `if` statement
    -   Boolean operators (`<`, `>`, `==`, `!=`, `>=`, `<=`)
    -   Comparing numeric values using Boolean expressions
    -   Comparing string values using Boolean expressions
    -   Using the `if`-`else` statement
    -   Nesting decision structures (`if` statements inside other `if`
        statements)
    -   The `if`-`elif`-`else` statement
    -   Logical operators (`and`, `or`, `not`)
9.  Count Controlled Loops (`for` loops)
    -   mechanics and how they work
    -   iterating over a list (i.e. `for x in [1,2,3,4,5]`:)
    -   using the target variable in a `for` loop
    -   using the `range()` function
    -   nested loops (i.e. loops inside of other loops)
7.  Condition Controlled Loops (`while` loops)
    -   mechanics and how they work
    -   setting up conditions for a `while` loop
    -   infinite loops and how to avoid them
    -   sentinels (defining a value that the user enters that causes the
        loop to end)
    -   input validation loops (asking the user to continually enter a
        value until that value matches some condition)
6.  Generating random numbers
8.  Accumulator variables
    -   setting up and using accumulator variables
    -   self referential assignment statements (i.e. `counter = counter + 1`)
    -   augmented assignment operators (i.e. `counter += 1`)
11. Lists
    -   Simple variables vs. lists (simple variables can only hold one
        piece of data, but lists can hold multiple values) – you can
        think of a list like a "book" and a variable like a "sheet of
        paper"
    -   Defining lists in Python (i.e. `mylist = [1,2,3]`)
    -   Concatenating lists with the `+` operator
    -   Repeating lists with the `*` operator
    -   Referencing list items using index notation (i.e. `mylist[0]`)
    -   Iterating through a list using a `while` loop
    -   Iterating through a list using a `for` loop
    -   Using the `len()` function to determine the number of items in a list
    -   Updating the value of an item in a list using bracket notation
    -   Creating empty lists
    -   Finding an item in a list using the `in` operator
    -   Adding items to a list using the `append` method
    -   Sorting items in a list using the `sort` method
    -   Reversing items in a list using the `reverse` method
    -   Finding the position of an item in a list using the `index` method
    -   Inserting an item in a list at a specific index using the `insert`
        method
    -   Finding the largest and smallest values in a list using the `min`
        and `max` methods
    -   Totaling the values of all elements in a list using an
        accumulator variable
    -   Removing an item from a list using the `remove` method
12. Strings Manipulation
    -   Iterating through all characters in a string using a `for` loop
    -   Indexing a specific character in a string using bracket notation
    -   Iterating through all characters in a string using a `while` loop
    -   String immutability (you can't change a string using bracket
        notation like you would change a list element)
    -   Testing a string for substrings using the `in` operator
    -   Detecting character types in a string using the built-in string
        testing methods (`isdigit`, `isalpha`, `isalnum`, `islower`, `isupper`,
        `isspace`)
    -   Splitting a string into a list using the `split` method




# Sample problems

**Sample Problems**

Evaluate the following expressions. Note the data type that gets
generated by each expression as well. You can check the solutions to
these problems by copying and pasting them into IDLE to see how Python
reacts.

  ----------------------------------------------------------
  **Expression**

  'a' + 'b'

  'a' \* 5

  5 \* 'a' + 5 \* 'b'

  [1] + [2]

  ['a', 'b'] + ['c', 'd']

  [2] \* 4 + [4] \* 2

  [1,2,3] + 3 \* [4]

  99 % 3

  5 + (10 % 3)

  100 &gt; 5

  100 &gt; 5 and 100 &lt; 99

  1 &gt; 2 or 2 &gt; 1

  not (1 &gt; 2) and not (3 &lt; 3)

  (True or False) and (False and True)

  x = 'giraffe'\
  x[2] \# evaluate the result of this line of code

  x = 'G+I+R+A+F+F+E'\
  x.split("+") \# evaluate the result of this line of code

  'cat' + 'dog'

  'cat' &gt; 'dog'

  (99 \* 2) &lt; 200 or (100 &gt; 50 \* 2)

  True or False or False or True
  ----------------------------------------------------------

**Trace the Output**

*Trace the output of the following programs (each shaded box below is a
separate Python program.)*

    count = 0

    while count < 10:
        print ('Hello')
        count += 1

------

    x = 10
    y = 0

    while x > y:
        print (x, y)
        x = x - 1
        y = y + 1

------

    keepgoing = True
    x = 100

    while keepgoing:
        print (x)
        x = x - 10
        if x < 50:
            keepgoing = False

------

    x = 45

    while x < 50:
        print (x)

------

    for x in [1,2,3,4,5]:
        print (x)

------

    for p in range(1,10):
        print (p)

------

    for z in range(-500,500,100):
        print (z)

------

    x = 10
    y = 5

    for i in range(x-y*2):
        print ("%", i)

------

    c = 0

    for x in range(10):
        for y in range(5):
            c += 1

    print (c)

------

    x = [1,2,3]

    counter = 0
    while counter < len(x):

        print (x[counter] * '%')

        for y in x:
            print (y * '*')

        counter += 1

------

    for x in 'lamp':
        print (str.upper(x))

------

    x = 'one'
    y = 'two'

    counter = 0
    while counter < len(x):
        print (x[counter], y[counter])
        counter+=1

------

    x = "apple,pear,peach"
    y = x.split(",")

    for z in y:
        print (z)

------

    x = 'apple,pear,peach,grapefruit'
    y = x.split(',')

    for z in y:
        if z < 'm':
            print (str.lower(z))
        else:
            print (str.upper(z))

------

    def myfun(a):
        print (a * '#')

    x = "1-2-3-4-5"
    y = x.split("-")

    for z in y:
        myfun(int(z))

------

    # Trace the output of the following program.  Then rewrite the program using a "while"
    # loop instead of a "for" loop.  You don't need to re-write the list - just rewrite
    # the looping portion of the program.

    pokemon = ["squirtle", "pikachu", "charmander",    
               "bulbasaur", "meowth"]

    for i in range(0, len(pokemon), 2):
        print (i, pokemon[i])


    # rewrite
    counter = 0

    while counter < len(pokemon):
        print (counter, pokemon[counter])
        counter += 2

------

    word = "pikachu"
    for c in word:
        print (c)

------

    word = "pikachu"
    for i in range(0, len(word)):
        print (i, word[i])

------

    word = "pikachu"
    for i in range(len(word)-1, -1, -1):
        print (i, word[i])

------

    word = "pikachu"
    for i in range(0, len(word), 2):
        print (i, word[i])

------

    word = "pikachu"
    print (word[0:len(word):2])

------

    word = "hello, world"
    newword = word[0:2] + word[-2:]

    print (newword)

------

    def foo(a):
        b = ""
        for c in a:
            if c.isalpha():
                b+=c
        return b

    print( foo("hello there!") )

------

    phrase = "4 score and 7 years ago ..."

    for c in phrase:
        if not (c.isdigit()):
            print (c, end="")
        else:
            x = int(c)
            if x % 2 == 0:
                print (x+1, end="")
            else:
                print (x-1, end="")

------

**Programming Challenges**

1.  Write a program that prompts the user to enter in 5 colors. Print
    out the colors entered in alphabetical orders. Then print out the
    colors entered in reverse alphabetical order.
2.  Write a program that prompts the user to enter in an unlimited
    number of colors. Test to make sure that the user did not already
    enter a color before storing it (i.e. "We're sorry, but you've
    already added the color 'yellow'"). When the user types the string
    "exit" you should stop collecting colors. The print out the colors
    entered in alphabetical order.
3.  Rewrite the following program using a "for" loop:

        x = [1,2,3,4,5]

        counter = 0
        while counter < len(x):
            print (x[counter])
            counter += 1

4.  Rewrite the following program using a "while" loop:

        x = ['a','b','c','d']

        for y in x:
            print (y)

5.  Rewrite the following program using a "while" loop:

        x = 'python'

        for y in x:
            print (y)

6.  Write a program that lets a user enter in 5 price values. Ensure
    that the prices entered are greater than 0 (but you can assume they
    will be numeric and not alphanumeric). Once you have collected all
    the prices you should print out the following:
    -   The average price
    -   The highest price
    -   The lowest price
    -   If the user spent more than 100, you can give them the lowest
        priced item for free. In this case you should congratulate them,
        print out their total bill and average price without the lowest
        priced item factored in.
7.  Write a function that accepts a single string as an argument. Your
    function should then determine if the string contains all uppercase
    characters. If so, return True, and if not return False.
8.  Write a function that accepts a single string as an argument.
    Convert the string to all lowercase and return the new string.
9.  Write a program that continually prompts the user to enter in a
    number. Evaluate whether the value entered is a valid number (float
    or int). If it is, print out the number. If it isn't, ask the user
    to try again. Your program should not crash if the user enters an
    invalid number (i.e. "twenty" is invalid since it does not contain
    all numeric digits)
10. Write a function that generates a random letter from the string
    'BINGO'. Here is a sample running of this program:

        x = generate_bingo_letter()
        print (x)

        >> N

        x = generate_bingo_letter()
        print (x)

        >> O

11. Take your "bingo" function and write a program that continually
    generates 5 random letters from the string 'BINGO' and print them
    out along with the attempt number. If all 5 letters spell the word
    "BINGO" you can end the program and print out a congratulatory
    message. Here's a sample running of the program:

        0 GBOBI
        - OOOIG
        - NIIIN
        - BIGNN
        - OGOIN
        - BNOGB

        .......

        - 56 BGIIO
        - 57 NBONN
        - 58 IBNGI
        - 59 GNOBN
        - 60 BINGO
        Finally, after 3860 tries!

12. You have been asked to write a "slot machine" program which should
    randomly arrange three graphical symbols on the screen. All possible
    symbols are defined in the following list:

        symbols = ['cherry', 'pear', 'star', 'seven', 'watermelon']

    Write a program that randomly selects three of these symbols and
    prints them out to the user. You cannot repeat a symbol (i.e. you
    cannot select 'cherry' twice). Here's are a few sample runnings of
    the program:

        >> cherry star seven

        >> seven watermelon star

        >> pear star cherry

13. Write a program that generates a random series of lottery numbers
    for the user. Your program should generate 5 unique random numbers
    between 1 and 100. Numbers should not be repeated within a series
    and should be printed in ascending order. Here are three sample
    runnings of the program:

        Your lottery #'s are:
        [19, 61, 62, 78, 99]
        >>> ================================ RESTART

        Your lottery #'s are:
        [1, 41, 64, 66, 78]
        >>> ================================ RESTART

        Your lottery #'s are:
        [19, 20, 28, 41, 97]

14. Body Mass Index (BMI) is a measurement that is used to classify the
    weight of an individual as underweight, normal weight, overweight or
    obese. The formula for calculating BMI is as follows:*BMI = (Weight
    in pounds \* 703) / (height in inches)^2^*. BMI values can be
    interpreted as follows:

    -   Below 18.5 - underweight
    -   18.5 - 24.9 - normal
    -   25 - 29.9 - overweight
    -   30+ – obese

     

    Write a **function** called "calc\_bmi" that accepts two arguments -
    a weight value in pounds (float) and a height value in inches
    (float). You can assume the arguments supplied are valid floats.
    Using these arguments calculate BMI using the formula above, and
    **return** a the BMI (float) and a description (string). Use IPO
    notation to document your function.

15. Write a program that asks the user for their weight in pounds (one
    value) and their height in feet and inches (two values). You cannot
    assume anything about these values, so validate the input as
    necessary. Next, use the function you wrote for question \#14 to
    calculate the user's BMI and print it out for them as follows. Your
    program does not need to repeat. Note that 12 inches = 1 foot. (10
    points)

        Enter weight in pounds:  none of your business
        Sorry, that's not a valid weight.  Try again
        Enter weight in pounds:  150
        Enter height in feet: 6
        Enter height in inches:  none
        Sorry, that's not a valid height.  Try again.
        Enter a height in inches:  0

        A 6'0 person weighting 150lbs has a BMI of 20.3414352.  This is considered normal weight.

16. Write a function that rolls a 10 sided die. Your function should
    take no arguments and should return the result of the die roll. Then
    write a program that lets the user enter two integers (validate the
    values – the user could enter any data type here). Next, continually
    uses your function to roll two dice until both die roll the numbers
    that the user entered at the same time. Note that the numbers may
    appear in any order (i.e. if the user enters 6 and 5 a valid end
    state of your program would be the rolls (6,5) or (5,6). Keep track
    of how many rolls it took to reach this state. Here is a sample
    running of this program:

        Enter a number between 1 and 10:  6
        Enter a number between 1 and 10:  5

        -  5 and 1
        -  6 and 3
        -  3 and 10
        -  5 and 6
        Your numbers were found on roll # 4

17. Write a function called “line” that accepts a string as an argument.
    Your function should generate a string pattern based on the argument
    provided. Here are the rules:
    -   If the string provided is a number, and that number is even,
        generate a pattern of hash signs that matches the number
        provided. For example, calling line("4") will generate the
        following:

            ####

        and calling line("10") will generate the following:

            ##########

    -   If the string provided is a number, and that number is odd,
        generate a pattern of stars using the number provided. For
        example, calling line("3") will generate the following:

            ***

        and calling line("9") will generate the following:

            *********

        If the string provided is not a number you can simply generate
        and return empty string.

    Once you have generated your pattern you should return the result
    when completed. You cannot assume anything about the supplied
    string, and your function should avoid raising any exceptions that
    will cause your program to crash. If an exception is raised you can
    return an empty string.
18. Write a FUNCTION called "valid\_n\_number" that determines if a NYU
    Student ID is valid. For the purpose of this question a valid NYU
    Student ID is defined as follows:

    -   exactly 9 characters long
    -   begins with the uppercase character 'N'
    -   all characters beside the beginning 'N' character must be
        numbers

    Your function should accept a test "N number" as an ARGUMENT
    (String) and RETURN a status value (Boolean). Here's a sample
    program that uses your function:

        test1 = valid_n_number("N123")
        test2 = valid_n_number("N1234567890")
        test3 = valid_n_number("P12345678")
        test4 = valid_n_number("NXYZ!5678")
        test5 = valid_n_number("N12345678")

        print (test1, test2, test3, test4, test5)

    And here's the expected output:

        False False False False True

 

**Programming Problems – Solutions**

**Problem \#1**

    # create an empty list
    colors = []

    # prompt the user for 5 colors
    counter = 0
    while counter < 5:

        # get a color from the user
        color = input("Give me a color: ")

        # put the color in the list
        colors.append(color)

        counter += 1

    # sort the list
    colors.sort()

    print (colors)

    # reverse the list
    colors.reverse()

    print (colors)

**Problem \#2**

    colors = []

    # ask the user for an unlimited number of colors
    keepgoing = True

    while keepgoing == True:

        # ask the user for a color
        color = input('Give me a color: ')

        # does the user want to exit?
        if color == 'exit':
            keepgoing = False

        elif color in colors:
            print ("Sorry, that's already in the list.")

        else:
            colors.append(color)

    # sort the list
    colors.sort()

    print (colors)

**Problem \#3**

    x = [1,2,3,4,5]

    for y in x:
        print (y)

**Problem \#4**

    x = ['a','b','c','d']

    counter = 0

    while counter < len(x):
        print (x[counter])
        counter += 1

**Problem \#5**

    x = 'python'

    counter = 0

    while counter < len(x):

        print (x[counter])

        counter += 1

**Problem \#6**

    prices = []

    # grab 5 values from the user ensuring that they are
    # all greater than 0
    keepgoing = True

    # counter variable
    total = 0

    while keepgoing == True:

        # grab a price
        price = float(input("Give me a price: "))

        # is the price greater than zero?
        if price <= 0:
             print ("Sorry, too low.")
        else:
             prices.append(price)
             total += price

        # see if we can get out of the loop
        if len(prices) == 5:
             keepgoing = False

    print ("Average: ", total / 5)
    print ("Highest: ", max(prices))
    print ("Minimum: ", min(prices))

    # special deal
    if total > 100:

        newtotal = total - min(prices)

        print ("Congrats!")
        print ("New total: ", newtotal)

        print ("New average: ", newtotal / 4)

**Problem \#7**

    def uppercase_test(s):

        # look at each character in s and determine
        # if it is uppercase or lowercase
        for char in s:

            if char.isupper() == False:
                return False

        return True

    x = uppercase_test("CRAIG")

    print (x)

**Problem \#8**

    def lowercase_converter(s):

        s = str.lower(s)
        return s

**Problem \#9**

    keepgoing = True

    while keepgoing:

        # test to see if the number is truly a number
        try:
            num = float(input("Give me a number: "))

        # if there was an error, do this:
        except:
            print ("Sorry, bad number!  Try again.")

        else:
            keepgoing = False

    print (num)

**Problems \#10 & \#11**

    import random

    def generate_bingo_letter():

        # what is the string we are using as a source?
        source = 'BINGO'

        # generate a random integer between 0 and 4
        num = random.randint(0,4)

        # grab out the substring
        letter = source[num]

        # send it back
        return (letter)

    keepgoing = True

    counter = 1

    while keepgoing == True:

        # generate 5 random characters
        c1 = generate_bingo_letter()
        c2 = generate_bingo_letter()
        c3 = generate_bingo_letter()
        c4 = generate_bingo_letter()
        c5 = generate_bingo_letter()

        # build a word out of this letter
        word = c1 + c2 + c3 + c4 + c5

        # does this spell bingo?
        if word == 'BINGO':
            print ("got it after", counter, "tries!")
            keepgoing = False
        else:
            counter += 1

**Problem \#12**

    import random

    symbols = ['cherry', 'pear', 'star', 'seven', 'watermelon']

    # select 3 symbols at random
    for x in range (3):

         # get a random number between 0 and the length of our list
         i = random.randint(0, len(symbols) - 1)

         # print out the symbol at this position
         print (symbols[i], ' ', end = '')

         # remove the symbol from the list
         symbols.remove(symbols[i])

**Problem \#13**

    import random

    lottery = []

    for x in range(5):

        while True:

            num = random.randint(1,100)
            if num not in lottery:
                lottery.append(num)
                break


    lottery.sort()

    print (lottery)

**Problems \#14 and \#15**

    def calc_bmi(weight, height):

        bmi = (weight*703)/(height**2)

        if bmi < 18.5:
            return bmi, "Underweight"
        elif bmi < 25:
            return bmi, "Normal weight"
        elif bmi < 30:
            return bmi, "Overweight"
        else:
            return bmi, "Obese"



    # get weight
    while True:
        try:
            weight = float(input("Enter weight in pounds: "))
        except:
            print ("Not a valid weight, try again")
        else:
            if weight < 0:
                print ("Negative weight values are not allowed")
            else:
                break

    # get height in feet and inches
    while True:
        try:
            height_feet = int(input("Enter height in feet: "))
            height_inches = int(input("Enter height in inches: "))
        except:
            print ("Not a valid height, try again")
        else:
            if height_feet <= 0 or height_inches < 0 or height_inches >= 12:
                print ("Invalid entry, try again")
            else:
                break

    # calc bmi
    bmi, description = calc_bmi(weight, height_feet*12+height_inches)

    print ("A", height_feet, "'", height_inches, "person weighing", weight, "lbs has a BMI of", bmi, ". This is considered", description)

**Problem \#16**

    import random

    def roll_10_sided_die():
        d1 = random.randint(1,10)
        d2 = random.randint(1,10)
        return d1, d2

    while True:
        try:
            user_d1 = int(input("Enter a number between 1 and 10: "))
            user_d2 = int(input("Enter a number between 1 and 10: "))
        except:
            print ("Invalid number, try again")
        else:
            if user_d1 < 1 or user_d1 > 10 or user_d2 < 1 or user_d2 > 10:
                print ("Numbers must be between 1 and 10, try again")
            else:
                break

    counter = 0
    while True:

        counter += 1

        d1, d2 = roll_10_sided_die()

        print (counter, ". ", d1, " and ", d2, sep="")

        if (d1 == user_d1 and d2 == user_d2) or (d1 == user_d2 and d2 == user_d1):
            print ("Your numbers were found on roll #", counter)
            break

**Problem \#17**

    def line(x):

        try:
            if x.isdigit():
                x = int(x)
                if x % 2 == 0:
                    return x*"#"
                else:
                    return x*"*"
            else:
                return ""
        except:
            return ""


    print (line("4"))
    print (line("5"))
    print (line("apple"))
    print (line(100))

**Problems \#18**

    def valid_n_number(number):

        if len(number) != 9:
            return False
        else:
            if number[0] != "N":
                return False
            else:
                testdigits = number[1:]
                if testdigits.isdigit():
                    return True
                else:
                    return False


    print (valid_n_number("N123") )
    print (valid_n_number("N1234567890") )
    print (valid_n_number("P12345678") )
    print (valid_n_number("NXYZ!5678") )
    print (valid_n_number("N12345678") )
