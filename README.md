### Этот проект содержит сервис с ml-моделью предсказания оттока клиентов телекома.
* Проект включает front и back части. Общение между front и back реализовано по API.
* Front часть предлагает опцию загрузки файла(неразмеченного) для скоринга в формате .csv и опцию выгрузки файла с предсказаниями. Файл с предсказаниями содержит id объекта(в нашем случае клиента) и предсказание для него (1 или 0)
* Полученный сервис упакован в Docker Image.
