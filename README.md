# Test-STEK-1C
Выполнены основные 7 тестовых задач. 
Сразу оговорю те моменты, которые немного не докрутила (не успеваю), чтобы сэкономить ваше время и обозначить, что я вижу, где нужно дорабатывать:
1. Задача № 5 - тот список, в котором выдываем команду "Установить отметку" обновляется сразу. А связанный список будет также с отметкой, если его открыть. Если же он уже был открыт, то для появления там отметки, необходимо его обновить (F5). Понимаю, что надо подтянуть связь со списком связанного документа. 
2. Задача № 6 - уух )) Сделала просто отчет, который выводит клиентов, купивших выбранный товар. Мыслю, что для заданного условия ("Купил товар А, но при этом не купил товар Б") выборки в SQL я бы сделала просто две выборки (1 - купившие товар и 2 - не купившие товар) и объединила бы их через INNER JOIN. Но как это реализовать в 1С, пока не могу сообразить. Понимаю, что в СКД только левое соединение работает. А через виртуальные таблицы не нашла пока такого функционала (по хорошему-то все промежуточные расчеты лучше же в виртуальных таблицах держать).
3. Задача № 7 - тут когда клиет говорит, что ДА, действительно хочет выйти, то форма обработки закрывается не сразу, а при повторном нажатии на крестик (но уже, конечно, без дополнительных вопросов). 
