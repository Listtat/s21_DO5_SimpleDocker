## Part 1. Готовый докер

1.1 Использование команды docker pull для выкачки докера nginx
![./Screenshots/1.png](./Screenshots/1.png)
1.2 Проверка наличия докер образа при помощи команды docker images
![./Screenshots/2.png](./Screenshots/2.png)
1.3 Запуск докер образа при помощи команды docker run -d image_id
![./Screenshots/3.png](./Screenshots/3.png)
1.4 Проверка запуска докера при помощи команды docker ps
![./Screenshots/4.png](./Screenshots/4.png)
1.5 Просмотр информации о контейнере при помощи команды docker inspect container_id
![./Screenshots/5.png](./Screenshots/5.png)
![./Screenshots/6.png](./Screenshots/6.png)
![./Screenshots/7.png](./Screenshots/7.png)
![./Screenshots/8.png](./Screenshots/8.png)
1.6 Остановка докер образа и проверка, что он остановился
![./Screenshots/9.png](./Screenshots/9.png)
1.7 Запуск докера с замапленными портами 80 и 443
![./Screenshots/10.png](./Screenshots/10.png)
1.8 Проверка на доступность стартовой страницы nginx по адресу localhost:80 в браузере
![./Screenshots/11.png](./Screenshots/11.png)
1.9 Перезапуск докера и проверка, что он запустился
![./Screenshots/12.png](./Screenshots/12.png)

## Part 2. Операции с контейнером

2.1 Вывод содрежимого файла nginx.conf
![./Screenshots/13.png](./Screenshots/13.png)
2.2 Создание на локальной машине файла nginx.conf. Настройка в нем по пути /status отдачу страницы статуса сервера
![./Screenshots/14.png](./Screenshots/14.png)
2.3 Копирование файла nginx.conf внутрь докер образа. Перезапуск nginx внутри докер рбраза. Проверка статуса сервера
![./Screenshots/15.png](./Screenshots/15.png)
2.4 Экспорт контейнера в файл. Остановка контейнера
![./Screenshots/16.png](./Screenshots/16.png)
2.5 Удаление образа
![./Screenshots/17.png](./Screenshots/17.png)
2.6 Удаление остановленного контейнера
![./Screenshots/18.png](./Screenshots/18.png)
2.7 Импорт контейнера обратно. Запуск импортированного контейнера. Проверка работоспособности контейнера
![./Screenshots/19.png](./Screenshots/19.png)

## Part 3. Мини веб-сервер

3.1 Создание сервера на языке С
![./Screenshots/20.png](./Screenshots/20.png)
3.2 Создание nginx.conf
![./Screenshots/21.png](./Screenshots/21.png)
3.3 Выкачка докера nginx. Проверка, что загрузка прошла успешно. Запуск образа и проверка, что он запустился
![./Screenshots/22.png](./Screenshots/22.png)
3.4 Копирование nginx.conf и server.c в докер-контейнер
![./Screenshots/23.png](./Screenshots/23.png)
3.5 Вход в сам контейнер. Проверка, что файлы успешно скопировались
![./Screenshots/24.png](./Screenshots/24.png)
3.6 Обновление контейнера. Установка gcc, spawn-dcgi, libfcgi-dev
![./Screenshots/25.png](./Screenshots/25.png)
3.7 Компиляция и запуск нашего сервера
![./Screenshots/26.png](./Screenshots/26.png)     
3.8 Перезагрузка контейнера и проверка страницы в браузере
![./Screenshots/27.png](./Screenshots/27.png)

## Part 4. Свой докер

4.1 Создание докер образа.
![./Screenshots/28.png](./Screenshots/28.png)
4.2 Запуск скрипта из докера                                                  
![./Screenshots/29.png](./Screenshots/29.png)
4.3 Сбор написанного образа. Маппинг 81 порта на 80. Проверка доступа стрички командной localhost:80                              
![./Screenshots/30.png](./Screenshots/30.png)
4.4 Проверка на корректность сборки                                           
![./Screenshots/31.png](./Screenshots/31.png)
4.5 Добавление в файл nginx.conf проксирование странички /status                                        
![./Screenshots/32.png](./Screenshots/32.png)
4.6 Проверка странички /status                                     
![./Screenshots/33.png](./Screenshots/33.png)

## Part 5. **Dockle**

5.1 Сканирование образа                                  
![./Screenshots/34.png](./Screenshots/34.png)
5.2 Проверка на отсутствие ошибок и предупреждений после исправления образа                    
![./Screenshots/35.png](./Screenshots/35.png)

## Part 6. Базовый **Docker Compose**

6.1 Файл docker-compose.yml                  
![./Screenshots/36.png](./Screenshots/36.png)

6.2 Проверка на работоспособность после сборки и запуска                
![./Screenshots/37.png](./Screenshots/37.png)
