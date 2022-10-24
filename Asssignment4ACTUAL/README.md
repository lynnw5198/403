
# Assignment4
response='1'

if response == '1' or response == '2':
    if response == '1':
        print('correct')

    if response == '2':
        print('incorrect')


elif response == 'NaN':
        print('subject did not respond')

else:
    print('subject pressed the wrong key')
    
#correct

response='2'
if response == '1' or response == '2':
    if response == '1':
        print('correct')

    if response == '2':
        print('incorrect')


elif response == 'NaN':
        print('subject did not respond')

else:
    print('subject pressed the wrong key')
#incorrect

response='5'
if response == '1' or response == '2':
    if response == '1':
        print('correct')

    if response == '2':
        print('incorrect')


elif response == 'NaN':
        print('subject did not respond')

else:
    print('subject pressed the wrong key')
#subject pressed the wrong key

response='NaN'
if response == '1' or response == '2':
    if response == '1':
        print('correct')

    if response == '2':
        print('incorrect')


elif response == 'NaN':
        print('subject did not respond')

else:
    print('subject pressed the wrong key')
#subject did not respond


LOOP

myname='Lorilyn'

counter = -1
for letter in myname:
    counter=counter+1 #increase value by one 
    print(letter)
    print(counter) 

L
0
o
1
r
2
i
3
l
4
y
5
n
6

#3
names=['Amy','Rory','River']

for name in names:
   lettercounter=-1
   print(name)
   for letter in name:
       lettercounter = lettercounter +1
       print(letter)
       print(lettercounter)


Amy
A
0
m
1
y
2
Rory
R
0
o
1
r
2
y
3
River
R
0
i
1
v
2
e
3
r
4

iteration-0
while iteration<20:
    if iteration <10:
        print('%i, image1.png' %iteration)
        
    elif iteration <20:
        print('%i, image2.png' %iteration)
    iteration=iteration+1
    
import random
response=''
looping=True
failsafe=0
while looping:
    response=random.randint(0,10)
    print(response)
    print('this is an image')
    failsafe=failsafe+1
    
    if response ==1 or response ==2 or failsafe ==5:
        looping= False
    
    
