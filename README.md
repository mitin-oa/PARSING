# PARSING
TEST Parsing_text 
1.	Необходимо написать скрипт для парсинга диалогов из файла test_data.csv. Получившийся скрипт необходимо выложить в гит репозиторий и прислать ссылку в качестве результата прохождения тестового задания. Данные выкладывать в гит не следует. 
2.	Главные задачи, которые должен выполнять скрипт:
a.	Извлекать реплики с приветствием – где менеджер поздоровался. 
b.	Извлекать реплики, где менеджер представил себя. 
c.	Извлекать имя менеджера. 
d.	Извлекать название компании. 
e.	Извлекать реплики, где менеджер попрощался.
f.	Проверять требование к менеджеру: «В каждом диалоге обязательно необходимо поздороваться и попрощаться с клиентом»
3.	Рекомендации:
a.	Сделать локальную копию файла test_data.csv, в исходнике никакие данные не менять!
b.	Можно создать дополнительное поле в таблице test_data.csv, куда будет сохраняться результат парсинга – например, напротив реплики в столбце “insight” можно ставить флаг того, что эта реплика с приветствием greeting=True.
c.	Для выполнения задачи можно использовать любые библиотеки и NLP модели. 
d.	Попробуйте учесть возможные синонимичные выражения, которые могут помочь с извлечением данных сущностей. 
