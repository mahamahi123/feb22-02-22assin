# feb22-02-22assin
Range end value 
n=int(input())
k=1
for i in range(1,n+1):
    for j in range(1,i+1):
        print(j,end=' ')
    k+=1
    print('\n')
for i in range(n-1,0,-1):
    k+=1
    for j in range(1,i+1):
        print(j,end=' ')
    print('\n')
