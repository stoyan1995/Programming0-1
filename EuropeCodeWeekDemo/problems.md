# Задачите, които ще решаваме по време на занятията

Всяка една задача има указания как и къде да се изпълни:

* Първите 4 части се изпълняват в интерпретатора
* За останалите ще използваме Sublime, ще записваме `.py` файлове и ще ги изпълняваме целите.

## Част първа - добрият стар калкулатор

В интерпретатора, сметнете отговора на изразите по-долу, като имате предвид следните особености:

*  `^` означава повдигане на степен
* `50% от 100` си се чете "50 процента от 100" и точно това имаме предвид.


1. Колко е `2 + 123`?
2. Колко е `2 * 2 + 213`?
3. Колко е  `10 * 9 * 8 * 7 * 6 * 5 * 4 * 3 * 2 * 1`?
4. Колко е `1 + 1 + 2 + 3 + 5 + 8 + 13`?
5. Колко е `((13.0 / 8) + (8.0 / 5) + (5.0 / 3) + (3.0 / 2)) / 4` ?
6. Колко е `2 ^ 32`?
7. Колко са `20%` от `10`?
8. Колко са `40%` от `99999`?
9. Колко са `0.1%` от `10^5`?
10. Колко е `7 / 2`?

## Част втора - променливи

### Отново сметки, този път с x, y и z

Дефинирайте три променливи, които да имат следните стойности:

* `x = 11`
* `y = 24`
* `z = 8`

В интерпретатора,  пресметнете следните изрази:

1. `4y + 16z`
2. `2z + 19x`
3. `8x - 24x`
4. `17y + 2x`
5. `9z`
6. `21y - 12x`
7. `11z`
8. `11y + 1y`
9. `25z - 21y`
10. `13y`
11. `20y`
12. `8y * 4y`
13. `12x + 20z`
14. `20x - 19z`
15. `25x`
16. `25x / (20x2)`
17. `20z * 22y`
18. `8y + 24z`
19. `11y * 16y`
20. `23z - 19x`

### Да платим сметката

Имаме следната ситуация: Иван, Мария, Пешо и Ина са излезли на вечеря и е дошло време да плащат сметката.

Ако знаем, че сметката е 50 лв, а бакшишът е 15% от сметката и:

* Сметката на Иван е 15 лв.
* Сметката на Мария е 15 лв.
* Сметката на Пешо е  10 лв.

**Използвайки променливи в интерпрератора на Python, намерете следните суми:**

* Заедно с бакшиша, колко е общата сметка?
* Колко е сметката на Ина?
* Ако всички ще си разделят бакшиша по равно, по колко трябва да плати всеки?

### От 1 до 10

Имате променливата `x = 1`

Напишете 10 израза в REPL-то, така че `x` да придобие стойност `10`.

Подксазка: `x = x + 1`

## Част трета - как да пишем текст? Низове.

### Как се казваш?

Използвайки променливи в Python, направете:

* Променлива `first_name`, която да държи първото ти име
* Променлива `middle_name`, за бащиното име
* Променлива `family_name`, за фамилията

Използвайки тези 3 променливи, напишете такъв израз, който да изкара цял низ, съдържаш 3те имена, с разстояние между тях.

Например, ако имаме:

```python
first_name = "Radoslav"
middle_name = "Yordanov"
family_name = "Georgiev"
```

То резултатът накрая трябва да бъде:

```python
"Radoslav Yordanov Georgiev"
```

### Колко букви има в следните изрази?

Използвайки интерпретатора на Python и вградената функция `len`, намерете колко букви има в следните изрази:

* `чичковите червенотиквеничковчета`
* `Непротивоконституционствувателствувайте`
* `Python е швейцарско ножче в езиците за програмиране`

**Внимавайте за празните разстояния. Те не са букви!**

### Операции между низове и числа.

В интерпретатора на Python, напишете следните изрази. Преди да ги напишете, предположете какъв би бил резултатът:

* `"Python" + 3`
* `"Python" - 3`
* `"Python" * 3`
* `"Python" * "Python"`
* `"1" + 1`
* `"Python" + "Python"`
* `"1" + str(1)`

`str` е функция, която превръща числата в низове.

