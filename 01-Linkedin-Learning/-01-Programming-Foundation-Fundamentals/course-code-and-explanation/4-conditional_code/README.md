### Conditional or Boolean expression:

<br>

Any expression that breaks down to either true or false

**Relation operators :**

operand1 (operator) operand2 => True/False

**Equality operator :**

operand1 == operand2 => True/False

**UnEquality operator:**

operand1 != operand2 => True/False

**Greater than operator:**

operand1 > operand2 => True/False

**Less than operator:**

operand1 < operand2 => True/False

**Greater than or equal operator:**

operand1 >= operand2 => True/False

**Less than or equal operator:**

operand1 <= operand2 => True/False

| Symbol         | Operation                | Examples        |
| -------------- | ------------------------ | --------------- |
| &nbsp;&emsp;== | Equal to                 | 3 == 3 // True  |
| &nbsp;&emsp;!= | Not Equal to             | 3 != 3 // False |
| &nbsp;&emsp;<  | Less than                | 3 < 4 // True   |
| &nbsp;&emsp;>  | Greater than             | 3 > 4 // False  |
| &nbsp;&emsp;>= | Greater than or equal to | 3 > 4 // True   |
| &nbsp;&emsp;<= | Less than or equal to    | 3 <= 4 // True  |

**Note :** 4 Not equal to "4", because they are not from the same type, one is an integer and the other is a string.

---

### Conditional Content:

<br>

We can make decision in code by using the if statement

<br>

**If condition :** execute the block if the condition is true, if not skip the if condition.

**block:** statements that are grouped together.

The indentation in Python is very important, because that's how the interpreter knows which statements belong to the if.

---

To add a bit more flexibility to our code we can add one more condition by using else-if statement

<br>

```
plant = "Irises"

if plant == "Cacti":
    print(plant, "don't need a lot of water")
else:
    print(plant, "love water")

print("Thanks!")
```
