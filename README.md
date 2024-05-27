# Bubblesort
For O/A Level. Bubble sort using two nested loops with comparisions
#Bubble Sort
myArr=[23,45,12,9,7,6,2,1]
def BubbleSort(myArr):
    n=len(myArr)
    for i in range(n-1):
        for j in range(0,n-i-1):
            if myArr[j]>myArr[j+1]:
                myArr[j],myArr[j+1]=myArr[j+1],myArr[j]

BubbleSort(myArr)

print('Sorted Array is: ')
for i in range(len(myArr)):
    print('%d'%myArr[i])
