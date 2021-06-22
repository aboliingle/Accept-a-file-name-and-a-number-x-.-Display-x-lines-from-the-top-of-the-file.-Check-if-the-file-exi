# Accept-a-file-name-and-a-number-x-.-Display-x-lines-from-the-top-of-the-file.-Check-if-the-file-exi
Accept a file name and a number (x). Display x lines from the top of the file. Check if the file exists and is readable. The value of x should not exceed the total number of lines in the files. Display suitable messages in case an error is encountered.



# Content of the file
for i in range(10):
     fp.write("This is line %d\r\n" % (i+1))
fp.close()                                         # close the file.

# Read line by line from the file
fp = open("data.txt")                               # fp is file pointer.
lines = fp.readlines()
for line in lines:
  print(line)
fp.close()

# Print the number of lines in a file
fp = open("data.txt", "r")                         # file created and open file for reading the content.
line_count = len(lines)                            # count the number of lines content in file data.txt
fp. close()                                        # When ever file is open we have to close the file.
print(line_count)                                  # print the number of lines.

//The value of x should not exceed the total number of lines in the files. Display suitable messages in case an error is encountered.//

#case 1
x = 8                                               # different values assign for "x"
if line_count > x:
  print("The value of x not exceed the number of lines in file")
elif line_count < x:
  print("The value of x exceed the number of lines in file")
else:
  print("Error occured Try again with new value of x")

output:- The value of x not exceed the number of lines in file

#case 2
x = 15                                                # different values assign for "x"
if line_count > x:
  print("The value of x not exceed the number of lines in file")
elif line_count < x:
  print("The value of x exceed the number of lines in file")
else:
  print("Error occured Try again with new value of x")

output:- The value of x exceed the number of lines in file

#case 3
x = 10                                               # different values assign for "x"
if line_count > x:
  print("The value of x not exceed the number of lines in file")
elif line_count < x:
  print("The value of x exceed the number of lines in file")
else:
  print("Error occured Try again with new value of x")         #Displayed the suitable messages in case of an error is encountered

output:- Error occured Try again with new value of x
