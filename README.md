# Приложение, которое решает задачу Линейного Программирования графическим и симплекс методом
## Краткая информация
**Задача линейного программирования _(ЛП)_** – это задача, в которой требуется найти максимум или минимум функции,
называемой целевой функцией, при ограничениях, заданных системой линейных неравенств или уравнений.

Пример такой системы (ЛП):  
![Задача Линейного программирования в виде системы неравенств](../assets/assets/linear-prog.png?raw=true)

Приложене реализует 3 способа решения:
- Симплекс метод
- Метод искусственного базиса
- Графический метод

Про _графический метод_ решения можно почитать здесь:  
https://math.semestr.ru/lp/index.php  
Про _Симплекс метод_ и _Искуственный базис_ читаем здесь:  
https://programforyou.ru/calculators/simplex-method

Демо:   
![Гифка с результатами работы приложения](../assets/assets/demo-work.gif?raw=true)

## Особенности приложения
- Приложения отображает каждый промежуточный результат. Если нужен ответ, то
  достаточно нажать кнопку "**Получить ответ**"
- Имеется история промежуточных результатов, поэтому легко откатиться назад  
- Можно загружать и выгружать условия задачи  
`Файл -> Открыть / Сохранить условие задачи`
- Отображение чисел можно представить в виде обыкновенных (1/2) или десятичных (0.5) дробей
- Есть возможность выбирать базисный вектор самостоятельно на каждом этапе решения
  