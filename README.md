# Архитектура проекта

Проект представляет собой реализацию игры "Виселица" на языке программирования C++. Файлы проекта распределены следующим образом:

- `/lib` - папка, содержащая библиотеку Gtest для тестирования функций проекта.
- `CMakeLists.txt` - файл, содержащий инструкции для сборки проекта с использованием CMake.
- `gallows.h` - заголовочный файл, содержащий объявления функций для реализации игры "Виселица".
- `gallows.cpp` - файл, содержащий определения функций для реализации игры "Виселица".
- `tests.cpp` - файл, содержащий юнит-тесты для функций проекта.

# Запуск проекта

Для сборки проекта необходимо выполнить следующие шаги:

- Установить CMake, если он ещё не установлен.
- Склонировать репозиторий проекта на локальную машину.
- Открыть терминал в корневой папке проекта и выполнить следующие команды:


```shell
mkdir build
cd build
cmake ..
make
```

- После сборки проекта в папке build появится файл `with_tests`. Запустите его, выполнив команду `./with_tests`.
Запуск приведет к выполнению всех тестов над программой.
