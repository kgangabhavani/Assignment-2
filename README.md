# Assignment-2(18-02-22)
to print sum of n factorial number
def factorial(num):
    fact=1
    while(num>0):
        fact=fact*num
        num=num-1
    return(fact)
n=int(input("Enter Value of n : "))
sum=0
for a in range(1,n+1):
    sum=sum+factorial(a)
print("Sum of Factorials : ",sum)


input:
Enter Value of n:5
output:
Sum of Factorials :153
