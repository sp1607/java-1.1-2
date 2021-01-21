# Отчёт о тестировании Credit Card Number Validator

## Тестирование функциональности валидации номера банковской карты

21.01.2021 было проведено функциональное тестирование, тестирование граничных значений приложения Credit Card Number Validator.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:

* [Credit Card Number Validator не распознаёт валидные карты с номером более 16 символов](https://github.com/sp1607/java-1.1-2/issues/1)

* [Credit Card Number Validator не распознаёт валидные карты с номером менее 16 символов](https://github.com/sp1607/java-1.1-2/issues/2)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* [Установка IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)
* [Техническое задание](https://github.com/netology-code/javaqa-homeworks/tree/master/intro#задача-2---credit-card-number-validator)

В качестве тестовых данных использовались данные из [генератора валидных номеров карт](https://www.freeformatter.com/credit-card-number-generator-validator.html#validate):
* 4916239011998393204 - ОК
* 6011123051415316849 - ОК
* 3540562426034483346 - ОК
* 36031961253914 - ОК
* 36287299090259 - ОК
* 36894999131836 - ОК

Тестирование производилось в следующем окружении:
* ОС: Windows 10 Pro x64
* Java: 11.0.9.1
* InteliJ IDEA Community Edition 2020.3.1