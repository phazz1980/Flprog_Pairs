# Flprog_Pairs
 Блок записи данных на флэш память контроллеров esp32/8266 для программы Flprog 

Позволяет сохранять на флэш память контроллера в удобном формате "ключ":значение.
Также возможно чтение из файла.

## Блок Main
![promo](/docs/main.png)

- использовать один раз<br>

## Параметры:<br>
 	timeout - время через которое данные сохраняются автоматически после последнего изменения данных

## Входы:<br>
 	delete - очистка файла
 	update - принудительное сохранение в файл до авершения таймаута.
	
