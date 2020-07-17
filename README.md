# 3-Basic-Python-Problem-Solving-Questions
3 questions on problem solving using Python was assigned as assignment by the Praxis Business School.

1. Maria plays college basketball and wants to go pro. Each season she maintains a record of her play. She tabulates the number of times she breaks her season record for most points and least points in a game. Points scored in the first game establish her record for the season, and she begins counting from there.

For example, assume her scores for the season are represented in the array = [12,24,10,24] . Scores are in the same order as the games played.

Given Maria's scores for a season, find and print the number of times she breaks her records.

Create a user defined function which can take:

number of matches played
scores in those matches
Output: an integer - how many times she has broken her own records in the season

The function defined should pass following test cases by returning the desired output:

4
12,24,10,24
output: 1
8
10, 5, 20, 20, 4, 6, 25, 20
output: 2
12
1,2,2,3,3,3,4,4,4,4,5,5
output: 4

2. John works at a clothing store. He has a large pile of socks that he must pair by color for sale. Given an array of integers representing the color of each sock, determine how many pairs of socks with matching colors there are.

For example, there are n=7 socks with colors array = [1,2,1,2,1,3,2]. There is one pair of color '1' and one of color '2'. There are three odd socks left, one of each color. The number of pairs is '2'.

Create a user defined function 'sockMerchant' can take parameters:

n: the number of socks in the pile

ar: the colors of each sock

Output: It must return an integer representing the number of matching pairs of socks that are available.

The function defined should pass following test cases by returning the desired output:

5
1,1,2,2,2
output: 2
8
1,1,1,2,2,3,4,4
output: 3
12
1,2,1,3,4,2,6,3,5,2,1,5
output: 4

3. Gary is an avid hiker. He tracks his hikes meticulously, paying close attention to small details like topography. During his last hike he took exactly 'n' steps. For every step he took, he noted if it was an uphill,'U', or a downhill, 'D' step. Gary's hikes start and end at sea level and each step up or down represents a 1 unit change in altitude. We define the following terms:

A mountain is a sequence of consecutive steps above sea level, starting with a step up from sea level and ending with a step down to sea level.
A valley is a sequence of consecutive steps below sea level, starting with a step down from sea level and ending with a step up to sea level.
Given Gary's sequence of up and down steps during his last hike, find and print the number of valleys he walked through.

For example, if Gary's path is:

s = [DDUUUUDD]

He first enters a valley units deep. Then he climbs out an up onto a mountain units high. Finally, he returns to sea level and ends his hike.

Create a User Defined Function to solve this problem with the following description:

Complete the countingValleys function in the editor below. It must return an integer that denotes the number of valleys Gary traversed.

countingValleys has the following parameter(s):

s: a string describing his path
Test your function with following inputs:

UDDDUDUU
output: 1
DDUUDDUDUUUD
output: 2
UDUUUDUDDD
output: 0
DUDDDUUDUU
output: 2
DDUDDUUDUU
output: 1
