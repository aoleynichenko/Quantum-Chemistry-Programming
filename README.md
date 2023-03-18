# Алгоритмы квантовой химии

В этом репозитории будут выкладываться небольшие уроки, посвящённые алгоритмам, которые используются в современной квантовой химии. Предполагается, что они позволят облегчить подготовку студентов, обучающихся квантовой химии, и снизить порог вхождения в научное программирование. Итогом прохождения курса должна стать небольшая, но настоящая квантовохимическая программа.

К работе по созданию уроков может присоединиться любой желающий. Для этого необходимо разработать небольшой урок по одной из перечисленных ниже тем (или предложить свою), оформить его в виде Jupyter Notebook и выслать на электронную почту alexvoleynichenko@gmail.com

### Пожелания к оформлению уроков

Для того, чтобы унифицировать уроки, желательно придерживаться единообразия в их оформлении:

- Уроки оформляются в Jupyter Notebook
- Язык программирования: Python 3
- В начале файла с уроком необходимо указать фамилии его авторов
- Файл должен содержать не только код, но и подробное описание алгоритма со всеми необходимыми формулами
- Завершаться файл должен списком литературы
- Желательно предусмотреть небольшие задачи в конце файла, дополняющие содержание урока

### Оглавление

*Оглавление является очень приближённым, любые предложения приветствуются*

- Геометрия молекулы
    - краткое введение в объектно-ориентированное программирование на Python
    - вычисление тензора инерции и вращательных постоянных
- Атомно-центрированные базисные наборы
    - считывание из файла
    - оболочки базисных функций
    - визуализация радиального распределения
    - (?) визуализация атомных орбиталей в 3D
- Одночастичные интегралы
    - интегралы перекрывания
    - интегралы от нерелятивистского оператора кинетической энергии
    - интегралы от кулоновского оператора притяжения к ядру (1/r)
    - интегралы от операторов свойств (дипольные и квадрупольные моменты)
- [Двухчастичные интегралы](https://github.com/aoleynichenko/Quantum-Chemistry-Programming/blob/main/two_ints.ipynb) *(Ю. Ломачук)*
- Декартовы и сферические базисные функции
    - преобразование интегралов к базису сферических функций
- Нерелятивистский метод Хартри-Фока для замкнутой оболочки (RHF)
- Нерелятивистский метод Хартри-Фока для открытой оболочки (UHF)
- Формат файлов .cube и визуализация электронной и спиновой плотностей
- Расчёт свойств
    - дипольные и квадрупольные моменты
- Оптимизация геометрии - 1: численные градиенты
    - методы оптимизации геометрии молекулы
- Оптимизация геометрии - 2: аналитические градиенты
    - дифференцирование молекулярных интегралов
    - аналитические градиенты энергии в методе Хартри-Фока
- Колебательная задача - 1: численные гессианы
    - построение и диагонализация гессиана
    - расчёт частот и мод нормальных колебаний
- Колебательная задача - 2: аналитические гессианы
    - аналитические вторые частные производные энергии в методе Хартри-Фока
- Метод DIIS для метода Хартри-Фока
- Преобразование молекулярных интегралов к базису молекулярных орбиталей
- Электронная корреляция - 1: метод MP2
- Электронная корреляция - 2: метод конфигурационного взаимодействия
    - модель CIS однократно для возбуждённых состояний
    - модель CISD для оценки энергии корреляции в основном состоянии
    - натуральные орбитали
- Матрицы плотности в методе CCSD
    - одночастичная матрица плотности
    - двухчастичная матрица плотности
    - визуализация корреляционной дырки
- Алгоритм Дэвидсона для диагонализации матриц больших размерностей


