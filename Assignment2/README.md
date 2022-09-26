Operations
1) print(5/2)
print(5.0/2.0)
The values are the same

2) Modulo operator takes the remainder of the answer: 
7%2
1

3) print(2**2)
4 
** is exponents

5) print(2//1).  // is integer division, / is float division
6)print(1+2+3*4/5)=5.4. python follows order of operations 

Variables
2. Variables show up in variable editor
4. It doesn't have a problem with them being the same name
5.The value doesn't depend on the variable (X doesn't equal K)
6. No because changing 1 to Z doesn't change it- L stays the same

Booleans
1) They are different values with the quotations surrounding them
2) print(5==(3+2))
True, it is equivalent

3) print(1==1.0 and not "1"=="1.0" and 5==(3+2))
True
print(1 == 1.0 or "1" == "1.0" and 5 ==(3+2))
True
print(1==1.0 or "1" =="1.0" or 5 ==(3+2))
True
print (1==1.0 and not "1" == "1.0" or 5==(3+2))
True
print (not 1==1.0 and not "1" == "1.0" or 5==(3+2))
True

List
oddlist= [1,3,5,7,9]

print(oddlist)
[1, 3, 5, 7, 9]

3) Len=how many numbers are in the list total
print(len(oddlist)) 

4) print(type(oddlist))
<class 'list'>
Type=class is list type

5) intlist=list(range(0,101))
6) print(intlist)
[0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21,
 22, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 36, 37, 38, 39, 40, 
 41, 42, 43, 44, 45, 46, 47, 48, 49, 50, 51, 52, 53, 54, 55, 56, 57, 58, 59, 
 60, 61, 62, 63, 64, 65, 66, 67, 68, 69, 70, 71, 72, 73, 74, 75, 76, 77, 78, 
 79, 80, 81, 82, 83, 84, 85, 86, 87, 88, 89, 90, 91, 92, 93, 94, 95, 96, 97, 
 98, 99, 100]

 
Dictionary
about_me = {'name': 'Lorilyn', 'age': 21.0, 'year': 4, 'food': ['sushi', 'pizza', 'salad', 'strawberrycake']}

print(about_me)
{'name': 'Lorilyn', 'age': 21.0, 'year': 4, 'food': ['sushi', 'pizza', 'salad', 'strawberrycake']}

print(type(about_me))
<class 'dict'>

print(len(about_me))
4= Length determined by the number of string categories

Array
1) mixnums = numpy.array([1,2,3,4.0,5.0,6.0])
print(mixnums)
[1. 2. 3. 4. 5. 6.]
When combining everything it converts to decimal points

2) mixtypes=numpy.array([1,2,3.0,4.0,'5','6'])
print(mixtypes)
['1' '2' '3.0' '4.0' '5' '6'] #follows with or without decimal points- in either integer or float format with quotation marks 

3) print(np.arange(1,100,2))
[ 1  3  5  7  9 11 13 15 17 19 21 23 25 27 29 31 33 35 37 39 41 43 45 47
 49 51 53 55 57 59 61 63 65 67 69 71 73 75 77 79 81 83 85 87 89 91 93 95
 97 99]

4) print(np.linspace(1,5,16))
[1.         1.26666667 1.53333333 1.8        2.06666667 2.33333333
 2.6        2.86666667 3.13333333 3.4        3.66666667 3.93333333
 4.2        4.46666667 4.73333333 5.        ]

