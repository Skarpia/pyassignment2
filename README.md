# pyassignment2
python PLP assignment 2

#python PLP assignment 2
#creating an empty list
my_list = {}
print(my_list)
#appending items on a list list
my_list = []
print("before append:", my_list)
#append function
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)
print("after append:",my_list)
#insert an element in the list
my_list.insert(1, "15")
print(my_list)
#using extend function
my_list2 = {50, 60, 70}
my_list.extend(my_list2)
print("list after extend:", my_list)
#removing an element from a list
del my_list[-1]
print(my_list)
#sorting a list in ascending order
my_list = [10, 20, 30, 40, 50, 60, 70]
my_list.sort()
print(my_list)
#finding an element using index
my_list = [10, 20, 30, 40, 50, 60, 70]
my_list.index(30)
