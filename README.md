# gcd of two numbers


m=int(input("enter the number,m:"))

n=int(input("enter the number,n:"))

if m<n:

    m,n=n,m

    print(m,n)

    

def gcd(m,n):

    r=m%n

    if r==0:

        return n

    else:

        return gcd(n,r)

#a=gcd(m,n)

print("the gcd is:",gcd(m,n))
