# Гайд #2

# запуск скриптов

```bash
@echo off
python start.py
pause
```

# input или "нажмите кнопку чтоб пройти дальше"

```python
input("Нажмите Enter чтоб пройти дальше")
```


# красим текст в консольке чтоб было вот так: 
![photo](assets/colorama.png)

# покраска с colorama: 

```python
from colorama import Fore, init # импортируем из библиотеки colorama init, fore

init()

print(f"{Fore.GREEN} Green Text")
```

сложение чисел с python: 

```python
one = 5 # записываем в переменную 1 число то етсь 5 

two = 10 # все тоже самое только число 10 

print(one + two)
```

вывод: 
```bash
15
```
