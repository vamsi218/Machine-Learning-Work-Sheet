# Machine-Learning-Work-Sheet
MACHINE LEARNING WORKSHEET-1  
1.Write a python function which should be capable of finding the factorial of any given number as an argument.   
2. Luke Skywalker has family and friends. Help him remind them who is who. Given a string with a name, return the relation of that person to Luke. Person Relation Darth Vader father Leia sister Han brother in law R2D2 droid

Example : relation_to_luke("Darth Vader") ➞ "Luke, I am your father."  
3. Create a function which takes a number as its argument and return the number of digits in it. Use of len function is not allowed. For example for 5 it should return 1, for 32 it should return 2 and 123 , 3 should be returned and so on.  
4. Write a function which takes a number as argument suppose 5 and gives results as multiplication of factorial of each positive number less than or equal to the number given. i.e !5*!4*!3*!2*!1 = 34560  
5. Write a function which takes any number of arguments from a user and return the result which should be output of a2 + b2+ c2+… if a , b ,c are numbers supplied ..i.e if 1,2,3 are supplied then result returned should be 14. But user may supply any number of inputs so make the function to adapt to that.  
6.Write a function which accepts 3 arguments from the user.1 .number 1, 2. Number2 and 3. An operation. The operation supported should be +, -, *, and /. The function should return the result of given operation. For example arguments are 3,2,+ then result returned should be 5  
7. Write a function which takes an argument which should be a numeric +ve integer. Depending on the input supplied you have to print “I CAN”, “I WILL”. Suppose some one enters argument as 1 then only “I CAN” should be printed. But if some one enters 2 then first “I CAN” should be printed then “I WILL”. And if someone enters 3 then following should be printed in corresponding order: “I CAN”, “I WILL”, “I CAN” and so on for any numbers entered.  
8. We have been given a list of whole numbers which represents the color of each gloves, determine how many pairs of gloves with matching colors there are. For example, there are 7 gloves with colors [1, 2, 1, 2, 1, 3, 2]. There is one pair of color 1 and one of color 2. There are three odd gloves left, one of each color. The number of pairs is 2. Create a function that returns an integer representing the number of matching pairs of gloves that are available.  
9. Write a function that returns True if two arrays, when combined, form a consecutive sequence. A consecutive sequence is a sequence without any gaps in the integers, e.g. 1, 2, 3, 4, 5 is a consecutive sequence, but 1, 2, 4, 5 is not.  

Notes   
• The input lists will have unique values.  

• The input lists can be in any order.  

Examples  
consecutive_combo([7, 4, 5, 1], [2, 3, 6]) ➞ True  
consecutive_combo([1, 4, 6, 5], [2, 7, 8, 9]) ➞ False  
consecutive_combo([1, 4, 5, 6], [2, 3, 7, 8, 10]) ➞ False  
consecutive_combo([44, 46], [45]) ➞ True  
10. You work for a manufacturer, and have been asked to calculate the total profit made on the sales of a product. You are given a dictionary containing the cost price per unit (in dollars), sell price per unit (in dollars), and the starting inventory. Return the total profit made, rounded to the nearest dollar. 

Examples
profit({
"cost_price": 32.67,
"sell_price": 45.00,
"inventory": 1200
}) ➞ 14796
