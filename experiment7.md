![Screenshot from 2021-05-27 16-28-49](https://user-images.githubusercontent.com/82803957/119815781-8b714800-bf09-11eb-9fa9-cb4ce32076a4.png)

def linearsearch(arr, x):
   for i in range(len(arr)):
      if arr[i] == x:
         return i
   return -1
arr = ['t','u','t','o','r','i','a','l']
x = 'a'
print("element found at index "+str(linearsearch(arr,x)))
