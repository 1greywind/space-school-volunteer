# Школа волонтеров Летней Космической Школы. Лекция №7
## Операционная система kOS

[Ссылка на запись лекции на канале "Твой Сектор Космоса"](https://www.youtube.com/watch?v=iqjGZDsFEvs).

### Краткое содержание лекции:
* Что такое операционная система kOS
* ЦПУ kOS и организация дискового пространства
* Запуск команд kOS
* Базовые сведения о языке KerbalScript
* Переменные, области видимости
* Циклы и триггеры
* Управление кораблем с помощью KerbalScript
* Работа с Telnet терминалом kOS
* Переключение между разными ЦПУ и запуск команд на разных кораблях

### Задания для Лекции №7:

№1

* Загрузите сохраненную игру и через центр слежения перейдите к разгонному блоку КВРБ-1
* Откройте терминал kOS
* Включите на разгонном блоке SAS и RCS, используя kOS
* Разверните разгонный блок против вектора скорости

№2

* Напишите программу, которая включит на КВРБ SAS и RCS
* Развернет КВРБ в положение prograde
* Дождется, пока КВРБ не достигнет перицентра
* В перицентре включит двигатели разгонного блока
* Дождется, пока апоцентр не будет равен 1000 км
* Выключит двигатели

### Как выполнять задания

1. Подготовьте рабочую среду
   1. Установите программу Kerbal Space Program (инструкцию по установке см. ниже) 
   2. Cкачайте архив с [файлами занятий](https://github.com/1greywind/space-school-volunteer/raw/master/Лекция%20№7/Школа_волонтеров_Задания_для_лекции_№7.zip)
   3. Распакуйте архив в папку /ваша папка, где установлена KSP/Saves
2. Запустите КСП
3. В главном меню выберите пункт "Начать игру"
4. Далее выберите "Сохраненная игра"
5. В появившемся меню выберите "Школа волонтеров - Задания для лекции №7" и либо кликните на этом пункте два раза, либо нажмите "Загрузить".
6. На экране космического центра нажмите ALT+F5, чтобы открыть список сохраненных состояний. Выберите в нем "Start"
7. На экране космического центра нажмите на значок Станции слежения слева (шестой сверху, с иконкой антенны)
   либо нажмите на здание Станции слежения в космическом центре
8. Внутри станции слежения выберите КВРБ-1 и перейдите к нему двойным щелчком
9. Справа вверху, на панели модов, выберите самый нижний пункт - kOS
10. В открывшемся окне нажмите на значок с изображением компьютера. Откроется терминал kOS
11. Для выполнения второго задания нужно будет перейти в папку с игрой, затем в папку Ships/Script
12. Там создаем файл программы, например program.ks
13. После написания программы в игре ее можно запустить в терминале kOS. Для начала вводим switch to 0. 
14. Затем run program.ks. Обратите внимание, что точка в конце команды обязательна, иначе интерпретатор выдаст ошибку
15. Для написания программы вам может пригодиться [документация по kOS](https://ksp-kos.github.io/KOS/contents.html#contents)
16. Для включения двигателя достаточно установить его тягу на полную мощность - LOCK THROTTLE TO 1.
17. Для выключения LOCK THROTTLE TO 0.
18. Также вам потребуются переменные APOAPSIS и PERIAPSIS и оператор WAIT кол-во секунд.
18. После выполнения задания нажмите ALT+F9 и сохрание состояние, дав ему соответствующее имя (например, "Выполненное задание №7")
19. Результат задания пришлите в чат ЛКШ•2021 [в Контакте](https://vk.me/join/AJQ1d_3CuBfywdM9wDb9kgNs)
    или [в Телеграме](https://t.me/space_school_chat) в форме скриншотов, видео или сохраненных файлов
20. Для второго задания достаточно прислать программу, которая выполняет поставленную задачу

Для выполнения большинства домашних занятий вам потребуется программа Kerbal Space Program

## Инструкция по установке Kerbal Space Program (KSP):
1. Приобретите KSP на
    [сайте разработчика](https://www.kerbalspaceprogram.com/store/),
    [онлайн магазине Steam](https://store.steampowered.com/app/220200/Kerbal_Space_Program/),
    [или GOG](https://www.gog.com/game/kerbal_space_program)
    (наименьшая цена в рублях будет скорее всего в стиме - 250-300 р. по скидке)
2. Установите программу (если у вас возникают трудности или вопросы,
   пишите в чат ЛКШ•2021 [в Контакте](https://vk.me/join/AJQ1d_3CuBfywdM9wDb9kgNs)
   или [в Телеграме](https://t.me/space_school_chat)
3. Так как нужные для выполнения задания модификации требуют версию KSP 1.8.1, то:
    1. При покупке игры через Steam выберите игру в списке
    2. Нажмите правой кнопкой и выберите там пункт "Свойства"
    3. В появившемся окне перейдите на таб "Бета-версии"
    4. И там выберите из списка 1.8.1 
4. Скачайте архив с комплектом необходимых дополнений [по ссылке](http://spaceprogram.ru/GameData-LKSH-2020-volunteer-modpack.zip)
5. Распакуйте архив в папку /ваша папка, где установлена KSP/GameData
6. Запустите KSP


