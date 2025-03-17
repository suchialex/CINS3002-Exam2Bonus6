# Instructions


<details>
  <summary>
    Assignment Instructions
  </summary>

- In replit under bonuses folder -> Create a file named exam2bonus6.py
- In that file, create a function called all_todos() - use pass keyword in the function body for now
- Create a function for each todo for example TODO 1 will be in todo1()
- Call todo1() in all_todos() after the pass keyword
- Import the bonuses/exam2bonus6 module in main. Call all_todos() in main.py
- As you complete each todo, comment out the function call to that todo
- You may use the default print statement or suchi_print
</details>


## Simple Dictionary

<details>
  <summary>
    ✅ 1. TODO: ⏩ Refer to 9-1a
  </summary>

  Create an empty dictionary and print it
</details>


<details>
  <summary>
    ✅ 2. TODO: ⏩ Refer to 9-2a-c
  </summary>

  Create a dictionary with following values using all the three methods and print it

  code -> "101"  
  title -> "Twilight"  
  price -> 25.99  
  copies -> 5
</details>


<details>
  <summary>
    ✅ 3. TODO: ⏩ Refer to 9-3a-c
  </summary>

  In the above created dictionary, find the value using the user input key, without raising an exception 

  ```python
  # 3. @TODO3a-c: Access dictionary values given the key
  key = input("Enter the key to access value: ")

  # a. Using exception handling


  # b. Using IF statement


  # c. Using the method

  ```
</details>


<details>
  <summary>
    ✅ 4. TODO: ⏩ Refer to 9-4a
  </summary>
  Change the book title to - Eclipse
</details>


<details>
  <summary>
    ✅ 5. TODO ⏩ Refer to 9-3b, 9-6:
  </summary>

  - Delete dictionary element at user-specified key
  - Without raising an exception
  - Hint: Use in operator to check if key exists

  ```python
  key = input("Enter the key to delete its value: ")
  ```
</details>


<details>
  <summary>
    ✅ 6. TODO ⏩ Refer to 9-5:
  </summary>
  Print how many data elements (key/value pairs) are there in your dictionary
</details>


## Complex Dictionary
Given the following dictionary
```python
student1 = {
         "age" : 29,
         "gpa" : 3.45,
         "name" : "John Smith",
         "courses" : {"fall": ["math 101", 'engl 101'],
                      "winter" : ["math 201", 'engl 201'],
                      "spring" : ["math 201", 'engl 201'],
                      "summer" : ["math 201", 'engl 201'],
                      },
         "sports" : ("tennis", "badminton", "ping pong"),
         "colors" : ["red", "black", "yellow"],
         "favorites" : ["apple", "orange", "banana"]
         }
```


<details>
  <summary>
    ✅ 7. TODO ⏩ Refer to 9-7:
  </summary>

Print the name and age of the student like this

NAME: John Smith  
AGE: 29  
</details>


<details>
  <summary>
    ✅ 8. TODO ⏩ Refer to 9-7:
  </summary>
  
  Print the colors of the student each in one line, must look like this  
  red  
  black  
  yellow
</details>


<details>
  <summary>
    ✅ 9. TODO ⏩ Refer to 9-7:
  </summary>

  Print the courses taken by the student in fall, like this  
  
  MATH 101  
  ENGL 101
</details>


<details>
  <summary>
    ✅ 10. TODO ⏩ Refer to 9-7:
  </summary>
  Change the student's age to 19
</details>


<details>
  <summary>
    ✅ 11. TODO ⏩ Refer to 9-7:
  </summary>
  Add pear to the student's favorite fruits (you may add at the end)
</details>


<details>
  <summary>
    ✅ 12. TODO ⏩ Refer to 9-7:
  </summary>
  Register student for acct 101 in Fall
</details>

<details>
  <summary>
    ✅ 13. TODO ⏩ Refer to 9-7:
  </summary>
  Drop student from math 201 in winter
</details>


<details>
  <summary>
    ✅ 14. TODO ⏩ Refer to 9-6:
  </summary>

  Drop student from math 101 in winter (Yes, student is not enrolled in math 101)  
  So, use exception handling or use `in` before attempting to delete
</details>


## Given the following dictionary
```python
student2 = {
         "age" : 20,
         "gpa" : 3.78,
         "name" : "Mira Ray",
         "major" : "ACCT",
         "courses" : {"fall": ["math 101", 'fren 101'],
                      "winter" : ["acct 201", 'span 201'],
                      "spring" : ["hist 301", 'engl 101']
                      }
        }
```


<details>
  <summary>
    ✅ 15. TODO ⏩ Refer to 9-7:
  </summary>
  Add pink as one of the favorite colors (colors must be a list)
</details>


<details>
  <summary>
    ✅ 16. TODO ⏩ Refer to 9-7:
  </summary>
  Add pickleball and volleyball as the student's sports (sports must be a tuple)
</details>


<details>
  <summary>
    ✅ 17. TODO ⏩ Refer to 9-7:
  </summary>
  Add two courses for this student for summer - engl 202 and span 304
</details>


