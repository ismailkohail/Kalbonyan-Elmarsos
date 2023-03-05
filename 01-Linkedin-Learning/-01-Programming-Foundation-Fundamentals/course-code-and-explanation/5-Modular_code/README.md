### Functions:

Functions are a block of code packaged together with a name. and they are the core feature of all programming languages, they help us to avoid writing the same lines of code again and again.

### How to create a function :

**def say_hello():**

1. def is a short for define.
2. after the def put a name for the function followed by () and :
3. the function name must be unique and it should respect the language naming rules.

after that put the indentation, then

```
    print("Hello, friends!")
```

after creating the function, you must call it (declare it) like this :

```
say_hello()
say_hello()
say_hello()
```

**Parameters:**

allows functions to change their behavior based on some input.

**Arguments :**

the values that we pass to a function

**Examples:**

amount_paid is the parameter

```
def wash_car(amount_paid):

    if (amount_paid == 12):
        print("Wash with tri-color foam")
        print("Rinse twice")
        print("Dry with large blow dryer")

    if (amount_paid == 6):
        print("Wash with white foam")
        print("Rinse once")
        print("Air dry")

wash_car(6)
```

6 is the argument

---

### Return value from function

```
def withdraw_money(current_balance, amount):
if (current_balance >= amount):
current_balance = current_balance - amount
return current_balance

balance = withdraw_money(100, 80)

if (balance <= 50):
print("We need to make a deposit")
else:
print("Nothing to see here!")
```

---

### Functions in other languages

**Java :**

```
Void hello() {

system.out.printLn("Hi, friend");

}
```

The Void word means that the function doesn't return a value, Unlike Python, Java requires that you always specify explicitly what the return type is of a function, even when that function isn't going to return a value.

---

**Kotlin :**

```
fun CheckGrade(grade: string){

if (grade == "A")
printLn("You aced the class")

}
```

Unlike Python, we have to specify what the type of our parameter is when we define the function. We do that by placing a colon after the parameter's name, and then the type.

**Ruby:**

```
def calculate_check(hourly_rate)
hourly_rate \* 40

end
```

**JavaScript:**

```
function isEven(number) {
if (number % 2 == 0)
return "yes";
else
return "No";
}
```
