print("prime numbers between:")
lower=int(input("lower"))
upper=int(input("upper"))
for n in range(lower,upper+1):
    if n>1:
        for i in range(2,n):
            if(n%i) ==0:
                break

        else:
            print(n)
