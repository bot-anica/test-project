# Работа с файлами - Чтение данных из .txt файлов - Практика

## Задание #1: Анализ лог-файлов
### Цель:
Написать код для анализа лог-файлов, который будет находить и выводить все строки, содержащие слово `"ERROR"`.

### Описание:
У вас есть файл `lesson47_large_log_file.txt`, который содержит записи логов.

Напишите программу, которая будет:
- Открывать файл и считывать его построчно.
- Находить строки, содержащие слово `"ERROR"`.
- Выводить эти строки на экран без лишних пробелов.

### Пример результата работы кода
```commandline
ERROR 2024-10-06 12:03:45 - Ошибка соединения с базой данных
ERROR 2024-10-06 12:06:22 - Некорректный формат данных
```

## Задание #2: Чтение и форматирование контактов

### Цель:
Написать код для чтения файла с контактами и форматирования их для записи в новый файл.

### Описание:
У вас есть файл `lesson47_contacts.txt`, в котором записаны контакты в формате: `Имя`,`Фамилия`,`Телефон`.

Напишите программу, которая будет:
- Открывать файл и считывать его построчно.
- Форматировать строки так, чтобы они выглядели следующим образом: `Фамилия` `Имя`: `Телефон`.
- Записывать отформатированные строки в новый файл `formatted_contacts.txt`.
- Выводить отформатированные строки на экран.

### Пример результата работы кода
```commandline
Иванов Иван: 123456789
Петрова Анна: 987654321
Гонсалес Мария: 456789123
Смит Джон: 321654987
Танака Акира: 654321789
```
