# hrudaya-spandana-Feb-28--ass1
x=[1,2,3,2,1,3,2,1,2,2]
l=[]
for i in x:
    if i not in l:
        if x.count(i)%2!=0:
            l.append(i)
print(l)
