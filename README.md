# ChefAndContest
# cook your dish here
t=int(input())
while t:
    x,y,p,q=map(int,input().split())
    a=x+(10*p)
    b=y+(10*q)
    if(a<b):
        print("Chef")
    elif(b<a):
        print("Chefina")
    else:
        print("Draw")
    t-=1
