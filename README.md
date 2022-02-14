n=int(input('enter number:'))
total=0
while(n>0):
    dig=n%10
    total=total+dig
    n=n//10
print("the total sum of digits is:",total)

output:
enter number:123
the total sum of digits is:6
