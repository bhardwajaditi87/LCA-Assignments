#Input List, Tuple and Dictionary data structure and operations on them
#list Operations
students_list=["Arjun", "Riya", "Rohan"]
print("Original list: ", students_list)
#Add
students_list.append("Ananya")
print("After adding: ", students_list)
#Update
students_list[1]="Priya"
print("After updating: ", students_list)
#Delete
students_list.remove("Rohan")
print("After deleting: ", students_list)

#Tuple Operations
students_tuple=("Aarav", "Riya", "Karan")
print("Tuple: ", students_tuple)
#Add
students_tuple = students_tuple + ("Ananya",)
print("After adding: ", students_tuple)
#Update
students_tuple = ("Aarav", "Priya", "Karan", "Ananya")
print("After updating: ", students_tuple)
#Delete
students_tuple = ("Aarav", "Priya", "Ananya")
print("After deleting: ", students_tuple)

#Dictionary Operations
students_dict={101: "Aarav", 102: "Riya", 103: "Karan"}
print("Original Dictionary: ", students_dict)
#Add
students_dict[104] = "Ananya"
print("After adding: ", students_dict)
#Update
students_dict[102] = "Priya"
print("After updating: ", students_dict)
#Delete
del students_dict[103]
print("After deleteing: ", students_dict)

OUTPUT:
Original list:  ['Arjun', 'Riya', 'Rohan']
After adding:  ['Arjun', 'Riya', 'Rohan', 'Ananya']
After updating:  ['Arjun', 'Priya', 'Rohan', 'Ananya']
After deleting:  ['Arjun', 'Priya', 'Ananya']
Tuple:  ('Aarav', 'Riya', 'Karan')
After adding:  ('Aarav', 'Riya', 'Karan', 'Ananya')
After updating:  ('Aarav', 'Priya', 'Karan', 'Ananya')
After deleting:  ('Aarav', 'Priya', 'Ananya')
Original Dictionary:  {101: 'Aarav', 102: 'Riya', 103: 'Karan'}
After adding:  {101: 'Aarav', 102: 'Riya', 103: 'Karan', 104: 'Ananya'}
After updating:  {101: 'Aarav', 102: 'Priya', 103: 'Karan', 104: 'Ananya'}
After deleteing:  {101: 'Aarav', 102: 'Priya', 104: 'Ananya'}




