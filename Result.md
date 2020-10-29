# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

29.10.2020 было проведено функциональное дымовое тестирования приложения Credit Card Number Validator.
На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:

* [Дефект 1](https://github.com/A-Yu-Zhukova/Credit-Card-Number-Validator/issues/1)
* [Дефект 2](https://github.com/A-Yu-Zhukova/Credit-Card-Number-Validator/issues/2)
* [Дефект 3](https://github.com/A-Yu-Zhukova/Credit-Card-Number-Validator/issues/3)
* [Дефект 4](https://github.com/A-Yu-Zhukova/Credit-Card-Number-Validator/issues/4)
* [Дефект 5](https://github.com/A-Yu-Zhukova/Credit-Card-Number-Validator/issues/5)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:

* Чек-лист
* Отчет о тестировании 
* Баг-репорт

В качестве тестовых данных использовались [данные](https://www.freeformatter.com/credit-card-number-generator-validator.html: )

Валидные номера банковских карт для тестирования 
* VISA:
4539727403303860
4024007198749128
4539569476979621297
* MasterCard:
2720998983503020
5455663433228040
2720994681173976
* American Express (AMEX):
341368018970052
349368251760881
340328855546986
* Discover:
6011062538399696
6011469207328023
6011804315957429914
* Maestro:
6762592946992048
0604444343735015
6762229964327951
* Visa Electron:
4844173062617276
4026166297275142
4175009291226225
* InstaPayment:
6392669037326860
6390733173528788
6376426841343189 

Невалидные номера банковских карт для тестирования 
4276550125879966
2200240871258963
5484015574562589

## Тестирование производилось в следующем окружении:

* ОС (Windows 7 Максимальная, 64-рязрядная),
* Java version 11.0.9
