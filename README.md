# ds_algo
def bubble_sort(arr):
    global num
    swap = True
    while swap:
        
        swap = False
        for num in range(len(arr)-1):
            if arr[num] > arr[num+1]:
                swap = True
                arr[num] , arr[num+1] = arr[num+1], arr[num]
                #print(arr)
               
arr = [5,2,5,2,6,2,1]
bubble_sort(arr)
#for i in range(1):

print(arr)