<details>
  <summary>
    ✅ 18. TODO ⏩ Refer to 9-6a, 9-6c, 9-7:
  </summary>
  
  Write a statement to delete the student's favorite fruits   
  
  💡 Hint:
  - key doesn't exist for this student, so you must
  - check if key is present using in operator
  - then write the del statement
</details>


<details>
  <summary>
    ✅ 19. TODO ⏩ Refer to 9-9a:
  </summary>
  Create a copy of dictionary student2 and call it student3
</details>


<details>
  <summary>
    ✅ 20. TODO ⏩ Refer to 9-9b:
  </summary>
  Delete the elements of student3 (but keep the dictionary)
</details>


<details>
  <summary>
    ✅ 21. TODO ⏩ Refer to 9-9c:
  </summary>
  Get the favorite fruits of student2 without raising an exception. Don't use the IF statement.
</details>


<details>
  <summary>
    ✅ 22. TODO ⏩ Refer to 9-9d:
  </summary>
  Using ONE statement with update() method, change the gpa of student2 to 3.84 and add new key cwid as 30088999
</details>


<details>
  <summary>
    ✅ 23. TODO ⏩ Refer to 9-9e:
  </summary>
  Print all the dictionary's keys and associated values of the student1 dictionary
</details>


<details>
  <summary>
    ✅ 24. TODO ⏩ Refer to 9-9f:
  </summary>
  Print the keys of student2 dictionary
</details>


<details>
  <summary>
    ✅ 25. TODO ⏩ Refer to 9-9g:
  </summary>
  Print just the values of student1
</details>


<details>
  <summary>
    ✅ 26. TODO ⏩ Refer to 9-9h:
  </summary>
  Delete major and its value from the student2 dictionary - use a method (not del statement)
</details>


<details>
  <summary>
    ✅ 27. TODO ⏩ Refer to 9-10:
  </summary>
  Pickle the dictionary student1 and save it in file named student1.txt
</details>


<details>
  <summary>
    ✅ 28. TODO ⏩ Refer to 9-10:
  </summary>
  Pickle the dictionary student2 and save it in file named student2.txt
</details>


<details>
  <summary>
    ✅ 29. TODO ⏩ Refer to 9-11:
  </summary>
  Unpickle student1.txt and print that dictionary
</details>


<details>
  <summary>
    ✅ 30. TODO ⏩ Refer to 9-11:
  </summary>
  Unpickle student2.txt and print that dictionary
</details>


# Sets

<details>
  <summary>
    ✅ 31. TODO - All set operations
  </summary>

  1. Create an empty set named honor_roll_students  
  ⏩ Refer to 9-12-1

  2. Create a set named comp_sci_students with values John, Jimmy, Reagan, Keenan, Timmy, Jonathan  
  ⏩ Refer to 9-12-2a
  3. Create a set named comp_sci_students2 with the list given below  
names = ["Mary", "Priya", "Anna", "Christina", "Karen", "Michelle"]  
⏩ Refer to 9-12-2b
4. Add elements of comp_sci_students2 to comp_sci_students  
⏩ Refer to 9-12-4b1
5. Create a tuple named t_students with four names of your choice - ⏩ Refer to 7-27c, and add the elements of t_students to the set comp_sci_students  
⏩ Refer to 9-12-4b2
6. Add the first five students of the list below to the honor_roll_students set you created in 1. 💡 Hint: slice the list and then use the update method  
list1 = ["Jonathan", "Jeremy", "Tiffany", "Malachi", "Keenan", "Peter", "Daniel"]
7. Add a student Brittany to both comp_sci_students and honor_roll_students (in two statements)  
⏩ Refer to 9-12-4a
8. Write statements for two different ways to remove John from honor_roll_students. Comment out the one that is raising an exception.  
⏩ Refer to 9-12-4c,4d
### Set Operations:
9. Print the computer science students that are also in the honor roll  
⏩ Refer to 9-12-8
10. Get all the students from both computer science and honor roll sets, in a set and print it  
⏩ Refer to 9-12-7
11. Print the computer science students that are not in the honor roll  
⏩ Refer to 9-12-9
12. Print the honor roll students that are not computer science students  
⏩ Refer to 9-12-9
13. Print all the students in both the lists, except for those who are both computer science students and in the honor roll  
⏩ Refer to 9-12-10
</details>


## Comprehensions

<details>
  <summary>
    ✅ 32. TODO: ⏩ Refer to 9-13
  </summary>
  
  From the list given, create a set with elements that are > 25 - using set comprehension  
  my_list = [25, 45, 56, 23, 17, 34, 33, 67, 20, 22, 78]
</details>


<details>
  <summary>
    ✅ 33. TODO: ⏩ Refer to 9-14
  </summary>

  Given the dictionary of products and prices in pounds
- Create another dictionary with products and prices in dollars rounded to two decimal places (Hint: Use round())
- The conversion rate is the variable pound_to_dollar
- Use dictionary comprehension

```python
# Given the dictionary of products and prices in pounds, create another dictionary with products and prices in dollars rounded to two decimal places

old_price = {'milk': 0.78, 'coffee': 1.9, 'bread': 1.7, 'eggs': 2.5}
pound_to_dollar = 1.32
```

</details>

