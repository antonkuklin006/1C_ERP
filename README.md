# Этот репозиторий преднозначен для руководителей проектов IT. 
> Проектный менеджер играющий отдельно от команды - обречен, на провал. Как и его проекты....
©Джон Дорр

## Твои основные дашборды на этапе разработки:
- [Планирование этапов](https://clck.ru/382PaF)
- [Задачи](https://clck.ru/382PsR)
- [Дорожная карта](https://clck.ru/382Qo3)



## Твои основные дашборды на этапе тестирования, на стороне заказчика:
- [Help desk](https://github.com/users/antonkuklin006/projects/2/views/7)
- [Ticket system](https://github.com/users/antonkuklin006/projects/2/views/8)
- [Bug tracker](https://github.com/users/antonkuklin006/projects/2/views/9)

## Что должен понимать:
- [Стэк](https://clck.ru/382KNk)
- [CI\CD](https://clck.ru/382PsR)
- [Клиент-серверная архетектура](https://clck.ru/382Qo3)
- [Бизнес-процессы](https://clck.ru/382Qo3)

## Документация (может изменяться: количеству, содержанию): 
- [Project Charter (Устав проекта)](https://clck.ru/382NPz)
- [Project Management Plan (План управления проектом)](https://clck.ru/382MwW)
- [Work Breakdown Structure (Разработка структуры проекта)](https://clck.ru/382NPz)
- [Risk Register (Реестр рисков)](https://clck.ru/382MwW)
- [Communication Plan (План коммуникаций)](https://clck.ru/382NPz)
- [Resource Management Plan (План управления ресурсами)](https://clck.ru/382MwW)
- [Stakeholder Register (Реестр заинтересованных сторон)](https://clck.ru/382NPz)
- [Change Management Plan (План управления изменениями)](https://clck.ru/382MwW)
- [Cost Management Plan (План управления затратами)](https://clck.ru/382NPz)
- [Scope Management Plan (План управления объемом работ)](https://clck.ru/382MwW)
- [Stakeholder Communication Plan (План коммуникации с заинтересованными сторонами)](https://clck.ru/382NPz)
- [Performance Reports (Отчеты о выполнении)](https://clck.ru/382MwW)
- [Risk Management Plan (План управления рисками)](https://clck.ru/382NPz)
- [Human Resource Management Plan (План управления человеческими ресурсами)](https://clck.ru/382MwW)
- [Project Archive (Архив проекта)](https://clck.ru/382NPz)
- [Project Closeout Report (Отчет о завершении проекта)](https://clck.ru/382MwW)

## Твои основные вопросы: 
- [Важность и приоритеты?](https://clck.ru/382NPz)
- [А что с бизнес-процессом?](https://clck.ru/382MwW)

```mermaid
sequenceDiagram
    participant Alice
    participant Bob
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts <br/>prevail!
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
```
- [Будем делать Ганнта?](https://clck.ru/382MwW)
```mermaid
gantt
    dateFormat  YYYY-MM-DD
    title       Adding GANTT diagram functionality to mermaid
    excludes    weekends
    %% (`excludes` accepts specific dates in YYYY-MM-DD format, days of the week ("sunday") or "weekends", but not the word "weekdays".)

    section A section
    Completed task            :done,    des1, 2014-01-06,2014-01-08
    Active task               :active,  des2, 2014-01-09, 3d
    Future task               :         des3, after des2, 5d
    Future task2              :         des4, after des3, 5d

    section Critical tasks
    Completed task in the critical line :crit, done, 2014-01-06,24h
    Implement parser and jison          :crit, done, after des1, 2d
    Create tests for parser             :crit, active, 3d
    Future task in critical line        :crit, 5d
    Create tests for renderer           :2d
    Add to mermaid                      :1d
    Functionality added                 :milestone, 2014-01-25, 0d

    section Documentation
    Describe gantt syntax               :active, a1, after des1, 3d
    Add gantt diagram to demo page      :after a1  , 20h
    Add another diagram to demo page    :doc1, after a1  , 48h

    section Last section
    Describe gantt syntax               :after doc1, 3d
    Add gantt diagram to demo page      :20h
    Add another diagram to demo page    :48h
```
