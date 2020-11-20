# Root-Problem
num=int(input('Enter a perfect square or cube:'))
root=2
pwr=1
power=1

while (root ** power !=num):
    
    while (root ** pwr!= num and pwr<7):

        power=pwr
        pwr+=1
        

    root+=1
    pwr=1

    
if (root**power == num):
    print ('Root is ', root, 'Power :', power)
else:
    print ('Problem')
