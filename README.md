#Write a program to create a new string made of an input string’s first, middle, and last character

strg=input('enter the string')

s=0
i=0
for i in strg:
    s=s+1
x=s//2
print('string’s first, middle, and last character',strg[0:s:x])

#2nd method

x=len(str)
print('first, middle, and last character',str[0],str[x//2],str[-1])
