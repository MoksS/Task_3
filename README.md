У меня две ветки. В ветке master готовое задание со своим линтером и стилями из прошлых работы. 
В ветке default исправленное задание с линтером и css стилями данными по умолчанию.

На скриншоте в описании третье задания в качестве ошибки отмечается не весь блок, а только его ключ "BLOCK",
в то время, как во втором задании просили в качестве ошибки вывести весь блок.
Из-за чего я немного изменил свой lint из второго задания.
Я не знаю правильно ли я сделал или нет, но сделал, так, как представлено на скриншоте, а именно вывожу саму ошибку, что выглядит более логично,
за исключением правила пропорции функциональных и рекламных блоков, а так же моментов, когда один блок выше другого.

Что касается настроек линтера в package json, скорее всего я сделал не правильно, но зато все очень просто и быстро работает. А именно я настройки линтера переместил в объект default, как тип ошибки так и ее описание.
