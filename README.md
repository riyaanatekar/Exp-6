AIM
To study and implement conditional statements in Python 
using if, elif, and else 
for solving different decision-making problems such as checking positive/negative numbers, even or odd, largest number, grade calculation, leap year, salary calculation, income tax, vowel or consonant, and date validation.

THEORY
Conditional statements in Python are used to execute different blocks of code based on conditions.
Python provides the following conditional constructs:
if statement – executes a block when the condition is true.
if–else statement – provides an alternative block if the condition is false.
if–elif–else ladder – checks multiple conditions in sequence.

ALGORITHM

Algorithm 1(a) & 1(b): Check Whether a Number is Positive, Negative or Zero
Start
Read an integer number num
If num > 0, display Positive
Else if num < 0, display Negative
Else display Zero
Stop

Algorithm 2: Check Whether a Number is Even or Odd
Start
Read an integer number num
If num % 2 == 0, display Even
Else display Odd
Stop

Algorithm 3: Find the Largest of Three Numbers
Start
Read three integers a, b, and c
If a ≥ b and a ≥ c, print a is largest
Else if b ≥ a and b ≥ c, print b is largest
Else print c is largest
Stop

Algorithm 4: Calculate Grade Based on Single Subject Marks
Start
Read marks of the subject
If marks ≥ 90, print Grade A
Else if marks ≥ 75, print Grade B
Else if marks ≥ 60, print Grade C
Else if marks ≥ 40, print Grade D
Else print Fail
Stop

Algorithm 5: Calculate Average Grade of Three Subjects
Start
Read marks of three subjects a, b, and c
Calculate average = (a + b + c) / 3
If average ≥ 60, print Grade A
Else if average ≥ 50, print Grade B
Else if average ≥ 40, print Grade C
Else print Grade Fail
Stop

Algorithm 6: Check Whether a Year is a Leap Year
Start
Read year year
If year is divisible by 4
If year is divisible by 100
If year is divisible by 400, print Leap Year
Else print Not a Leap Year
Else print Leap Year
Else print Not a Leap Year
Stop

Algorithm 7: Check Whether a Character is Vowel or Consonant
Start
Read a character ch
If ch is in (a, e, i, o, u, A, E, I, O, U), print Vowel
Else print Consonant
Stop

Algorithm 8: Calculate Gross Salary with Allowances
Start
Read basic salary
If basic ≤ 10,000
HRA = 20% of basic
DA = 80% of basic
Else if basic ≤ 20,000
HRA = 25% of basic
DA = 90% of basic
Else
HRA = 30% of basic
DA = 95% of basic
Calculate Gross Salary = Basic + HRA + DA
Display Gross Salary
Stop

Algorithm 9: Calculate Income Tax Based on Annual Income
Start
Read annual income
If income ≤ 2,50,000, tax = 0
Else if income ≤ 5,00,000
tax = 5% of (income − 2,50,000)
Else if income ≤ 10,00,000
tax = 5% of 2,50,000 + 20% of (income − 5,00,000)
Else
tax = 5% of 2,50,000 + 20% of 5,00,000 + 30% of (income − 10,00,000)
Display tax amount
Stop

Algorithm 10: Check Valid Date and Print Next Date
Start
Read date in dd/mm/yyyy format
Separate day, month, and year
Find maximum days in the given month
31 days for months with 31 days
30 days for months with 30 days
28 or 29 days for February based on leap year
If month is invalid or day exceeds maximum days
Print Date is invalid
Else
If day equals maximum day and month is not December
Set day = 1 and increment month
Else if day equals maximum day and month is December
Set day = 1, month = 1, and increment year
Else
Increment day by 1
Display the next date
Stop


CONCLUSION
Thus, the experiment was successfully completed and we learned how to use conditional statements in Python to make decisions based on different conditions.
Conditional statements help in solving real-life problems logically and are essential for writing effective Python programs.
