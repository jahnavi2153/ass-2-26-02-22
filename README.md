# ass-2-26-02-22
count=0
pos=0
neg=0
while(count<5):
    num=int(input('enter a number:'))
    if(num==0):
        break;
    elif(num>0):
        pos=pos+1
    else:
            neg=neg+1
            count=count+1
print("count of positive number is",pos)
print("coutn of negitive number is",neg)

output:
enter a number:26
enter a number:11
enter a number:3
enter a number:2
enter a number:0
count of positive number is 4
count of negative number is 0
