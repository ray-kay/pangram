# Pangram

A Pangram is a string that contains all the lower-case letters (a to z) at least once.

This is a code test inplemented in JS.


#The sentence:
"the quick brown fox jumps over the lazy dog" is a pangram.
Pangram is a string that contains all the lower-case letters (a to z) at least once.

You are given a N strings, these strings consist of lower-case letters (a-z) and space only.
Your task is to find whether the string is pangram or not. If string is pangram print 1 otherwise print 0.

#Contraints
1<= N <=100
1<= |S| <=10^5, where |S| is the length of string S

#Input Format
First line is an integer N, total number of strings. Each of next N lines contains a string S, consisting of lower-case letters (a-z) and spaces.

#Output formart
Output a string of length N, consisting of only Zeros and Ones, where i th character in output corresponds to the output of i th string.

#Sample Input #1 

4
we promptly judge antique ivory buckles for the next prize
we promptly judge antique ivory buckles for the prize
the quick brown fox jumps over the lazy dog
the quick brown fox jump over the lazy dog

#Sample Output #1
1010

#Explanation #1

Here 1st and 3rd strings are pangram