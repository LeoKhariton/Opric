# OPRIC &ndash; ОПРИС &ndash; Цифровая образовательная платформа для изучения математики и программирования
## Аннотация
Это кроссплатформенная цифровая образовательная платформа для изучения дисциплин из области математики, программирования и информационных технологий.  
В приложении:
- собраны теоретические материалы, практические задания и тесты самопроверки (в настоящий момент доступны дисциплины "Программирование на языке С/С++" и "Численные методы");  
- доступны вспомогательные сервисы &ndash; С++ компилятор, редактор блок-схем, а также конструктор графиков (*только в десктопной версии*);  
- есть личный кабинет, где ведется рейтинг лучших студентов и можно отслеживать свой прогресс;  
- есть возможность сменить тему на тёмную;  
- можно работать как с доступом к интернету, так и без него (без доступа к сети доступны *все функции, за исключением аккаунта*).
Еще ведь есть преподавательская версия.

![видеодемонстрация версии 2](https://github.com/LeoKhariton/Opric/blob/main/Test/видео1.gif)

## Установка
Начиная с версии 1.0, приложение разрабатывалось с помощью кроссплатформенных фрейморков, поэтому его можно запустить на широком круге устройств.  
Начиная с версии 2.0, приложение поддерживает связь с сервером.  
Начиная с версии 3.0, приложение является мультидисциплинарным.  
//можно добавить - кроссплатформенность, мультидисциплинарность, и тд  
//ссылки давать к истории версий, а в истории версий - на релизы
| Версия | Описание | Поддерживаемые платформы<br/>(минимальная версия) | Поддержка |
| :--: | -- | -- | -- |
| 0 | [Электронное учебное пособие по программированию на C++](#v0) | Windows 7 | &#10060; |
| 1 | [Кроссплатформенное электронное учебное пособие по программированию на C++ "Оприс" версии 1](#v1) | &#9989;**Android** 6.0 (API 23)<br/>**iOS** 10<br/>&#9989;**Windows** 8.1 (необходима поддержка **UWP**)<br/>**macOS** Mojave (10.14) | &#9989; |
| 2 | [Кроссплатформенное мультидисциплинарное электронное учебное пособие "Оприс" версии 2](#v2) | &#9989;**Android** 5.0 (API 21)<br/>**iOS** 11<br/>&#9989;**Windows** 10 (с помощью **Win UI 3**)<br/>**macOS** 10.15 | &#9989; |
| 3 | [Кроссплатформенное мультидисциплинарное цифровое учебное пособие "Оприс" версии 3 (превью)](#v3) | **Android** 5.0 (API 21)<br/>**iOS** 11<br/>&#9989;**Windows** 10 (с помощью **Win UI 3**)<br/>**macOS** 10.15 | &#9989; |
| 4 (текущая) | **Цифровая образовательная платформа "Оприс" для изучения математики и программирования** | Windows <br/> Android <br/> iOS <br/> macOS <br/> Linux (Ubuntu) | В разработке |
### Android
Скачайте установочный файл с расширением `.apk` и запустите его на устройстве Android.  
При необходимости, дайте приложению доступ к мобильной сети.
### Windows 11
1. Загрузить файл-установщик с расширением `.msix`.
2. Если сертификат еще не установлен, сначала необходимо его установить.
<details><summary>Установка сертификата</summary>
  
  1. Сначала откройте окно свойств установочного файла и перейдите к вкладке "Цифровые подписи". Выберите единственную подпись из списка и нажмите "Сведения":  
  ![w1](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w1.png)  
  2. В открывшемся окне "Состав цифровой подписи" выберите "Просмотр сертификата":  
  ![w2](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w2.png)  
  3. В открывшемся окне нажмите "Установить сертификат":  
  ![w3](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w3.png)  
  4. Выберите установку сертификата для всего локального компьютера и нажмите "Далее" от имени администратора:  
  ![w4](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w4.png)  
  5. Выберите "Доверенные корневые центры сертификации", нажмите "ОК":  
  ![w5](https://github.com/LeoKhariton/Opric/blob/main/Setup/UWP/w5.png)  
  6. А затем "Далее" и "Готово". Появится уведомление, оповещающее об успешной установке сертификата.  
  7. Закройте окно свойств и запустите установщик.
</details>

3. Запустите установщик
### Windows 10
Для Windows 10 необходимо проделать всю процедуру установки для Windows 11, а также дополнительно:

4. Установить с официального сайта Microsoft [Windows App SDK](https://learn.microsoft.com/ru-ru/windows/apps/windows-app-sdk/downloads) (если еще не установлена).
5. Первый раз необходимо открыть программу от имени администратора.

## Краткое руководство по эксплуатации
Сразу после запуска приложения загружается "главная" &ndash; страница выбора дисциплины. На текущий момент для изучения доступны две дисциплины &ndash; "Программирование на языке С/С++" и "Численные методы".  

После открытия приложения загрузится "главная" страница &ndash; страница, на которой можно выбрать раздел.  
![](https://github.com/LeoKhariton/Opric/blob/main/Test/1.png)  
В левом верхнем углу доступно навигационное меню-гамбургер, содержащее 3 вкладки &ndash; разделы, личный кабинет и настройки.
### Вкладка "Разделы"
Кликнув по соответствующему названию раздела, открывается страница с вкладками (Android/iOS) / верхним меню (Windows/macOS), на которой располагается содержимое раздела, которое включает "Лекцию", "Тест" и "Практику". В десктопных платформах доступны две дополнительные вкладки &ndash; С/С++ компилятор и редактор блок-схем.
![](https://github.com/LeoKhariton/Opric/blob/main/Test/3.png)  
Для преподавателя доступен режим редактирования учебного контента.  
![режим редактирования](https://github.com/LeoKhariton/Opric/blob/main/Test/4.png)
### Вкладка "Личный кабинет"
После прохождения регистрации будет доступен личный кабинет с рейтингом самых активных пользователей и со статистикой прохождения тестов, а на "главной" вокруг иконок разделов будет отображаться статистика прохождения теста по соответствующей теме.  
![](https://github.com/LeoKhariton/Opric/blob/main/Test/Презентация1.jpg)  
### Вкладка "Настройки"
В разделе "Настройки" можно выбрать тему приложения, а также доступны некоторые настройки аккаунта.  
![](https://github.com/LeoKhariton/Opric/blob/main/Test/6.png)  
***
Если вы нашли ошибку, просьба сообщить о ней *максимально подробно*, воспользовавшись формой для отправки отзывов. Необходимо описать ситуацию, которая привела к ошибке, и саму ошибку, желательно приложив скриншот. **Важно сообщить об ошибке как можно подробнее, чтобы разработчики могли повторить ситуацию, приведшую к ошибке и исправить ее.**  
Другой вариант сообщения об ошибке &ndash; сформировать подробный отчет о ней [на странице данного репозитория](https://github.com/LeoKhariton/Opric/issues). Там также следует описать саму обишку, по возможности приложить скриншот и описать шаги для ее воспроизведения.  
## Публикации и работы ##
1. Международная конференция ["Новые информационные технологии и системы" (НИТиС-2022)](https://elibrary.ru/item.asp?id=50454558&pff=1), Пенза.
2. [Всеросскийская конференция Нижневартовского государственного университета](https://konference.nvsu.ru/konffiles/383/Stud_konf_CH3_Informacionnye_tehnologii.pdf).  
3. [Региональный научно-практический семинар им. Л.В. Широкова](https://elibrary.ru/item.asp?id=54087229), Арзамас.
4. Международная конференция "Инновационные процессы в науке и технике XXI века", Нижневартовск.
5. Всероссийская научно-практическая конференция им. Жореса Алфёрова, Санкт-Петербург.
6. Всероссийская научно-практическая конференция "Наука молодых", посвященная 125-летию НГТУ им. Р.Е. Алексеева, Арзамас.
7. ИИТМА
8. Конкурс работ региональный и конкурс в Брянске
9. Конференция
10. Конференция Нижневартовск
11. Конференция еще
12. 

## Апробация и внедрение
![](https://github.com/LeoKhariton/Opric/blob/main/Акт%20о%20внедрении.png)

## Авторство и права на код и базу данных

## История версий \[АРХИВ]
### <a name="v3"/> Версия 3 &ndash; Мультидисциплинарное кроссплатформенное электронное учебное пособие "Оприс" (только preview)

https://github.com/user-attachments/assets/ffec16e0-ab8d-4b16-9ee8-79631d42f3a5

Приложение было с множеством нововведений, но релиз так и не состоялся.  
[Скачать](https://github.com/LeoKhariton/Opric/releases/tag/v3.0-preview2)

### <a name="v2"/> Версия 2 &ndash; Кроссплатформенное электронное учебное пособие по программированию на C++ "Оприс" с функцией редактирования учебного контента
Приложение написано на платформе .NET MAUI с помощью языка C#. Имеет связь с серверной БД SQLite.  
Была добавлена связь с сервером.  
![видеодемонстрация версии 2](https://github.com/LeoKhariton/Opric/blob/main/Test/видео1.gif)  
[Скачать](https://github.com/LeoKhariton/Opric/releases/tag/v2.0.0)

### <a name="v1"/> Версия 1 &ndash; Кроссплатформенное электронное учебное пособие по программированию на C++ "Оприс"
Приложение представляет собой кроссплатформенное электронное учебное пособие по программированию на языке C++. Оно написано на платформе Xamarin.Forms с помощью языка C# и целевыми устройствами для него являются ПК под управлением Windows и мобильные устройства Android.  
![видеодемонстрация версии 1](https://github.com/LeoKhariton/Opric/blob/main/Test/видео.gif)  
#### Windows
Это приложение является универсальным приложением Windows (т.е. доступно как на десктопных платформах, так и на Windows Phone, и даже на очках смешанной реальности HoloLens, которые также функционируют на базе универсальной платформы Windows). Поэтому установочный файл имеет не привычное расширение `.exe`, `.msi` или `.msix` (как у программ, разработанных на платформах WPF или Windows Forms), а `.APPX` или `.APPXBUNDLE`.  
#### Что делать, если компьютер не распознает файл .appx или .appxbundle?
Бывают случаи, когда компьютер с ОС Windows 10 не распознает файлы `.appx` и `.appxbundle` как установочные, и предлагает открыть их с помощью какой-то программы.  
В этом случае необходимо открыть Power Shell и ввести следующую команду:
```
add-appxpackage [путь к установочному файлу]
```
Если все необходимые пакеты установлены, то эта команда приведет к запуску установки приложения (важно, что **сертификат должен быть предварительно установлен вручную тем же способом, который описан выше в пп. 2-9**). В противном случае выведется сообщение об ошибке, возникшей в ходе устновки. Чаще всего это может быть связано с отсутствием каких-либо пакетов (например, пакета поддержки XAML необходимой версии). Их можно установить либо вручную, либо с обновлением Windows, либо с помощью Visual Studio 2019 (для этого обычно достаточно обновить VS до последней версии или подключить пакет разработки приложений для универсальной платформы Windows).  
*Примечание*  
Во избежание конфликтов стилей, желательно, чтобы тема приложения совпадала с системной.  
[Скачать](https://github.com/LeoKhariton/Opric/releases/tag/v1.2.2)

### <a name="v0"/> Версия 0 &ndash; Электронное учебное пособие по программированию на C++
Приложение "Электронное учебное пособие по программированию на языке C++" включало в себя панель с разделами и вкладки "Лекция", "Тест" и "Практика" с образовательным контентом. Оно было создано с помощью платформы Windows Forms на языке `C++` и целевыми устройствами для него являлись компьютеры с ОС Windows 7 и выше.  
Для работы приложения необходимо было загрузить весь образовательный контент и распаковать его в каталог `C:\faust\` вручную. Учебный контент представлял из себя набор pdf-файлов и изображений, не организованных в реляционную базу данных.  
![a9](https://github.com/LeoKhariton/Opric/blob/main/Version%20History/v0-WinForms.png)
