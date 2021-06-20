# Program-to-print-all-prime-numbers-between-0-and-999-in-python
for x in range(1,999):
    prime= True
    for y in range(2,x):
if (x%y) == 0:
            prime= False
    if prime==True:
print(x)
