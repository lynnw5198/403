This is my assignment 3

Variable operations
sub_code='sub'
sub_int='2'
subnr_str='2'

print(sub_code+sub_int)
print(sub_code+subnr_str)

subnr_str='"2"'
print(sub_code+subnr_str)
#Only subnr_str can be added to sub_code because it is a float and not an integer 

2.
print(sub_code+" "+sub_int)
#sub 2
print(sub_code+" "+sub_int+sub_int+sub_int)
#sub 222
print((sub_code+sub_int)*3)
#sub2sub2sub2
print(sub_code+sub_code+sub_code+sub_int+sub_int+sub_int)
#subsubsub222

LIST EXERCISE
numlist='[1,2,3]'
print(numlist*2)
#[1,2,3][1,2,3]

import numpy as np
numarr=np.array[1,2,3]
print((numarr)*2)
#UNABLE TO DO

#exercise3
strlist=['do','re','mi','fa']
print(strlist*2)
#['do', 're', 'mi', 'fa', 'do', 're', 'mi', 'fa']

print([strlist[0]*2,strlist[1]*2,strlist[2]*2,strlist[3]*2])
#['dodo', 'rere', 'mimi', 'fafa']

imgs_F=['face1.png','face2.png','face3.png','face4.png','face5.png']
imgs_H=['house1.png','house2.png','house3.png','house4.png','house5.png']
cues=['cue1','cue2']*5 

ZIPPING EXERCISE
facehouse=list(zip(imgs_F,imgs_H,cues))
print(facehouse)
#[('face1.png', 'house1.png', 'cue1'), ('face2.png', 'house2.png', 'cue2'), ('face3.png', 'house3.png', 'cue1'), ('face4.png', 'house4.png', 'cue2'), ('face5.png', 'house5.png', 'cue1')]

SLICING EXERCISE
list100=range(100)
#print(list100)
#list100=range(0,101)
#print(list(list100))

#1
list100=list(range(0,101))
print(list100)
#[0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 36, 37, 38, 39, 40, 41, 42, 43, 44, 45, 46, 47, 48, 49, 50, 51, 52, 53, 54, 55, 56, 57, 58, 59, 60, 61, 62, 63, 64, 65, 66, 67, 68, 69, 70, 71, 72, 73, 74, 75, 76, 77, 78, 79, 80, 81, 82, 83, 84, 85, 86, 87, 88, 89, 90, 91, 92, 93, 94, 95, 96, 97, 98, 99, 100]

print(list100[:11])
#[0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

print(list100[99::-2])
#[99, 97, 95, 93, 91, 89, 87, 85, 83, 81, 79, 77, 75, 73, 71, 69, 67, 65, 63, 61, 59, 57, 55, 53, 51, 49, 47, 45, 43, 41, 39, 37, 35, 33, 31, 29, 27, 25, 23, 21, 19, 17, 15, 13, 11, 9, 7, 5, 3, 1]

print(list100[-97:])
#[4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 36, 37, 38, 39, 40, 41, 42, 43, 44, 45, 46, 47, 48, 49, 50, 51, 52, 53, 54, 55, 56, 57, 58, 59, 60, 61, 62, 63, 64, 65, 66, 67, 68, 69, 70, 71, 72, 73, 74, 75, 76, 77, 78, 79, 80, 81, 82, 83, 84, 85, 86, 87, 88, 89, 90, 91, 92, 93, 94, 95, 96, 97, 98, 99, 100]


#4 
print(list100[-4:]) 
#[97, 98, 99, 100]

#print(list100[:-4])
#print(list100[::-4])
#print(list100[:-4:])
#print(list100[100:-4]). []

#5
print(list100[39:44]==[39,40,41,42,43])
#True
