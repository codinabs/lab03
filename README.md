ЗАДАНИЕ №1
print(len(input()))
(# данная строка выполняет след. действи: 1) ввод строчных данных, 2) подсчет количества символов литерала, 3) вывод)

ЗАДАНИЕ №2
print('Дараев Станислав Русланович', 'Р20Б1', '09.01.2002', sep='\n')

ЗАДАНИЕ №3
print('г. Курган', 'Добыча урана', 'Грустные лица', sep='\n')

ЗАДАНИЕ №4
print('23.06.1941')
print('Румыния', 'Италия', 'Венгрия', 'Финлядния', 'Хорватия', sep=', ')
print()
print('09.06.1945')
print()
print('СССР')

ЗАДАНИЕ №5
input('напишите, что вы думаете про такого-то человека')

ЗАДАНИЕ №6
while True:
    a = input()
    if a == 'stop it!':
        print(':(')
    else:
        print(':)')
        
ЗАДАНИЕ №7
print('|      ДИСЦИПЛИНА      ', 'ОЦЕНКА|', sep='|')
print('|ЯЗЫКИ ПРОГРАММИРОВАНИЯ', '   5  |', sep='|')

ЗАДАНИЕ №8
a, b, c = 'САНЯ', 'ВАНЯ', 'ЖОРА'
print(f'{a} + {b} + {c} любим анжуматься')

ЗАДАНИЕ №9
orange_stocks = 1051
print('Запасы апельсин на складе:', orange_stocks)
        
Доп задание : 

apt install python3.8

cd/home

touch hel.py

vim hel.py

IN VIM: press i to go to insert mode
then add code : print('23.06.1941');print('Румыния', 'Италия', 'Венгрия', 'Финлядния', 'Хорватия', sep=', ');print ();print('09.06.1945');print();print('СССР')
then press esc button and type :wq to save script.

chmod 777 hel.py

python 3.8 hel.py        



