# 15.unique-numbers-in-a-duplicate-list
n = int(input())
l = list(map(int,input().split()))
dup=0
un=0
for i in range (n):
    for j in range (i+1,n):
        if l[i]==l[j]:
            dup=dup+1
            print(l[i])
if dup==0:
    print('unique')
