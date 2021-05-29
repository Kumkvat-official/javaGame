Простая текстовая бродилка (квест)

Основные команды: Локация - получить описание текущей локации.
Предметы - получить описание инвентаря текущей локации.
Взять - добавить предмет из локации к себе в инвентарь.
Выложить - добавить предмет из своего инвентаря в локацию.
Инвентарь - показать предметы из твоего инвентаря.
Использовать - использовать предмет из инвентаря.
Вперёд (ё обязательна), назад, влево, вправо - пойти в соответсвующую сторону, если это возможно.
Выход - закончить игру. (Сохранение пока ещё, к сожалению, не завезли).
Помощь - прочитать это сообщение ещё раз.

Запуск игры происходит в методе main() класса Main


Версия игры: 2.0

Что нового:
Добавил диаграммы классов в двух экземлярах: полная и без классов Game(сюжет игры) и Main
В диаграмме классов вместо HashMap<String, Location> указано HashMap<String and Location> потому что StarUML не разрешил мне разделять типы данных запятой

Разложил классы по папкам, вынес кучу String'ов с описаниями локаций в отдельный класс

Также добавил в тесты с двумя локациями и четырьмя предметами, чтобы убедиться в правильном взаимодействии классов

Пофиксил команду выхода из игры: теперь выход осуществляется не по команде "стоп" а по "выход", как и написано во вступлении
