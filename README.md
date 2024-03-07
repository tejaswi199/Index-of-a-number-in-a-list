#Approach-1
n=int(input())
a=list(map(int,input().split()))
print(a)
x=int(input())
if x in a:
    print(a.index(x))
   
#Approach-2
n=int(input())
a=list(map(int,input().split()))
print(a)
x=int(input())
res="none"
for i in range(n):
  if x==a[i]:
    res=i
if(res=="none"):
  print("Element  not found")
else:
  print(res)

#Approach-3
n=int(input())
a=list(map(int,input().split()))
print(a)
x=int(input())
for i in range(n):
  if x==a[i]:
    print(i)
    break
else:
  print("Element not found")
