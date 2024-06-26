# Задумка проекта
Программа предназначена для быстрого и удобного создания редактируемых цифровых копий текстов, отображаемых на экране монитора.

# Описание проекта
Данная программа была разработанна с целью экономии времяни и сил. Основная задумка заключалась в автоматизации лишних процессах. По сравнению с другими программами и сайтами, имеется возможность выделить часть экрана, с которой будет считываться текст, что позволяет экономить время и не делать скриншоты.

## Возмоности
- Распознавать текст с экрана монитора.
- Автоматически форматировать текст.
- Сохранять текст в различных форматах (docx, txt).

## Преимущества
- Повышение производительности: программа позволяет быстро и легко создавать цифровые копии текстов, что экономит время и силы пользователя.
- Удобство использования: программа имеет простой и понятный интерфейс, что делает ее доступной для пользователей с любым уровнем подготовки.
- Многофункциональность: программа поддерживает распознавание текста на различных языках, автоматическое форматирование и сохранение в различных форматах.

# Начало работы
## Поддерживаемые операционные системы
Перед началом работы с програамой необходимо убедиться в том, что ваша версия Windows соответствует с тревобованиями программы, на данный момент программа поддержимает Windows 7 и выше.

## Установка .NET Framework
Для работы программы необхода программная платформа .NET Framework 4.8. Для установки необходимой версии, перейдите по следующей ссылке: [Ссылка на сайт](https://support.microsoft.com/ru-ru/topic/microsoft-net-framework-4-8-автономный-установщик-для-windows-9d23f658-3b97-68ab-d013-aa3c3e7495e0). Затем нажмите на кнопку "Скачать автономный установщик Microsoft .NET Framework 4.8", начнется процесс загрузки. По завершении загрузки откройте скачанный файл и выполните установку .NET Framework 4.8.

# Пользовательский интерфейс
## Настройки
Данное меню включает в себя все настройки программы.

![1](https://github.com/Nerx2008/SceenshotTextRecognizer/assets/102707294/66b812cd-8492-43fd-af9d-dd23f5432baa)
- Кнопка "Bind": назначьте клавишу для запуска процесса считывания с экрана.
- Кнопка "Выделение области": открывает новое окно для настройки процесса выделения области экрана.
- Кнопка "Результат сканирования": открывает новое окно для настройки анализа результатов сканирования.
- Поле для отметки "Показывать поверх других окнон": опция, которая обеспечивает отображение приложения поверх других окон.
- Поле для отметки "Работа в фоновом режиме": переключение в режим фоновой работы, позволяющее приложению выполнять задачи в фоновом режиме.
- Поле для отметки "Автозагрузка": включает автоматический запуск приложения при старте операционной системы.
  
![2](https://github.com/Nerx2008/SceenshotTextRecognizer/assets/102707294/1d041415-5cdc-4f6a-b886-ad5931a242b9)

Настройки процесса выделения области экрана.
- Выбор "Выделение области": выберите способ выделения области - по зажатию кнопки мыши или ПКМ/ЛКМ.
- Выбор "Фон при выделении": выберите цвет фона при выделении - чёрный или без фона.
- Кнопка "Отмена bind:": назначьте клавишу для отмены текущего процесса сканирования.
- Кнопка "Подтвердить bind:": назначьте клавишу для подтверждения выделеной области для дальнельшей обработки.

![3](https://github.com/Nerx2008/SceenshotTextRecognizer/assets/102707294/6346d879-4de7-4e43-b6ca-0ea82c3ac067)

Настройки анализа результатов сканирования.
- Поле для отметки "Удалять лишние пробелы": удалить лишние пробелы в результатах сканирования.
- Поле для отметки "Удалять пустые строки": удалить пустые строки в результатах сканирования.
- Поле для отметки "Удалять строки без букв": удалить строки, не содержащие букв, работает только с русский и английским языком.

## Языковые модели
В этом меню вы можете увидеть уже скаченые языки и скачать новые для дальнельшего использования.

![4](https://github.com/Nerx2008/SceenshotTextRecognizer/assets/102707294/4847136f-1466-49d4-bb15-eb7b36ff0c5e)
- Поле для ввода "Поиск": позваляет быстро найти в списке скаченых языков, тот, который вы ищите.
- Кнопка "Удалить": удаляет выбраный вами язык.
- Кнопка "Скачать": открывает новое окно, в котором вы можете скачать другие языки.

![5](https://github.com/Nerx2008/SceenshotTextRecognizer/assets/102707294/01670ed2-a40b-4f93-8b84-5ff0ea63d6fe)

Окно для скачивания языков.
- Поле для ввода "Поиск": позваляет быстро найти в списке языков, тот, который вы ищите.
- Кнопка "Выбрать всё": позваляет выбрать все не скаченные языки.
- Кнопка "Отменить всё": отменяет все выбраные языки для скачивания.
- Кнопка "Начать загрузку": начинает загруку языков.
    
## Языковые комбинации
Сдесь можно комбинировать языки, чтобы распознавать текст сразу не нескольких язык. Например можно использовать вместе русский язык и английский язык.

![6](https://github.com/Nerx2008/SceenshotTextRecognizer/assets/102707294/cc6eafa4-be59-4ec4-8f9c-f1d584b668ff)
- Список комбинаций: откравет выбранную при двойном нажатии языковую комбинацию в новом окне для её редактирования.
- Поле для ввода "Поиск": позваляет быстро найти в списке комбинаций, ту, которую вы ищите.
- Кнопка "Удалить": удаляет выбраную вами комбинацию.
- Кнопка "Редактировать": открывает новое окно для редактирования комбинации.
- Кнопка "Новая комбинация": открывает новое окно для ввода данных в новую языковую комбинацию.

![7](https://github.com/Nerx2008/SceenshotTextRecognizer/assets/102707294/efe25d2f-de7d-4510-94ae-9914db2cb61a)

Окно для редактирования или создании новой комбинации
- Поле для ввода "Имя": изменение имяни комбинации.
- Список "Выбрать": при двойном нажатии добавляет в комбинацию выбранный язык.
- Список "Выбранные": при двойном нажатии убирает из комбинации выбранный язык.
- Кнопка "Сохранить": сохраняет все изменения.
