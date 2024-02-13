# Flprog_Pairs
 Блок записи данных на флэш память контроллеров esp32/8266 для программы Flprog 
 Создана на основе билиотеки [Pairs](https://github.com/GyverLibs/Pairs)

Позволяет сохранять на флэш память контроллера в удобном формате "ключ":значение.
Также возможно чтение из файла.

## Блок Main
![promo](/docs/main.png)

- Главный блок, использовать обязательно!<br>
- использовать в проекте один раз<br>

### Параметры:<br>
 	timeout - время через которое данные сохраняются автоматически после последнего изменения данных

### Входы:<br>
 	delete - очистка файла
 	update - принудительное сохранение в файл до завершения таймаута.
	
## Блок Get <br>
![promo](/docs/get.png)
- чтение данных из файла<br>


### Входы:<br>
	Key - ключ по которому будут прочитаны необходимые данные

### Выходы:<br>
	data - данные полученные по ключу на входе
	
## Блок Set <br>
![promo](/docs/set.png)
- запись данных в файл

### Входы:<br>
	En - вход разрешения записи
	Key - ключ по которому будут записаны необходимые данные
	Data - данные которые небходимо записать
