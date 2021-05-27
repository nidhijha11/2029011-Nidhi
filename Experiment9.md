def selectionSort( itemsList ):
    n = len( itemsList )
    for i in range( n - 1 ): 
        minValueIndex = i

        for j in range( i + 1, n ):
            if itemsList[j] < itemsList[minValueIndex] :
                minValueIndex = j

        if minValueIndex != i :
            temp = itemsList[i]
            itemsList[i] = itemsList[minValueIndex]
            itemsList[minValueIndex] = temp

    return itemsList


el = [21,6,9,33,3]

print(selectionSort(el))![Screenshot from 2021-05-27 16-55-03](https://user-images.githubusercontent.com/82803957/119818128-72b66180-bf0c-11eb-8fd3-40ad0bbb118f.png)
