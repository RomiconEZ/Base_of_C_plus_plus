[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-f059dc9a6f8d3a56e377f745f24479a46679e63a5d9fe6f495e02850cd0d8118.svg)](https://classroom.github.com/online_ide?assignment_repo_id=7124584&assignment_repo_type=AssignmentRepo)
# Задание для тестирования
Набор положительных чисел a_1, a_2, ..., a_k называется разбиением натурального числа n, если n = a_1 + a_2 + ... + a_k, где a_1 ⩾ a_2 ⩾...⩾ a_k > 0.

Например, существует 5 различных разбиений числа n=4:
* 1+1+1+1
* 2+1+1
* 2+2
* 3+1
* 4

Необходимо для заданных чисел n и k вычислить число разбиений n на k частей.

Числа n и k пользователь вводит с клавиатуры (n,k⩽500). Результатом работы программы является выведенное в консоль число разбиений n на k частей.

### Пример
**Вход:** `4 2`

**Выход:** `2`

Шаблон программы приведен в файле `task.cpp`. В нём необходимо написать реализацию функции `partition`.
