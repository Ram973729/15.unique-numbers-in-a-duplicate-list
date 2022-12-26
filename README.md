# 15.unique-numbers-in-a-duplicate-list
n = int(input())
l = list(map(int,input().split()))
print('Unique numbers are:')
for i in range(n):
    a=0
    for j in range(n):
        if l[i]==l[j]:
            a=a+1
    if a==1:
        print(l[i])

