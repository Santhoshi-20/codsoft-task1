# codsoft-task1
password generator
import random
letters=['a','b','c','d','e','f','g','h','i','j','k','l','m','n','o','p','q','r','s','t','u','v','w','x','y','z']
numbers=['0','1','2','3','4','5','6','7','8','9']
symbols=['!','@','#','$','%','^','*','()','-','=']
n_letters=int(input('how many letters\n'))
n_numbers=int(input('how many numbers\n'))
n_symbols=int(input('how many symbols\n'))
password=""
for i in range(1,n_letters+1):
    char=random.choice(letters)
    password+=char 
for i in range(1,n_numbers+1):
    char=random.choice(numbers)
    password+=char
for i in range(1,n_symbols+1):
    char=random.choice(symbols)
    password+=char
print(password)
