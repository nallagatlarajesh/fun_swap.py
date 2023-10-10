# fun_swap.py
def swap(n1,n2):
    if n1<n2:
        n1,n2=n2,n1
        return(n1,n2)
    else:
        return(n1,n2)
n1=int(input("enter the first number"))
n2=int(input("enetr second number"))
x,y=swap(n1,n2)
print("after swapping results is")
print("first number :",x)
print("seecond number is :",y)
