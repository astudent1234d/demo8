# Отчёт о тестировании <Precision>

## Краткое описание

04.11.2021 - 04.11.2021 было проведено функциональное тестирование приложения Precision.

На тестирование затрачено: один час

В результате тестирования выявлены следующие дефекты:
* [При выполнении операции добавления дополнительного бонуса новым клиентам, итоговая сумма бонуса отличается от ожидаемой](https://github.com/astudent1234d/demo8/issues/1)

## Описание процесса тестирования

В качестве тестовых данных использовались следующие данные:
* regularBonus типа double равное 0.3
* specialBonus типа double равное 0.6
* totalBonus типа double равное regularBonus + specialBonus
* Ожидаемый результат сумма данных значений 0.9


Тестирование производилось в следующем окружении:
* Linux Mint 20.2 х64
* Java 11.0.11
* IntelliJ IDEA 2021.2.3
