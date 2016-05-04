# Relational MapReduce Patterns #2 - Selections
Guide: http://www.slideshare.net/rantav/introduction-to-map-reduce

## Task
Given a set of integers, only select and display odd integers, greater than 10.

The code for the MapReduce class, reading and splitting the text, parts related to IO etc. has already been provided. However, for this particlar task, you ONLY need parts of the mapper and its related functions. However certain parts of the mapper and reducer functions are incomplete. You need to replace the questionmarks (?). Your task is to fill up these question marks appropriately, such that the program works, and performs the specified task. 
Also, this program may output certain information to the error stream. This information has been logged to help beginners gain a better understanding of the the intermediate steps in a map-reduce process.

## Input format
The first line contains an integer N, which is the number of elements in the set. This is followed by N integers, each on a new line, such that -100 <= X <= 100. Also, 10 <= N <= 100 
For instance, if R = [10,20,40,20,60];you may treat it as [10,20,40,60]

## Output Format
Output each of the integers satisfying the predicate (odd numbers exceeding 10), each on a new line, without disturbing their relative ordering.
