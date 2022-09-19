#This python code demonstrate how to sort an array using a bubble sort algorithm.
#Note: The time complexity of this sorting algorithm is O(N^2).

#Importing the array module.
import array

#Initializing the array, you can choose from multple array examples:
#Exmaple number one:
#int_array = array.array('i',[2,3,4,1])
#Exmaple number two:
#int_array = array.array('i',[7,2,5,3,4,1])
#Example number three:
#int_array = array.array('i',[2,8,4,9,1])
#Example number four:
int_array = array.array('i',[2,3,2,1,1,3,2,4])

#Declaring the boolean flag.
flag = False

#Printing the array before sorting it out:
print("Array before being bubble sorted:", end = " ")
for i in range(len(int_array)):
	print(int_array[i], end = " ")
print("")

#This while loop will keep running until our boolean flag will change to true.
#If the flag value has changed to true, that will mean that our array is now sorted and we can exit our loop.
#It will only change to true once the number of swaps was 0, meaning, there was no need to sort anything.
while flag == False:
	left = 0
	swaps = 0
	for right in range(1, len(int_array)):
		if int_array[left] > int_array[right]:
			tmp_var = int_array[left]
			int_array[left] = int_array[right]
			int_array[right] = tmp_var
			left+=1
			swaps+=1
		else:
			left+=1
	if swaps ==  0:
		flag = True

#Printing the array after sorting it out:
print("Array after being bubble sorted:", end = " ")
for i in range(len(int_array)):
        print(int_array[i], end = " ")
print("")

#Programmed by Sagi Cohen.
