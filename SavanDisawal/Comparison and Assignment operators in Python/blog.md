﻿# Comparison and Assignment operators in Python

 Hello friends! Here you will learn about comparison and assignment operators in **python**




**A. Comparison Operators:**

In python *Comparison* operator will always return Boolean value.

Following are the types of comparison operators:

**1** Equality 

**2**  Not Equal To 

**3** Greater Than

**4** Less Than 

**5**  Greater Than Equal To

**6** Less Than Equal To

## Lets learn one by one:

**1** Equality operator: For **Equality** operator we use **==** sign. Equality operator is used to check the equality of two Integers or two Strings or two variables.

**E.g.** 

``5 == 5``  will return **True**

``5 == 4`` will return **False**

``'Savan' == 'Savan'`` will return **True**

``'Savan' == 'Disawal' `` will return **False**

**2** Not Equal To operator: For **Not Equal To** operator we use **!=** sign. This operator is used to check if two values / Strings / Variables are not equal. 

**E.g.**  

``5 != 4`` will return **True**

``5 != 5`` will return **False**

``'Savan' != 'Disawal'`` will return **True**

``'Savan' != 'Savan'`` will return **False**

**3** Greater Than operator: For **Greater Than** operator we use **>** sign. This operator is used to check if one integer is greater than other. Or one String is Greater than other. Now here you will ask how Strings can be checked for Greater than. But if you know the ASCII values of all characters then you will understand how this can be checked.

**E.g.**

``5 > 4`` will return **True**

``5 > 6`` will return **False**

``'Savan' > 'savan'`` will return **False**  since ASCII value of 's' is 115 and ASCII value of 'S' is 83 and remaining values are same hence result is **False**

Similarly ``'savan' > 'Savan'`` will return **True**

If 1st character is same then it will check for 2nd character and so on.

**4** Less Than operator: For **Less Than** operator we use **<** sign. This operator is used to check if one integer is greater than other. Or one String is Greater than other.

**E.g.**

``5 < 4`` will return **False**

``5 < 6`` will return **True**

``'Savan' < 'savan'`` will return **True** 

``'savan' < 'Savan'`` will return **False**

 
**5** Greater Than Equal To: For **Greater Than Equal To** operator we use **>=** sign. This operator is used to check if one value is greater than or equal to other value. 

**E.g.**


``5 >= 5`` will return **True**

``5 >= 6`` will return **False**

``'Savan' >= 'savan'`` will return **False**

``'savan' >= 'Savan'`` will return **True**


**6** Less Than Equal To: For **Less Than Equal To** operator we use **<=** sign. This operator is used to check if one value is greater than or equal to other value. 

**E.g.**


``5 <= 5`` will return **True**

``5 <= 4`` will return **False**

``'Savan' <= 'savan'`` will return **True**

``'savan' <= 'Savan'`` will return **False**

**B. Assignment Operators:**

__'='__ is used for Assignment operator. This is used to assign value to a variable.
Let's see some example.

``number = 10``

``name ='Savan'``

``surname = "Disawal"``

You can do multiple assignments like ```number1 = number2 = number3 = 10``

Another interesting example is ``number1, number2 = 20, 50``

__20__ will be assigned to __number1__ and __50__ will be assigned to __number2__


