# ASSN1

Assignment 1

The attached program reads the input from the given text files which contains student’s name followed by their exam marks. The output of this program will be as per the given task .i.e. it will output student’s name and their grades as per their marks in a well formatted way. Further more it displays the student’s grade as per their average marks and this program also full fills all the conditions mentioned in the assignment. Below is the explanation of the whole program along with their snippets


o	fhandling.cpp

In this file I have made a program which has two functions named int main() and isNumber(). Firstly while loop will be executed and will read the data from the file. Then getline() function will be called and will read the data line by line. isNumber() will check if the passed character is a number of type int or not. If yes, then the number will be used to initialise total score and if it is not a number then 3rd index of the vector tokens will be taken as full name. Then a loop will be executed which will read the marks of a particular student. And in this the marks will be stored in a vector (i.e. datatype used for storing marks) and at the same time when whole line will be read from the file along with marks and will get total scores and will be added into the vector and then this vector will be iterated and average will be calculated and grades will be founded taking reference from the given table and whole output will be displayed in the console and the output file.

o	fhandling2.cpp

In this file I have made a two-dimensional array whose ith index which is 25 and total jth index will be of columns which is 10 and in this two-dimensional array I will store every marks of the individual student. Like example: 0,1,2,3,4… and then I will find the average of the scores taking the average of ith index only. Example calculating the average of 25 students for one exam (vertically) likewise for all 10 exams. And now for grade another two dimensional array will is made named grade[] and the same marks will be iterated and all the three conditions will be checked and whichever grade will be obtained will be appended in the two-dimensional array according to the marks comparing a particular marks in greater then the average (i.e. linear array) and in the end whole output will be displayed in the file

o	isnum.h

This is a header file which is used in both the cpp files and this header includes a function called isNumber().This is a Boolean function .i.e this function will return True or False as per the conditions to be fulfilled .i.e will check whether the input string contains number or not
