# Отчёт о тестировании Money Transfer

## Краткое описание
21.12.2021 - 21.12.2021 было проведено юнит-тестирование приложения Money Transfer.

На тестирование затрачено: 0 ч 5 мин

В результате тестирования выявлены следующие дефекты:

* Итоговая сумма после перевода имеет отрицательное неправильное знаечние (-1794967296)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:

* Сhecklist
* Bug Reports в Issues

В качестве тестовых данных использовались данные входные данные:

* текущий баланс счёта клиента - переменная типа int, значение - 2_000_000_000 (два миллиарда рублей)*
* сумма перевода - переменная типа int, значение - 500_000_000 (пятьсот миллионов рублей)
* переменная для хранения итогового значения - тип int

Тестирование производилось в следующем окружении:

* Windows 10 Pro x64
* версия Java 11.0.13
* IntelliJ IDEA Community Edition 2021.1 x64
