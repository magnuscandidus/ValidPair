# ValidPair
# cook your dish here
a,b,c=map(int,input().split())
if(a==b or b==c or c==a or a==b==c):
    print("yes")
else:
    print("no")
