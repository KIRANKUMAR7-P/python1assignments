# STRINGASSIGNMENT

1. Write a python program to convert a string to lower case

p="KIRANKUMAR"
p.lower()


     
'kirankumar'
2. Write a python program to convert only odd indexed characters to lower case

a="INNOMATICS LABS"
b= []
for i in range(len(a)):
 if i % 2==0:
     b.append(a[i].lower())

 else:
      b.append(a[i].upper())

print( b)


     
iNnOmAtIcS LaBs
3. Write a python program to convert only even indexed characters to lower case

a="INNOMATICS LABS"
b= []
for i in range(len(a)):
 if i %2!=0:
     b.append(a[i].lower())

 else:
     b.append(a[i].upper())

print( b)


     
InNoMaTiCs lAbS
4. Write a python program to convert only odd indexed characters to upper case

a="INNOMATICS LABS"
b=[]
for i in range(len(a)):
 if i % 2==0:
     b.append(a[i].upper())
 else:
     b.append(a[i].lower())

print( b)


     
InNoMaTiCs lAbS
5. Write a python program to convert only even indexed characters to upper case

a="INNOMATICS LABS"
b=[]
for i in range(len(a)):
 if i %2!=0:
     b.append(a[i].upper())
 else:
     b.append(a[i].lower())

print( b)


     
['i', 'N', 'n', 'O', 'm', 'A', 't', 'I', 'c', 'S', ' ', 'L', 'a', 'B', 's']
6. Write a python program where you have different variable which contains your name, gender, age, phone number, father’s name and mother’s name. And byusing this variable create a variable named bio-data where you will use all this variable

a="kirankumar"
b="male"
c=25
d=8247431205
e="Sujeeva rao"
f="meri"
bio_data=print("My name is {}, My age is {},My phone-no is {},my father’s name is {} ,and my mother’s name is {}".format(a,c,d,e,f))


     
My name is kirankumar, My age is 25,My phone-no is 8247431205,my father’s name is Sujeeva rao ,and my mother’s name is meri
7. Write a python program to count how many times “@” occurred

k="k@I@R@A@N K@U@M@A@R"
print(k)
o=k.count("@")
print("no of  count value:",o)


     
k@I@R@A@N K@U@M@A@R
no of  count value: 8
8. Write a python program to get only names from the string

k1=input(" enter the 1st email: ")
k2=input(" enter the 2nd email: ")
k3=input(" enter the 3rd email: ")
a=k1.split("@")
b=k2.split("@")
c=k3.split("@")
print(a[0],b[0],c[0],sep=',')


     
 enter the 1st email: saimaruthi388@gmail.com
 enter the 2nd email: admin@yourstore.com
 enter the 3rd email: kkassociates129@gmail.com
saimaruthi388,admin,kkassociates129
9. Write a program to remove vowels from the entire alphabets

text = input("Enter String: ")

vowels = ['a', 'e', 'i', 'o', 'u', 'A', 'E', 'I', 'O', 'U']
newtext = ""

for c in text:
    if c not in vowels:
        newtext = newtext + c
text = newtext
print("\nWithout Vowels =", text)


     
Enter String: abcdefghiklmnopqrstuvwxyz

Without Vowels = bcdfghklmnpqrstvwxyz
10. Find all occurrences of a substring in a given string by ignoring the case

str1="Welcome to Innomatics.innomatics"
str1=str1.lower()
sub_string="innomatics"
count=str1.count(sub_string)
print("the count repated words:",count)


     
the count repated words: 2

 


     
