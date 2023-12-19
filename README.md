Step 1: To write a python program for getting the word count from a text file

Step 2:

Open the required file by using the function "with".

Step 3:

Then use the laptop to assign the i value in the file.

Step 4:

Using split function to spilt the words

Step 5:

Finding the given length of the words by using len() fuction.

Step 6:

Calling the function and Printing the number of words.

PROGRAM:
```
#Program to find the word count.
#Developed by: JAYADEV PALLINTI
#RegisterNumber: 212223240058



num_word=0
with open ("sample.txt",'r') as f:
for i in f:
word=i.split()
num_word+=len(word)
print("number of words ={}".format(num_word)
```
OUTPUT:
![Screenshot 2023-12-19 103206](https://github.com/jayadev133/Word-count/assets/150319465/e2669f39-1c08-4316-b158-2a49a658c549)


![Screenshot 2023-12-19 103223](https://github.com/jayadev133/Word-count/assets/150319465/e5aece5a-75ec-4c1e-9f6c-a8fe97393761)


RESULT:
Thus the program is written to find the word count from a text.
