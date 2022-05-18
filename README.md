import random

src = input('Input your source name : \n')
dest = input('Input your destination name: ')
number = random.randrange(101,200)
print('Your generated ticket is :\n')
print("airline:scr:dest:number\n")
print('AL1:',src,':',dest,':',number)
