# calculator_v3
Простой калькулятор. Он конечно сырой, но это мой первый шаг в области программирования на Python 
print('===========Калькулятор 3.0============')
print('Я попытался сделать его максимально минималистичным')

number = int(input('Первое число: '))
number2 = int(input('Второе число: '))


full = input('Какое действие вы хотите совершить? ')


if full == '+':
    print('Сложение. Ответ:', number + number2)

if full == '-':
    print('Вычитание. Ответ: ', number - number2)

if full == '*': 
    print('Умножение. Ответ: ', number * number2 )

if full == '/':
    print('Деление. Ответ: ', number / number2)

if full == '**':
    print('Степень. Ответ: ', number ** number2)

if full == '%':
    print('Модуль. Ответ: ', number % number2 )

if full == '//':
    print('Целочислительное деление. Ответ: ', number // number2)

if full == 

else:
    print('Вы выбрали некоректное действие')
print('======ПРОГРАММА ЗАВЕРШЕНА======')


