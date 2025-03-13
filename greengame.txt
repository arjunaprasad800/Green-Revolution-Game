#Basic need of the budget (**inputs)
D= int(input())
R = int(input())
T = int(input())
TM[t]= map(int,input().split())
TX[t]=map(int,input().split())
TR[t]= map(int,input().split())
RI[r]= map(int,input().split())
RA[r]= map(int,input().split())
RP[r]=map(int,input().split()) 
RM[r]=map(int,input().split()) 
RT[r]=map(int,input().split()) 
RE=map(int,input().split())


#whole program
if TM[t]%n == 0:
    print(" profit is not acquired")
else:
    profit = min(n, TX[t])*TR[t]
    #print(profit)
    RU[r] =int(input())
    greenmaxnumberofbuildings = (RU[r]*profit)/100 # increases the number of buildings powered by the facilities by a percentage.
    nonprofit=(RU[r]*profit)/100
    if nonprofit%n==0:
        print(nonprofit, "nongreennumberofbuildings")
        print(greenmaxnumberofbuildings-nonprofit)
        print((profit)/100) #: increases by a percentage the minimum (TM) and maximum (TX) thresholds of buildings that can be powered.
        print(((profit)/100)-(1/100))
        print(((profit)/100)+(1/100))
        RL[r]= (((profit)/100)+(1/100))
        print(RL[r]-(1/100))
        RW[r]= int(input())
        print(((RW[r]*profit)/100))
        if nonprofit%n==0:
            print(((profit)/100)-(1/100))
            E = TM[t]-n-TX[t] #virtual store
    RU[r] = RU[r]+RE*RU[r]+RE*RU[r]
    if RI[r] <RA[r]:
        print("invalid")
    else:
        print("valid")
    periodic_cost = R[P]*R[U]
    max_profit = (RU[r]*profit)*100
    budgetupdate= (max_profit)-(RP[r]/100)
    score = max_profit
    print(score)



