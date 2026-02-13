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

1. Start

2. Read an integer number num

3. If num > 0, display Positive

4. Else if num < 0, display Negative

5. Else display Zero

6. Stop

Algorithm 2: Check Whether a Number is Even or Odd

1.Start

2,Read an integer number num

3.If num % 2 == 0, display Even

4.Else display Odd

5.Stop

Algorithm 3: Find the Largest of Three Numbers

1.Start

2.Read three integers a, b, and c

3.If a ≥ b and a ≥ c, print a is largest

4.Else if b ≥ a and b ≥ c, print b is largest

5.Else print c is largest

6.Stop

Algorithm 4: Calculate Grade Based on Single Subject Marks

1.Start

2.Read marks of the subject

3.If marks ≥ 90, print Grade A

4.Else if marks ≥ 75, print Grade B

5.Else if marks ≥ 60, print Grade C

6.Else if marks ≥ 40, print Grade D

7.Else print Fail

8.Stop

Algorithm 5: Calculate Average Grade of Three Subjects

1.Start

2.Read marks of three subjects a, b, and c

3.Calculate average = (a + b + c) / 3

4.If average ≥ 60, print Grade A

5.Else if average ≥ 50, print Grade B

6.Else if average ≥ 40, print Grade C

7.Else print Grade Fail

8.Stop

Algorithm 6: Check Whether a Year is a Leap Year

1,Start

2.Read year year

3.If year is divisible by 4

4.If year is divisible by 100

5.If year is divisible by 400, print Leap Year

6.Else print Not a Leap Year

7.Else print Leap Year

8.Else print Not a Leap Year

9.Stop

Algorithm 7: Check Whether a Character is Vowel or Consonant

1.Start

2.Read a character ch

3.If ch is in (a, e, i, o, u, A, E, I, O, U), print Vowel

4.Else print Consonant

5.Stop

Algorithm 8: Calculate Gross Salary with Allowances

1.Start

2.Read basic salary

If basic ≤ 10,000

HRA = 20% of basic

DA = 80% of basic

3.Else if basic ≤ 20,000

HRA = 25% of basic

DA = 90% of basic

4.Else

HRA = 30% of basic

DA = 95% of basic

5.Calculate Gross Salary = Basic + HRA + DA

6.Display Gross Salary

7.Stop

Algorithm 9: Calculate Income Tax Based on Annual Income

1.Start

2.Read annual income

If income ≤ 2,50,000, tax = 0

3.Else if income ≤ 5,00,000

4.tax = 5% of (income − 2,50,000)

Else if income ≤ 10,00,000

tax = 5% of 2,50,000 + 20% of (income − 5,00,000)

5.Else

tax = 5% of 2,50,000 + 20% of 5,00,000 + 30% of (income − 10,00,000)

6.Display tax amount

7.Stop

Algorithm 10: Check Valid Date and Print Next Date

1.Start

2.Read date in dd/mm/yyyy format

Separate day, month, and year

3.Find maximum days in the given month

31 days for months with 31 days

30 days for months with 30 days

28 or 29 days for February based on leap year

4.If month is invalid or day exceeds maximum days

5.Print Date is invalid

6.Else

7.If day equals maximum day and month is not December

8.Set day = 1 and increment month

9.Else if day equals maximum day and month is December

10.Set day = 1, month = 1, and increment year

Else

Increment day by 1

11.Display the next date

12.Stop


CONCLUSION
Thus, the experiment was successfully completed and we learned how to use conditional statements in Python to make decisions based on different conditions.
Conditional statements help in solving real-life problems logically and are essential for writing effective Python programs.
