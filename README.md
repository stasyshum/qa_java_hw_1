# qa_java_hw_1
# Отчёт о тестировании KeyValidator #


25.01.2021 - 25.01.2021 было проведено функциональное тестирование приложения KeyValidator.

На тестирование затрачено: 0.5 ч.

 ### В результате тестирования выявлены следующие дефекты: ###

1 [Не действительность валидного ключа №2 в KeyValidator.](https://github.com/stasyshum/qa_java_hw_1/issues/2 )  
2 [Не действительность валидного ключа №4 в KeyValidator.](https://github.com/stasyshum/qa_java_hw_1/issues/3 )  
3 [Действительность невалидного ключа № 5 в KeyValidator.](https://github.com/stasyshum/qa_java_hw_1/issues/4 )   


### Описание процесса тестирования
В процессе тестирования использовались следующие артефакты:

-Тест-кейс домашнего задания №1 с перечисленными валидными и невалидными ключами для KeyValidator.

В качестве тестовых данных использовались данные Тест-кейса домашнего задания №1 с перечисленными валидными и невалидными ключами для KeyValidator.:

-Валидные ключи:  
8f05e6a7-70e9-33d7-bfe7-b19eae0d8998  
80b427f8-92cd-3aae-ba04-3927fbe17c6  
b295bc63-9f03-3b4b-af80-969b39f8c262  
387eedc6-12e9-3b32-9881-63b6b5e85317  
c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180  
*Ожидаемый результат: ОК.*

-Невалидные ключи:  
18252235-78e0-44a5-8720-556f0c7da17a  
e66075b6-ddad-445e-baf6-161b3289522b  
b6d53250-f07e-4352-a293-6102ddf7f1ca  
c2bc778a-1cb9-46c6-b435-0489649d2a42  
2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1  
*Ожидаемый результат: FAIL.*

*Тестирование производилось в следующем окружении:*

Windows 10 64 bit  
java -version (openjdk version "11.0.10" 2021-01-19)





# Отчёт о тестировании Credit Card Number Validator #


26.01.2021 - 26.01.2021 было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 1 ч.

 ### В результате тестирования выявлены следующие дефекты: ###

Не выявлено. 


### Описание процесса тестирования
В процессе тестирования использовались следующие артефакты:

-Тест-кейс домашнего задания №2 с ссылкой на сайт  freeformatter.com с перечисленными валидными и невалидными номерами карт для Validator.

В качестве тестовых данных использовались данные  freeformatter.com с перечисленными валидными и невалидными ключами для Validator.:

-Валидные карты:  
4532543207116607  
5530566818005488   
4917849644204905 

*Ожидаемый результат: ОК.*

-Невалидные карты:  
4539778091795128125  
6011548013588714181   
36835659615915 

*Ожидаемый результат: FAIL.*

*Тестирование производилось в следующем окружении:*

Windows 10 64 bit  
java -version (openjdk version "11.0.10" 2021-01-19)