### Текст на песен

Имаме следните променливи, които държат ред по ред на текстът на една песен:

```python
line_1 = "The pictures tell the story"
line_2 = "This life has many shades"
line_3 = "I’d wake up every morning and before I’d start each day"
line_4 = "I’d take a drag from last nights cigarette"
line_5 = "That smoldered in it’s tray"
line_6 = "Down a little something and then be on my way"
line_7 = "I traveled far and wide"
line_8 = "And laid this head in many ports"
line_9 = "I was guided by a compass"
line_10 = "I saw beauty to the north"
line_11 = "I drew the tales of many lives"
line_12 = "And wore the faces of my own"
line_13 = "I had these memories all around me"
line_14 = "So I wouldn’t be alone"
line_15 = "Some may be from showing up"
line_16 = "Others are from growing up"
line_17 = "Sometimes I was so messed up and didn’t have a clue"
line_18 = "I ain’t winning no one over"
line_19 = "I wear it just for you"
line_20 = "I’ve got your name written here"
line_21 = "In a rose tattoo"
```

Задачата е следната: целият текст трябва да се конкатенира в променлива, която се казва `rose_tattoo_text`.
Между всеки два реда в текста, трябва да има специалния символ за нов ред - `"\n"`

Използвайте следните операции:

```python
text = ""
text = text + "Newly append text"
text = text + "\n"
text = text + "More appended text"
print(text)
```

За да видите резултатът накрая, напишете следния код в интерпретатора: `print(rose_tattoo_text)`


## Част четвърта. Истина и Лъжа.

В интерпретатора на Python, вижте на какво са равни следните изрази:

* `"1" == "1"`
* `"1" == 1`
* `"1" != 1`
* `1 != 1`
* `1 == 1`
* `1 > "1"`
* `2 < 10`
* `1 <= "1"`
* `1 >= "1"`
* `True == False`
* `True == True`
* `False == 0`
* `False == ""`
* `"python" == "Python"`
* `"Python" in "Python is an awesome language!"`
* `1 in [1, 2, 3]`
* `True`
* `False`

## Част пета. Повече от 1 ред код. Вход / Изход и print("Hello!")

Тук ще използваме Sublime и ще решаваме задачи, които взимат решения.

Ще трябва да добавим Python в променливите на средата - envinroment variables.
Това е магия и ще ви покажем как!

### Hello Python!

Във файл, който се казва `hello.py`, напишете следния код:

```python
print("Hello Python!")
print("Nice to meet you!")
```

Запишете файла, в папка, която се казва `code`, след което отидете чрез конзолата до нея и напишете:

```
$ python hello.py
```

### Текст на песен

Във файла `song.py` напишете такъв код, който да принтира текста на песента от задачата по-горе (Rose Tattoo)

### Is it friday yet?

По идея на сайта http://isitfriday.org/

Във файла `friday.py` (създайте си го) имаме следното парче код:

```python
import time

today = time.strftime("%A")

print(today)

```

Имате следните задачи:

1. Изпълнете програмата, за да видите резултатът.
2. Допишете програмата по следния начин:

* Ако днес сме петък, програмата трябва да принти `"IT'S FRIDAY!"`
* Ако не сме петък, програмата трябва да принтира `"No, today is <current day>"`
* `<current day>` трябва да е string за днешния ден - Например `"Sunday"`

### Програма, която чете число и го връща на квадрат

Използвайки следният факт:

```python
n = input("Enter number")
print(n)
```

Напишете програма `square.py`, която чете число от потребителя и го принтира на квадрат.

### Програма, която чете две числа и ги събира.

Напишете програма `sum.py`, която чете две числа от потребителя и принтира тяхната сума.

### HTTP или HTTPS?

Знаем, че не е хубаво да си даваме потребителско име и парола на сайтове, които не са https.

Напишете програма - `trust.py`, която чете от потребителя URL към сайт и проверява дали URL-a е `"http"` или `"https"`.

Ако дадения URL е HTTP, изпишете: `"Внимавай! Не се логвай там"`, иначе изпишете: `"Нека криптографията бъде с теб!"`

Примери:

* `"https://hackbulgaria.com/"`
* `"http://www.dir.bg/"`
