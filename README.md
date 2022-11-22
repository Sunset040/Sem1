# Sem1

# # Task 1
# day = int(input("Введите число дня недели от 1 до 7: "))
#
# if day > 0 and day <= 5:
#     print("Рабочий день")
# elif day > 0 and day < 8:
#     print("Выходной")
# else:
#     print("Нет такого дня недели")



# # Task 2
# x = int(input('Введите число x: '))
# y = int(input('Введите число y: '))
# z = int(input('Введите число z: '))
#
# a = x * y * z
# b = x + y + z
#
# if a > 0:
#     a = 0
# elif a < 1:
#     a = 1
#
# if b > 0:
#     b = 1
# elif b < 1:
#     b = 1
#
# print(a == b)



# # Task 3
# x = int(input('Введите число x: '))
# y = int(input('Введите число y: '))
#
# if x > 0 and y > 0:
#     print("1")
# elif x < 0 and y > 0:
#     print("2")
# elif x < 0 and y < 0:
#     print("3")
# elif x > 0 and y < 0:
#     print("4")
# else:
#     print("Неверное значения для X ли Y")



# Task 4
# num = int(input('Введите номер четверти: '))
#
# if num == 1:
#     print("X > 0 / Y > 0")
# elif num == 2:
#     print("X < 0 / Y > 0")
# elif num == 3:
#     print("X < 0 / Y < 0")
# elif num == 4:
#     print("X > 0 / Y < 0")
# else:
#     print("Не существует номера заданной четверти")


# Task 5
aX = int(input('Введите данные для точки A(x): '))
aY = int(input('Введите данные для точки A(y): '))
bX = int(input('Введите данные для точки B(x): '))
bY = int(input('Введите данные для точки B(y): '))

result = ((bX - aX)**2 + (bY - aY)**2) ** 0.5
print(result)
