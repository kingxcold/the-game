# the-game
sum=0
while True:
    x=int(input("P1:"))
    if x>10:
        print("error")
        break
    else:
        sum=sum+x
        print("sum:",sum)
    if sum==100:
        print("Player1 wins")
        break
    if sum>100:
        print("Player1 wins")
        break
    y=int(input("P2:"))
    if y>10:
        print("error")
        break
    else:
        sum=sum+y
        print("sum",sum)
    if sum==100:
        print("Player2 wins")
        break
    if sum>100:
        print("Player2 wins")
        break
        
