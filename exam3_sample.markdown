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

## Expressions

Evaluate the following expressions. Note the data type that gets
generated by each expression as well. You can check the solutions to
these problems by copying and pasting them into IDLE to see how Python
reacts.

- `  'a' + 'b'`

- `  'a' \* 5`

- `  5 \* 'a' + 5 \* 'b'`

- `  [1] + [2]`

- `  ['a', 'b'] + ['c', 'd']`

- `  [2] \* 4 + [4] \* 2`

- `  [1,2,3] + 3 \* [4]`

- `  99 % 3`

- `  5 + (10 % 3)`

- `  100 > 5`

- `  100 > 5 and 100 < 99`

- `  1 < 2 or 2 > 1`

- `  not (1 > 2) and not (3 < 3)`

- `  (True or False) and (False and True)`


- `  'cat' + 'dog'`

- `  'cat' > 'dog'`

- `  (99 * 2) < 200 or (100 > 50 * 2)`

- `  True or False or False or True`


- assume that `  x = 'giraffe' ` what are the values of the following expressions?
    - `x[2]`
    - `len(x)`
    - `x[:3]`
    - `x[4:]`

## Trace the Output

Trace the output of the following programs (each shaded box below is a
separate Python program.)

1.

    count = 0

    while count < 10:
        print ('Hello')
        count += 1

2.

    x = 10
    y = 0

    while x > y:
        print (x, y)
        x = x - 1
        y = y + 1

3.

    keepgoing = True
    x = 100

    while keepgoing:
        print (x)
        x = x - 10
        if x < 50:
            keepgoing = False

4.

    x = 45

    while x < 50:
        print (x)

5.

    for x in [1,2,3,4,5]:
        print (x)

6.

    for p in range(1,10):
        print (p)

7.

    for z in range(-500,500,100):
        print (z)

8.

    x = 10
    y = 5

    for i in range(x-y*2):
        print ("%", i)

9.

    c = 0

    for x in range(10):
        for y in range(5):
            c += 1

    print (c)

10.

    x = [1,2,3]

    counter = 0
    while counter < len(x):
        print (x[counter] * '%')
        for y in x:
            print (y * ' * ')
        counter += 1

11.

    for x in 'lamp':
        print (x.upper())

12.

    x = 'one'
    y = 'two'

    counter = 0
    while counter < len(x):
        print (x[counter], y[counter])
        counter+=1

14.

    y = ["apple","pear","peach","grapefruit"]

    for z in y:
        if z < 'm':
            print (z.lower())
        else:
            print (z.upper())

16.

    # Trace the output of the following program.  Then rewrite the program using a "while"
    # loop instead of a "for" loop.  You don't need to re-write the list - just rewrite
    # the looping portion of the program.

    pokemon = ["squirtle", "pikachu", "charmander",    
               "bulbasaur", "meowth"]

    for i in range(0, len(pokemon), 2):
        print (i, pokemon[i])


17.

    word = "pikachu"
    for c in word:
        print (c)

18.

    word = "pikachu"
    for i in range(0, len(word)):
        print (i, word[i])

19.

    word = "pikachu"
    for i in range(len(word)-1, -1, -1):
        print (i, word[i])

20.

    word = "pikachu"
    for i in range(0, len(word), 2):
        print (i, word[i])

21.

    word = "pikachu"
    print (word[0:len(word):2])

22.

    word = "hello, world"
    newword = word[0:2] + word[-2:]

    print (newword)

24.

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



## Programming Challenges

1.  Write a program that prompts the user to enter in 5 colors. Print
    out the colors entered in alphabetical orders. Then print out the
    colors entered in reverse alphabetical order.
