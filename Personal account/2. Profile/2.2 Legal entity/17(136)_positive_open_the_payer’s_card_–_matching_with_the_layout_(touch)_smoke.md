* Тестовые данные: Позитивная проверка. Открыть карточку плательщика - совпадение с макетом (touch).

	тестовый сервер - https://test2.stroyrem-nn.ru/   продовый сервер - https://stroyrem-nn.ru/

* Предусловие: пользователь авторизован, открыт «Личный кабинет» / "Профиль", у пользователя есть плательщик

* Шаги:
1.	Выбрать вкладку "Юридическое лицо"
2.  Открыть карточку плательщика

* Ожидаемый результат: открывается карточка плательщика, в которой есть:
	- стрелка для возврата во вкладку
	- раздел "Данные плательщика" с кнопками для переключения между плательщиками (??? уточняется)
	- раздел "Данные контактного лица":
		- аватар с начальной буквой имени
		- имя и фамилия
		- контакты: номер телефона и "E-mail" 
		- кнопка "Изменить данные"
	- раздел "Данные об организации":
		- данные: "ИНН", "Название организации", "Юридический алрес", "Почтовый адрес"
		- кнопка "Изменить данные об организации"	
	- раздел "Данные о счёте организации":
		- данные: "Расчетный счёт", "БИК", "Наименование банка", "Корреспондентский счёт"
		- кнопка "Изменить данные о счёте"	

* Постусловие: удалить тестовые данные

Автор: Надежда
	
* Отчет о тестировании
  
Тестовый сервер
| Дата | Время | Версия браузера Десктоп | Результат/Баг в Трелло Десктоп|  Версия браузера и ОС Тач |Результат/Баг в Трелло Тач| Дата релиза| QA  |
| --- | --- | --- | --- |  --- | --- | --- | --- |   
| 10.09.23 | 17:50 |  | --- | Chrome версия 116.0.5845.163 MIUI 12.5.13 | FAIL https://trello.com/c/GhJr0Fj9/530 | 03.09.23 | Надежда |  

Продовый сервер
| Дата | Время | Версия браузера Десктоп | Результат/Баг в Трелло Десктоп|  Версия браузера и ОС Тач |Результат/Баг в Трелло Тач| Дата релиза| QA |
| --- | --- | --- | --- |  --- | --- | --- | --- |   
| 10.09.23 | 17:52 | --- | --- | Chrome версия 116.0.5845.163 MIUI 12.5.13 | FAIL https://trello.com/c/GhJr0Fj9/530 | 03.09.23 | Надежда |