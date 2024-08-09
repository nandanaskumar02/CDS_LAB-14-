/*---------------------------------------------------------------------
CDS_LAB-14
LINEAR SEARCH IN PYTHON USING WHILE LOOP 
NANDANA.S.KUMAR
9-07-2024
------------------------------------------------------------------------*/
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