2.  Write a program that prompts the user to enter in an unlimited
    number of colors. Test to make sure that the user did not already
    enter a color before storing it (i.e. "We're sorry, but you've
    already added the color 'yellow'"). When the user types the string
    "exit" you should stop collecting colors. The print out the colors
    entered in alphabetical order.
3.  Rewrite the following program using a `for` loop:

        x = [1,2,3,4,5]

        counter = 0
        while counter < len(x):
            print (x[counter])
            counter += 1

4.  Rewrite the following program using a `while` loop:

        x = ['a','b','c','d']

        for y in x:
            print (y)

5.  Rewrite the following program using a `while` loop:

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

7.  Write a program that accepts a single string entered by the user, then tests if the string contains all uppercase characters. If so, the program should print "ALL UPPER", otherwise, the program should print "not upper".

9.  Write a program that prompts the user for three numbers. The program should detect if the values entered by the user are numerical or not. If not, the program should re-prompt the user for that number (i.e., if the user enters "hello" instead of a number, they should be prompted for it again). Once the user enters three successful numbers, print the smallest of them.

10. Write a program that generates a random letter from the word "BINGO". This means that there are five possible outcomes and each of them is equally likely.  

11. Use the idea from the previous program to write a program that continually
    generates 5 random letters from the string 'BINGO' and prints them
    out along with the attempt number. If the 5 letters spell the word
    "BINGO" you can end the program and print out a congratulatory
    message. Here's a sample running of the program:

        1 OOOIG
        2 NIIIN
        3 BIGNN
        4 OGOIN
        5 BNOGB
        ...
        56 BGIIO
        57 NBONN
        58 IBNGI
        59 GNOBN
        60 BIGNO
        ...
        3860 BINGO
        Finally, after 3860 tries!

    - What is the probability of generating "BINGO" on any given try?

12. You have been asked to write a _slot machine_ program which should
    randomly arrange three graphical _symbols_ on the screen. All possible
    symbols are defined in the following list:

        symbols = ['cherry', 'pear', 'star', 'seven', 'watermelon']

    Write a program that randomly selects three of these symbols and
    prints them out to the user. The program terminates when the user wins (i.e.,
    they get the output in which all _symbols_ are the same).  Here is  a sample run of the program:

        cherry star seven
        seven watermelon star
        pear star cherry
        ...
        pear pear seven
        cherry star pear
        ...
        cherry cherry cherry

    - How many possible outcomes are there for each attempted try?
    - How many winning outcomes are there?
    - What is the probability of winning with a single try?

13. Write a program that generates a random series of lottery numbers
    for the user. Your program should generate 5 unique random numbers
    between 1 and 100. Numbers should not be repeated within a series
    and should be printed in ascending order. Here are three sample
    runnings of the program:

        Your lottery #'s are:
        [19, 61, 62, 78, 99]
        ================================

        Your lottery #'s are:
        [1, 41, 64, 66, 78]
        ================================

        Your lottery #'s are:
        [19, 20, 28, 41, 97]

    - What is the probability that the lottery numbers are all even?
    - What is the probability that the lottery numbers contain 100?

14. Write a program that prompts the user to enter a string (this could be a very long string, e.x., a text of a book). Calculate and display the frequency of each vowel.

15. Your program is given two lists:
    - list of movie titles (strings)
    - list of lead actor names separated by commas, for each of the movies for the first list

    Write the program that allows the user to enter the name of an actor and prints
    all the movies in which the actor performed.

    Continue your program after the following list definitions (your program should
    work even if the lists are changed):

        titles = ["Casablanca", "To Kill a Mockingbird (1962)", "The Treasure of the Sierra Madre", "The Maltese Falcon", "The Big Sleep", "Roman Holiday (1953)", "The Philadelphia Story", "Bringing Up Baby", "Charade", "The African Queen", "My Fair Lady", "Breakfast at Tiffany's", "Spellbound (1945)", "The Guns of Navarone (1961)", "The Omen"]

        actors = ["Humphrey Bogart, Ingrid Bergman", "Gregory Peck, John Megna", "Humphrey Bogart, Walter Huston", "Humphrey Bogart, Mary Astor", "Humphrey Bogart, Lauren Bacall", "Gregory Peck, Audrey Hepburn", "Cary Grant, Katharine Hepburn", "Katharine Hepburn, Cary Grant", "Cary Grant, Audrey Hepburn", "Humphrey Bogart, Katharine Hepburn", "Audrey Hepburn, Rex Harrison", "Audrey Hepburn, George Peppard", "Ingrid Bergman, Gregory Peck", "David Niven, Gregory Peck", "Gregory Peck, Lee Remick"]

<!--

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

    s = input("Enter a string: ")

    # look at each character in s and determine
    # if it is uppercase or lowercase
    upper == True
    for char in s:
        if char.isupper() == False:
            return False

    if upper :
        print("ALL UPPER")
    else :
        print("not upper")

**Problem \#9**   !!!!

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

**Problems \#10**

    import random

    # the string that is the source of random letters
    source = 'BINGO'

    # generate a random integer between 0 and 4
    num = random.randint(0,4)

    # get the letter at that position
    letter = source[num]

    # print it
    print ("the randome letter is:", letter)

**Problems \#11**

    import random

    source = "BINGO"
    counter = 0
    try = ""

    while try != source:

        # generate 5 random characters
        c1 = source[random.randint(0,4)]
        c2 = source[random.randint(0,4)]
        c3 = source[random.randint(0,4)]
        c4 = source[random.randint(0,4)]
        c5 = source[random.randint(0,4)]

        # build a word out of this letter
        try = c1 + c2 + c3 + c4 + c5

        counter += 1

        print (counter, try )

    print ("Finally, after", counter, "tries!")

**Problem \#12**  !!!

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
--> 
