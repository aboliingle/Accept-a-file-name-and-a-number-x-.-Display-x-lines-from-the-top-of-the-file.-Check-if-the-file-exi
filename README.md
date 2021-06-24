# Python Task Related to File.

# Task
Accept a file name and a number (x). Display x lines from the top of the file. Check if the file exists and is readable. The value of x should not exceed the total number of lines in the files. Display suitable messages in case an error is encountered.

# Introduction 
In this task I have to accept one file and number. Then I have to print the number of lines in file. After all this I have to find out file exists or not and also readable or not. At the end I have to print suitable massage in case of an error is encountred.

# Explanation
Step 1:- Create a file name. File nmae is "data.txt".

Step 2:- After creating a file we need to add some lines in the file. So we used "write mode" with the file name, example(fp = open("data.txt", 'w')). To write 10 lines in the file, range sholud be set to "10" then the loop will work for 10 times and 10 lines printed, as given in the "code file". 

Step 3:- As per mentioned in question we have to find out whether the file exists and is readable.
To find out file name exists or not. Imported "operating system package" then used if else condtional statement to print the massage that file exists or not. 

Step 4:- So, take 2 cases. First file name is "data.txt" and second file name is "ZXC.txt". So pass the "data.txt" file the program wil print "file exist",
then pass "ZXC.txt" file program will print "file not exist". The file we created in the starting only that file is exist.

Step 5 :- Next step to find out file is readable or not. In two ways we can find out that, so write "type 1" and "type 2" in the programme. It print "True" when file is readable. Print "False" when file is not readable

Step 6 :- As per mentioned in the task, we have to find out number of lines in the file. That count is stored in "line_count", you can see in programme. After counting the number of lines in the file. Compare the number "x" not exceed the number of lines in the file.

Step 7:- Take three different values for "x" i.e x = 8, x = 15, x = 10. Three cases I used to define three situation.

Step 8:- Case 1, When "X=8", The value of X is not exceed the number of lines in file then it will print "The value of x not exceed the number of lines in file".

Step 9:- Case 2, When "X=15", The value of X is exceed the number of lines in file then it will print "The value of x exceed the number of lines in file".

Step 10:- Case 3, When "X=10", The value of X is similar to the number of lines in file or any other error occured it will print "Error occured Try again with new value of x"

# Tool Used
Google Colab Notebook.

# Programing Langauge
Python 3.8
