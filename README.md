# Modul-1
# 1. Напишите код, который создает переменную `name` и присваивает ей строковое значение. Затем выведите значение переменной на экран.
name = "Shaxzod'
print(name)
# 2. Создайте список из трех элементов и измените второй элемент на новое значение. Напечатайте измененный список.
moshinalar = ['kobalt','BYD Song','matiz']
moshinalar[1] = 'damas'
print(moshinalar)
# 3. Напишите код, который вычисляет сумму двух чисел и выводит результат на экран.
a = int(input('birinchi sonni kiriting  '))
b = int(input('ikkinchi sonni kiriting  '))
c = a+b
print('sonlar yigindisi', c)
#4. Создайте строку и используйте метод `.replace()` для замены определенного слова на другое.
matn = 'Python dasturlash tilini ozlashtirish korsatkichi'
matn_new = matn.replace('ozlashtirish','ozlashtiraolmaslik')
print(matn_new)
#5. Напишите функцию, которая принимает два числа и возвращает их произведение.
def multiply(a, b):
    return a * b

result = multiply(4, 5)
print(result)
#6. Используя цикл `for`, создайте код, который выводит числа от 1 до 10 на одной строке, разделенные пробелом.
sonlar = list(range(1,11))
for son in sonlar:
    print(son, end=' ')
#7. Напишите код, который создает словарь с тремя ключами и значениями, и затем изменяет значение одного из ключей.
car_0 = {'model':'malibu','matori':1.5}
car_0['matori'] = 1.8
print(car_0)
#8. Создайте кортеж с 4 элементами и напечатайте его длину.
car_0 = ['matiz','damas','tiko','malibu']
uzunlik = len(car_0)
print(uzunlik)
#9. Используя цикл `while`, напишите код, который выводит числа от 10 до 1 в обратном порядке.
son = 10
while son >= 1:
    print(son, end= ' ')
    son = son - 1
#

