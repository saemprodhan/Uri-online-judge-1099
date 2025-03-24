# Uri-online-judge-1099
Sum of Consecutive Odd Numbers II
number = int(input())
for i in range(number):
    x,y = map(int,input().split())
    count = 0
    if x>y:
        x,y=y,x
    for j in range(x+1,y):
        if j%2!=0:
            count += j
    print(count)
