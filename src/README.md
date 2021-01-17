# Отчёт о тестировании приложения Precision
### Краткое описание

17.01.2021 было проведено позитивное функциональное тестирование приложения [MoneyTransfer](https://github.com/EliseevG787/JAVAQA-2.1/blob/master/src/Main.java).

На тестирование затрачено: 1/6 часа.

В результате тестирования выявлены следующие дефекты:

* [Некорректный вывод приложения для подсчёта текущего баланса](https://github.com/EliseevG787/JAVAQA-2.1/issues/1)


### Описание процесса тестирования

Входные данные:

* текущий баланс счёта клиента - переменная типа int, значение - 2_000_000_000 (два миллиарда рублей)
* сумма перевода - переменная типа int, значение - 500_000_000 (пятьсот миллионов рублей)
* переменная для хранения итогового значения - тип int


Тестирование производилось в следующем окружении:

* Windows 10 LTSC X64

* openjdk version "11.0.9.1" 2020-11-04
  OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.9.1+1)
  OpenJDK Client VM AdoptOpenJDK (build 11.0.9.1+1, mixed mode)

* IntelliJ IDEA Community Edition

* [MoneyTransfer](https://github.com/EliseevG787/JAVAQA-2.1/blob/master/src/Main.java)