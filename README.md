# stake-demo
L = []
while True:
    C = int(input('''
        1 push element
        2 pop element
        3 peek elements
        4 display stack
        5 Exit 
                  
        '''))
    if C==1:
        n=int(input("enter value:-"))
        L.append(n)
        print(L)

    elif C==2:
        if len(L)==0:
            print("empty stack") 
        else:
            p=L.pop
            print(p)
            print(L)

    elif C==3:
        if len(L)==0:
            print("empty stack") 
        else:
            print("last stack value:-", L[-1])

    elif C==4:
        print("diplay stack:-",L)  

    elif C==5:
        break;         
    else:
        print("invalid opr......")
