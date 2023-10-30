# informatika8

#Домашние работы Ника Кенякина (8Л)
#а)

num = input("Введите трехзначное число: ")
sum = 0
product = 1
for digit in num:
    sum += int(digit)
    product *= int(digit)

print("Сумма цифр:", sum)

#б)

num = int(input("36: ")) 
i = 1 
print("1, 2, 3, 4, 6, 12, 18", num, ":") 
while i <= num: 
    if num % i == 0: 
        print(i) 
    i += 1

#2

num = int(input("Введите натуральное число: ")) 
i = 1 
print("Делители числа", num, ":") 
while i <= num: 
    if num % i == 0: 
        print(i) 
    i += 1
