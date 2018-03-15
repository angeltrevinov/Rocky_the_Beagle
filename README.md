Description:

Rocky the dog, is a Beagle who loves toe at all the time. Lately, Rocky is eating too much and having too little exercise. That’s why Rocky’s owner is worried about its health and is trying to find a new way to provide Rocky with enough food and putting it in the farthest room of the house to exercise Rocky. The problem is that Rocky, as a hound dog, always finds the shortest path to get the food.

Rocky lives in a house with several rooms, sometimes the room’s doors are open and some other times they are locked. Room A is also known as Rocky’s room. For example, if Rocky’s house has five rooms and the connectivity between them is as shown in the following illustration:



Rocky would have to take 5 meters to get into room B, 4 meters to get on room C and so on. If Rocky’s food is in room E, and the idea is to make him exercise. Which path would you recommend to the owner who is trying to find the longest shortest path?

Input:

The first line of the input includes a positive integer giving the number of cases. Then for each case the code includes a positive integer n (n <= 20)   meaning the number of rooms and a positive integer k (k<=200) meaning the  number of connections between two rooms. Then the code includes k lines with 2 chars (X, Y) and a positive integer (c), meaning that the connection between X to Y and Y to X has c meters (c<=1000).

Output:

One line per case telling the longest shorest room, from room A. In case of a tie between several rooms show the lowest alphabetic room of them.

Sample Input:

2
5 7
A B 5
A C 4
A D 7
B E 3
C D 2
C E 4
D E 1
4 6
A B 1
A C 1
A D 1
B C 1
B D 1
C D  1
Sample Output:

Case 1: E
Case 2: B
