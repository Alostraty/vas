# 2 ТИП

## 1

```

```

# 8 ТИП

## 1
Все 5-⁠буквенные слова, составленные из букв В, И, Н, Т, записаны в алфавитном порядке и пронумерованы. Вот начало списка:
##### 1.ВВВВВ
##### 2.ВВВВИ
##### 3.ВВВВН
##### 4.ВВВВТ
##### 5.ВВВИВ
Запишите слово, которое стоит под номером 1019.
```
from itertools import *
number = 1
for i in product("ВИНТ", repeat=5):
    print(number, i)
    number += 1
```
ЛИБО, чтобы точно выдал номер (1019), остальные нет
```
from itertools import *
number = 1
for i in product("ВИНТ", repeat=5):
    if number == 1019:
        print(number, i)
    number += 1
```
Ответ: ТТТНН

## 2

```
i1 = 'ЯРОСЛАВ'
count = 0
for Я in i1:
    for Р in i1:
        for О in i1:
            for С in i1:
                for Л in i1:
                    for А in i1:
                        for В in i1:
                            i = Я + Р + О + С + Л + А + В
                            if i.count('Я') <= 1 and i.count('Р') <= 1 and i.count('О') <= 1 and i.count('С') <= 1 and i.count('Л') <= 1 and i.count('А') <= 1 and i.count('В') <= 1 and i.count('Р') + i.count('С') + i.count('Л') + i.count('В') > i.count('Я') + i.count('О') + i.count('А') and i.count('ЯО') == 0 and i.count('ЯА') == 0 and i.count('ОА') == 0 and i.count('ОЯ') == 0 and i.count('АЯ') == 0 and i.count('АО') == 0:
                                count += 1
print(count, i)
```
Ответ:
## 3
уцкуепукпкупукпкупукпкупу
```
from itertools import *
count = 0
for i in product("1234", repeat=5):
    if i.count("1") == 2:
        count += 1
    print(count)
```
Ответ:
## 4

```

```
Ответ:
## 5

```

```
Ответ:
## 6

```

```
Ответ:
## 7

```

```
Ответ:
## 8

```

```
Ответ:
## 9

```

```
Ответ:

# 12 ТИП

## 1
## 2


