# LockoutDraws
# cook your dish here
t=int(input())
while t:
    a=list(map(int,input().split()))
    a.sort()
    if a[0]+a[1]==a[2]:
        print("YES")
    else:
        print("NO")
    t-=1
