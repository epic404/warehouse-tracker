Given two arrays, box[] and truck[], where box[i] represents the weight of the ith box and truck[i] represents the maximum load that the ith truck can carry. Now each truck takes 1 hour to transport a box from source to destination and another one hour to come back. Now, given that all the boxes are kept at the source, the task is to find the minimum time required to transport all the boxes from the source to the destination. 

Note that there will always be some time in which the boxes can be transported and only a single box can be carried by truck at any instance of time.

Examples:  

Input: box[] = {7, 6, 5, 4, 3}, truck[] = {10, 3} 
Output: 7 
1st hour: truck[0] carries box[0] and truck[1] carries box[4] 
2nd hour: Both trucks are back at the source location. 
Now, truck[1] cannot carry anymore boxes as all the remaining boxes 
have weights more than the capacity of a truck[1]. 
So, truck[0] will carry box[1] and box[2] 
in a total of four hours. (source-destination and then destination-source) 
And finally, box[3] will take another hour to reach the destination. 
So, total time taken = 2 + 4 + 1 = 7


Input: box[] = {10, 2, 16, 19}, truck[] = {29, 25} 
Output: 3
