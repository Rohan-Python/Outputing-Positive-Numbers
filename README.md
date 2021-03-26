# Outputing-Positive-Numbers
This program outputs only positive number 
lst1 = [] 
lst1 = [int(item) for item in input("Enter random integers without commas in between: ").split()]
for num in lst1 :
    if num >= 0:
       print(num, end = " ")
