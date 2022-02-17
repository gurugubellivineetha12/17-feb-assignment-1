n=int(input("enter n value:"))
sum=0
for i in range (1,n+1):
    if i%2==0 :
        sum=sum+i
print("sum of even numbers",sum)
add=0
for i in range (1,n+1):
    if i%2==1:
        add=add+i
print("sum of odd numbers:",add)
