/*-----------------------------------------------------------------------------------------------------------------
CDS_LAB-14
LINEAR SEARCH IN PYTHON USING WHILE LOOP 
NANDANA.S.KUMAR
9-07-2024
-------------------------------------------------------------------------------------------------------------------*/

ALGORITHM:-

STEP 1:-Start: Beginning of the flowchart.
STEP 2:-Initialize i = 0: Set the starting index.
STEP 3:-Check if i < len(list): Decision point to determine if the index is within the bounds of the list.
STEP 4:-Check if list[i] == n: Decision point to check if the current element matches the target number.
Yes: Return the index i and print "Found at i".
No: Increment i and repeat the loop.
STEP 5:-End of Loop: If the loop completes without finding the number, return -1 and print "Not Found".
STEP 6:-End: End of the flowchart.








-------------------------------------------------------------------------------------------------

CODE:-

def search(list, n):
    for i in range(len(list)):
        if list[i] == n:
            return i
    else:
        return -1


list = [3,45,2,3,56,7,40,35,1,7]
n = 40

if search(list, n)!= -1:
    print("Found at ",search(list,n))
else:
    print("Not Found")
