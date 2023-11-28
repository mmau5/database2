# Домашнее задание "Базы данных, из типы" - Зябликова Анастасия
 
# Задание 1

1.1 Целостность и четкая структура данных может быть осуществлена при использовании реляционной базы данных

1.2 Реляционные базы данных являются стандартом для CRM-приложений. Также подойдет СУБД ключ-значение т.к обеспечивает хранение простых структур и быстрый доступ к ним

1.3 Если нужно хранить структуры, включая объекты, списки, нормы, правила и словари - для этих целей подойдут Документные СУБД.

1.4 Применение СУБД реляционного типа в логистических системах позволяет наладить четкую логическую связь, т.к есть возможность выполнить следующие условия:

- Сократить время выполнения операций

- Точно определить критерии работы

- Обеспечить стабильность выполнения операций и качество

- Планировать и прогнозировать логистические процессы


# Задание 2

2.1 Онлайн транзакция. Пополнение через приложение банка в телефоне. 

1. выбор услуги (пополнение баланса)
2. выбор суммы
3. подтверждение пользователем
4. информация передается в платежную систему, которая обслуживает карту с которой производится пополнение счета.
5. данные карточки попадают в операционный центр
6. там происходит проверка платежных данных.
7. информация об одобрении операции или отказе передается в банк, который проверяет финансовую операцию. 
8. банк проверяет наличие доступного остатка денежных средств, чтобы провести платеж, PIN-код держателя карты, если таковой вводился. 
9. При успешной проверке банк одобряет операцию, передает данные в платежную систему, которая направляет информацию в торговую точку. 
10. Далее проводятся взаиморасчеты, по результатам которых банк перечисляет необходимую сумму денег, а также комиссию платежной системы за обработку операции. 
11. Со счета покупателя банк списывает деньги за покупку. 

Транзакция завершается, когда ответ поступает в торговую точку с ее одобрением или с отказом. 



# Задание 3

3.1 
1. использование SQL языка стандартизировано международными организациями, БД можно без проблем перенести на другую СУБД, так как все распространенные СУБД используют SQL, помимо этого перенести БД можно и на другую вычислительную систему.

2. Поскольку основа языка реляционная, табличная структура понятна, а сам язык просто изучить. Благодаря обеспечению различного представления данных, можно сделать так, чтобы тот или иной пользователь видел различные представления таблицы. 

3. SQL поддерживает архитектуру «клиент-сервер», позволяет манипулировать БД, обеспечивая возможность динамического изменения и расширения структуры, поддерживает возможность программного доступа к БД.

4. точность — можно не хранить избыточные данные;

5. гибкость — даже самые сложные запросы легко выполнить;

6. масштабируемость — с одной БД могут работать множество пользователей;

7. безопасность — доступ к данным в таблицах есть только у определенных пользователей.

# Задание 4

Для работы с большим количеством данных и вычислениями подходят колоночные СУБД. Основные преимущества колоночных СУБД – эффективное выполнения сложных аналитических запросов на больших объемах, и легкое, практически мгновенное, изменение структуры таблиц с данными, плюс существенная компрессия и сжатие, которое позволяет значительно экономить место.

Выбор СУБД зависит от возможности эффективно работать с большим объемом данных. 

Тип Кластерных вычислений подходит лучше всего, т.к для выполнения задач задействовано 1000 машин. В данной архитектуре несколько компьютеров соединяются вместе, образуя единую систему. Каждый компьютер в кластере отвечает за часть задач по обработке или хранению данных. Такой подход чаще всего используют для высокопроизводительных приложений.

