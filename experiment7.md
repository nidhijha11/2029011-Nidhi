#linear search
def linearsearch(arr, x):
   for i in range(len(arr)):
      if arr[i] == x:
         return i
   return -1
arr = ['t','u','t','o','r','i','a','l']
x = 'a'
print("element found at index "+str(linearsearch(arr,x)))![Screenshot from 2021-05-27 16-28-49](https://user-images.githubusercontent.com/82803957/119815396-1bfb5880-bf09-11eb-9276-2d21b23fde1c.png)
