import time
from os import system
def h():
    print('_________________')
    print('| created by PSA \ ')
    print('|_________________\___________________________________________')

def pardazesh():
    global s,c,x,b
    h()

    while 1:

        print()
        x = (input('Enter the numbers:'))

        if x=='0':break
        elif x=='exit':break
        elif x=='Exit':break

        elif x == 'cls':
            system('cls')
            print()
            h()
            print()
        elif x == 'clean':
            system('cls')
            print()
            h()
            print()
        elif x == 'eraser':
            system('cls')
            print()
            h()
            print()


        else:
            s = x.split()
            c=(len(s))
            sum=0
            try:
                for i in s:
                    v=int(i)
                    sum+=v
            except:
                print()
                print('! Invalid !')
                print()
                time.sleep(1.0)
                print('______________________________________________________________')
                continue
            b=(sum / c)
            print()
            print("The answer is:",b)
            print()
            print('______________________________________________________________')


pardazesh()
