# -4-Variables-use-input-function-python
1. Create 4 Variables use input function() (Name (string),Math Grade (float),Science Grade (float),English Grade (integer), Average (float)) 

2. Assign appropriate value 

3. Display the result: 

Name: __________ 

Math Grade:_____________ 

Science Grade:___________ 

English Grade:___________ 

Average:______________

----------------------------------------------------------------------------------------------------------------

name = input("name: ")

mathgrade = float(input("enter your math grade: "))

sciencegrade = float(input("enter your science grade: "))

english = int(input("enter your english grade: "))

add = mathgrade + sciencegrade + english

average = float(add /3)

print("Name: " + name)

print("Math grade: " + str(mathgrade))

print("Science grade: " + str(sciencegrade))

print("English grade: " + str(english))

print("average: " + str(average))
