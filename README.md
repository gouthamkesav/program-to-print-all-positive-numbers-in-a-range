# program-to-print-all-positive-numbers-in-a-range
list_1 = [12,-7,5,64,-14]
p_no = [num for num in list_1 if num >=0]
print("positive no in the list: ", *p_no)

list_2 = [12,14,-95,3]
p_nos = [num for num in list_2 if num >=0]
print('positive no in the list: ', *p_nos)
