## my_game.py - игра, в которой перемещаясь по полю 4 на 4 необходимо "придавить" всех хомяков. 

1. После запуска игры отображается поле с метками хомяков (1, 2, 3, 4) и меткой игрока (х). 
Пустая клетка поля помечается звездочкой (*), например:
```python3
x**1
****
**4*
23**

2. Используя клавиши управления ("s" — вниз, "w" — вверх, "a" — налево, "d" — направо), 
перемещайтесь по по полю и "придавите" всех хомяков.
Дополнительно можно повысить уровень здоровья игрока, нажав на клавишу управления "e".
Выход из игры — клавиша управления "q".

3. В процессе игры игрок теряет уровни здоровья. Когда вы "придавите" всех хомяков, игра закончится:

****
****
****
x***
	WOW!!! You won!!!
