# Отчёт о тестировании Credit Card Number Validator
## Краткое описание
16.08.20 - 16.08.20 было проведено Sanity Tasting приложения Credit Card Number Validator.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
Карты American Express (AMEX) не валидны:
- 346762835865054: Result is FAIL
- 377354144638224: Result is FAIL
- 347205818711977: Result is FAIL


## Описание процесса тестирования





В качестве тестовых данных использовались данные https://www.freeformatter.com/credit-card-number-generator-validator.html:

- 5351719427810741: Result is OK
- 4539486845377715: Result is OK
- 4526947354521882800: Result is FAIL
- 2221008833375621: Result is OK
- 6011063810842346: Result is OK
- 3528399666179604: Result is OK
- 3535204485664282083: Result is FAIL
- 6761484133058091: Result is OK
- 4844031781711038: Result is OK
- 6395443407934878: Result is OK


Тестирование производилось в следующем окружении:
- Windows 7, 64-bit
- Java version "11.0.8" 2020-07-14
