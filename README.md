# Домашнее задание к работе 5
## Условие задачи
Создать программу вычисления указанной величины.
Результат проверить при заданных исходных значениях.
## 1. Алгоритм и блок-схема
### Алгоритм
1. **Начало**
2. ввод значений:
   - `x` = первое число.
   - `y` = второе число.
   - `z` = третий число 
3. Счёт:
   - `rest = pow(fabs(x - y), 2)`
   - `rest1 = pow(8 + rest + 1, 1 / 3.f)`
   - `rest2 = pow(x, 2)+pow(y, 2) + 2`
   - `rest3 = exp(fabs(x - y))`
   - `rest4 = pow(tan(z), 2)`
   - `rest5 = pow(rest4 + 1, x)`
   - `result = rest1 / rest2 - (rest3 * rest5)`
4. Выводим результаты расчетов:
   - `result`
5. **Конец**
### Блок-схема
<img width="702" height="1053" alt="image" src="https://github.com/user-attachments/assets/630039a9-f4cd-4b27-83ad-3291b0bfa7e6" />

## 2. Реализация программы
<img width="1134" height="1115" alt="image" src="https://github.com/user-attachments/assets/3f3d062b-39af-471a-b5f0-75130f1d8322" />

## 3. Результаты работы программы
<img width="572" height="311" alt="image" src="https://github.com/user-attachments/assets/c60556de-80f7-4960-ae63-bf954c047e9e" />

## 4. Информация о разработчике
### Ахмедов Одилжон З. бИПТ-252

