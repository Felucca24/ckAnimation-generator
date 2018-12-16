# ckAnimation generator
***Примеры работы внизу!***
Эти скрипты позволяют генерировать файлы анимаций подсветки для некоторых клавиатур от Bloody. Я тестировал на Bloody B975, должно работать на похожих моделях с RGB подсветкой. Изменяя ckAnimation_algorithms.py, можно легко добавлять свои анимации, наследуя класс Algorithm.

***ВНИМАНИЕ!***  
Если вы захотели опробовать данные скрипты - ВЫ ДЕЛАЕТЕ ВСЁ НА СВОЙ СТРАХ И РИСК! Если вдруг с Вашей клавиатурой или компьютером что-то случится, я не несу ответственности за это.

## Использование
Создайте папку и поместите оба скрипта в неё. Запустите скрипт с помощью Python 3.
Например, через консоль.  

    Shift+Правая кнопка мыши, находясь в папке -> Открыть окно команд
    
    python ckAnimation_generator.py

Далее скрипт попросит написать путь и описание ckAnimation файла.После будут предложены существующие варианты алгоритмов генерации анимаций. Выберите один, введя цифру и нажав Enter. В папке или по указанному пути будет сохранён сгенерированный файл анимации.

Теперь нужно зайти в KeyDominator (официальную программу для клавиатур Bloody), выбрать вкладку RGB animation и нажать сверху слева на "Файл"->"Импорт", найти файл, нажать зелёную стрелку и EXIT.
![Инструкция](https://i.imgur.com/impdjwi.png?1)  

Теперь следует забиндить анимацию в таблице.
![Инструкция](https://i.imgur.com/jA9lRlE.png)

И не забудьте нажать APPLY!  
![Инструкция](https://i.imgur.com/rPggu4S.png)  

***Готово. Теперь можно выбрать сгенерированную анимацию нажатием назначенного сочетания с Fn.***

***ЧТОБЫ УДАЛИТЬ ФАЙЛ (например, для замены другим) НУЖНО ЗАХОДИТЬ В РЕДАКТОР АНИМАЦИИ И НАЖИМАТЬ ТАМ УДАЛИТЬ ФАЙЛ.***

## GIF - примеры

![Инструкция](https://i.imgur.com/gO0a5b3.gif)