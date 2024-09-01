# Дипломная работа по курсу "Инженер по тестированию: с 0 до middle"

## Тестирование мобильного приложение "Хоспис"

[Ссылка на задание](https://github.com/netology-code/qamid-diplom)

### Для работы с проектом необходимо: 
- Android Studio
- Allure


### Для запуска тестов:

- Склонировать репозиторий с помощью команды git clone https://github.com/KaterinaVoroshilova/Diplom
- Открыть Android studio
- Открыть склонированный проект, папку fmhandroid
- Дождитесь загрузки Gradle
- Запустить эмулятор Pixel 2 API 29
- Запустите все тесты либо в меню Run -> All Tests, можете использовать горячие клавиши (по умолчанию Ctrl+Shift+f10)

### Для формирования Allure отчетов

- Запустить тесты
- Выгрузить каталог /data/data/ru.iteco.fmhandroid/files/allure-results с эмулятора (при помощи Device Manager).
- Перейти в консоли на уровень выше каталога allure-results
- Выполнить команду allure serve либо сделать отчет с помощью плагина Allure (см.инструкцию к плагину)
- Дождаться формирования отчета
- Открыть отчеты в браузере
