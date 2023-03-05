### Variable :

variable is simply a container for a value

The computer gives us space in its memory where we can put data that we want to use as a reference for later.

we make a variable by using the assignment operator = to assign a value to a variable that have a name

**Example:**

```
age = 36
print(age) \\ => 36
```

age : the name of the variable

= : the assignment operator

36 : the value that will be stored in the variable (age)

<br>

**Note:** when working with a "string" you should put it inside a quotation mark.

**Example:**

```
email= "john.doe@example.com"

print(email) \\ =>  john.doe@example.com
```

---

### How can we know the type of the data that is stored inside a variable?

<br>

we can do that by using the type() function

**Example :**

```
print(type(age)) \\ => int

print(type(email)) \\ => str
```

---

### Variable across language :

Some languages require that you define your variables and their types before you can use them, like Java, C , and C++.

**example in java :**

```
string cookie = "sugar";

system.out.println(cookie);
```

In other languages like Python, we don't need to declare a variable type before using it.

---

### Name convention for variables :

<br>

Names can only contain:

- letters
- numbers
- underscores

**Note:**

- the name can't start with number
- Don't use white space, instead use underscore
- the name in programming is case sensitive
- variable can not be keywords that words which are reserved by the language like If, For, while

To see the list of all of the keywords that are reserved by Python:

```
print(keyword.kwlist)
```

---

### Numbers:

**Integer:** a whole number

**float:** a decimal number has a floating point

### operators :

- addition[ + ]
- subtraction[ - ]
- multiplication[ * ]
- division[ / ]
- modularity [ % ] >>> give you the reminder of the division
- exponent [ ** ]

---

### Strings :

The name of a string comes from the fact that it's a string of characters one after the other. The characters can be letters, numbers, symbols, and even spaces.

you can put your string inside single quote or double quote, just make sure you don't use double inside another double the same thing goes for single quote.

---

### White spaces :

<br>

Python doesn't care about extra empty lines in your programs, just like most languages.

in general developers add white space for readability and to make the code look better

There are certain circumstances where white space really matters to Python. and that's when it relates to its special key words.

---

### Comments :

<br>

Comments are notes to your future self and others to describe what your code does, and they have no impact on your code, you can also use comments to help temporarily ignore some code.

In python you can make a line comment by adding a hash mark before the line.

in Vs code you can comment a line by pressing **ctrl + :**
