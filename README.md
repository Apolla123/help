print('Добро пожаловать в интернет-банк!')
print('У нас фантастические процентные ставки!')
print('Для вкладов до 10 тысяч ₽ включительно прибыль составит 10%,')
print('для вкладов на сумму до 100 тысяч включительно - 20%,')
print('для более 100 тысяч - 30%!')
print('На какую сумму желаете сделать вклад?')
mo = float(input())
if mo <= 10000.0:
    mo *= 1.1
elif mo <= 100000.0:
    mo *= 1.2
elif mo >= 100000.0:
    mo *= 1.3
print('Вы получаете', mo, '₽, поздравляем!')
