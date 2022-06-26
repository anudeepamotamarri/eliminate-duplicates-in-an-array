# eliminate-duplicates-in-an-array 
print("Hello world")
n=int(input())
l=[]
for i in range(0,n):
    l.append(int(input()))
for i in range(0,n):
    for j in range(i+1,n):
        if(l[i]==l[j]):
            print(l[j],end=" ")
