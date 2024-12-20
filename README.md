# Лабораторная работа №1. Работа с базой данных.
* Выполнила: Зинченко Анна
* Язык программирования: Java

# Что делает приложение?
Этот проект демонстрирует простой пример взаимодействия с базой данных в Android-приложении. 
Чтобы запустить проект можно прочитать ["Как запустить"](#как-запустить)

# Функциональность:
## Задание 1
* MainActivity: 
    На этом экране находятся кнопки "Показать", "Добавить", "Обновить".
<div align="left">
  <img src="https://github.com/domosedochka/Laba3/blob/main/Screenshot_2024-11-20-00-57-37-067_com.example.laba3ex1.jpg" width="200" />
</div>

* Кнопка 1 («Показать»):
Запускает второе действие (ShowActivity), которое отображает все записи из таблицы «classmate2» в виде списка, включая ФИО и время добавления каждой записи.
<div align="left">
  <img src="https://github.com/domosedochka/Laba3/blob/main/Screenshot_2024-11-20-01-07-59-444_com.example.laba3ex1.jpg" width="200" />
</div>

* Кнопка 2 («Добавить»):
  Добавляет новую запись в таблицу «classmate2».
<div align="left">
  <img src="https://github.com/domosedochka/Laba3/blob/main/Screenshot_2024-11-20-01-08-05-253_com.example.laba3ex1.jpg" width="200" />
</div>

* Кнопка 3 («Обновить»): изменяет ФИО в последней добавленной записи на «Иванов Иван Иванович». Пользователь получает уведомление об успешном или неудачном обновлении.
Все три кнопки взаимодействуют с классом DatabaseHelper для выполнения операций с базой данных.
<div align="left">
  <img src="https://github.com/domosedochka/Laba3/blob/main/Screenshot_2024-11-20-01-08-10-949_com.example.laba3ex1.jpg" width="200" />
</div>

## Задание 2
* MainActivity: 
    На этом экране находятся кнопки "Показать", "Добавить", "Обновить".
<div align="left">
  <img src="https://github.com/domosedochka/Laba3/blob/main/Screenshot_2024-11-20-02-03-25-314_com.example.laba3ex2.jpg" width="200" />
</div>

* Кнопка 1 («Показать»):
Запускает второе действие (ShowActivity), которое отображает все записи из таблицы «Classmate2» в виде списка, включая ФИО и время добавления каждой записи. По заданию Фамилия, Имя, Отчество должны находиться в разных полях.
<div align="left">
  <img src="https://github.com/domosedochka/Laba3/blob/main/Screenshot_2024-11-20-02-03-31-629_com.example.laba3ex2.jpg" width="200" />
</div>

* Кнопка 2 («Добавить»):
  Добавляет новую запись в таблицу «Classmate2».
<div align="left">
  <img src="https://github.com/domosedochka/Laba3/blob/main/Screenshot_2024-11-20-02-03-38-364_com.example.laba3ex2.jpg" width="200" />
</div>

* Кнопка 3 («Обновить»): изменяет ФИО в последней добавленной записи на «Иванов Иван Иванович». Пользователь получает уведомление об успешном или неудачном обновлении.
Все три кнопки взаимодействуют с классом DatabaseHelper для выполнения операций с базой данных.
<div align="left">
  <img src="https://github.com/domosedochka/Laba3/blob/main/Screenshot_2024-11-20-02-03-43-914_com.example.laba3ex2.jpg" width="200" />
</div>

# Как запустить
1. Загрузка или клонирование репозитория:
* Скачайте файлы проекта (ZIP-архив) и разархивируйте их в удобную папку или клонируйте репозиторий с помощью команды git clone [URL репозитория].

2. Открытие проекта в Android Studio:
* Откройте Android Studio.
* В главном окне выберите "Open an existing Android Studio project".
* Найдите папку, в которую вы скачали или клонировали проект, и выберите файл build.gradle.

3. Запуск приложения:
* В Android Studio, нажмите кнопку "Run" (зеленый треугольник) на панели инструментов.
* Выберите эмулятор или подключенное Android-устройство, на котором вы хотите запустить приложение.
* Дождитесь завершения сборки и запуска приложения.
