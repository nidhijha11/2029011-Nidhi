def bubbleSort(nlist):
    for passnum in range(len(nlist)-1,0,-1):
        for i in range(passnum):
            if nlist[i]>nlist[i+1]:
                temp = nlist[i]
                nlist[i] = nlist[i+1]
                nlist[i+1] = temp

nlist = [14,46,43,27,57,41,45,21,70]
bubbleSort(nlist)
print(nlist)![Screenshot from 2021-05-27 16-46-21](https://user-images.githubusercontent.com/82803957/119817157-4221f800-bf0b-11eb-8f35-fede584fb69b.png)
