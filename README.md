l=[5,3,4,5,2,8,3,2,5,9,0,2,3]
l1=[]
for i in l:
    if i not in l1:
        l1.append(i)
for j in l1:
    if l.count(j)==1:
            print(j)
            
 Output:4
        8
        9
        0
