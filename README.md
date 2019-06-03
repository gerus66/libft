## Libft
Моя библиотека функций для проектов School21. 

Изначально написана по [заданию](https://github.com/gerus66/libft/blob/master/readme/libft.en.pdf), с тех пор постоянно дополняется.
### Run & Use
`make`

`-I path/to/libft/includes -path/to/libft/libft.a`

## Библиотека:
* std - стандартная часть. Простейшие операции с памятью, строками, символами, числами, указателями.. Частично повторяет
функции _stdlib.h_ и _string.h_. Используются только встроенные типы.
* `list` - создан тип односвязный список и функции для работы с ним
* `vector` - создан тип саморасширяющийся / сжимающийся массив и функции для работы с ним
* `tree` - создан тип словарь (ключ: значение) по принципу AVL-дерева и функции для работы с ним
* gnl - функция последовательного считывания из файла по одной строке - [подробнее о проекте](https://github.com/gerus66/libft/blob/master/readme/get_next_line.en.pdf). 
Используется кастомные типы `vector` и `tree`
* ft_printf - повторяет поведение стандартного printf (включая undefined behavior) - [подробнее о проекте](https://github.com/gerus66/libft/blob/master/readme/ft_printf.en.pdf).
Используется кастомный тип `vector`.
### Codestyle
Проект написан в строгом соответствии с [Norminette codestyle](https://github.com/gerus66/norme)
