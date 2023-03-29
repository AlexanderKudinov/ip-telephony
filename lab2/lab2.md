University: ITMO University

Faculty: FICT

Course: IP telephony technology

Year: 2023

Group: K34202

Author: Кудинов Александр Вадимович

Lab: Lab2

Date of create: 29.03.2022

Date of finished:

Тема работы: Конфигурация voip в среде Сisco packet tracer

Цель работы: Изучить построение сети IP-телефонии с помощью маршрутизатора Cisco 2811, коммутатора Cisco catalyst 3560 и IP телефонов Cisco 7960.

Ход работы:

Создана схема, подключены все устройства
<img width="553" alt="image" src="https://user-images.githubusercontent.com/42407837/228646952-0082fbfd-495e-4309-bb0a-95628064bfec.png">

В конфигурационном режиме изменено название маршрутизатора на CMERouter.
<img width="670" alt="image" src="https://user-images.githubusercontent.com/42407837/228647102-63d4e02c-de3d-4a1b-b2a4-a2b4f8d19f94.png">

Отключен синтаксис ввода слов от DNS серверов.
<img width="657" alt="image" src="https://user-images.githubusercontent.com/42407837/228647157-72378679-1645-4fed-9a14-20bb5f79091e.png">

Заданы пароли для защиты маршрутизатора как в удаленном режиме, так и в режиме консоли.
<img width="654" alt="image" src="https://user-images.githubusercontent.com/42407837/228647241-9055ec00-18a0-4ee7-be8c-736f13bfa63b.png">

Настроен интерфейс fa0/0 на маршрутизаторе Cisco 2811 (CMERouter).
<img width="662" alt="image" src="https://user-images.githubusercontent.com/42407837/228647294-1abd407f-14de-4737-b4d1-7260a3f37b42.png">

Настроен DHCP сервер для передачи голоса и данных на маршрутизаторе Cisco 2811.
<img width="660" alt="image" src="https://user-images.githubusercontent.com/42407837/228647380-33e0b87e-e584-4f46-b1a2-44a95ae190f4.png">

Настроить услуги телефонии Cisco CallManager Express на маршрутизаторе 2811.
<img width="655" alt="image" src="https://user-images.githubusercontent.com/42407837/228647469-915df464-9bee-43f7-a07d-28102b44714b.png">

Созданы VLAN порты на коммутаторе Cisco Catalyst 3560 для взаимодействия коммутатора с маршрутизатором и подключены IP телефоны.
<img width="660" alt="image" src="https://user-images.githubusercontent.com/42407837/228647537-37de4650-3c75-4b43-a573-35c61141a0de.png">

Осуществленна настройки IP-телефоноы и их соединение с коммутатором Cisco Catalyst 3560. После чего осуществленны тестовые звонки.
<img width="1011" alt="image" src="https://user-images.githubusercontent.com/42407837/228647595-a5adfa7f-ee50-4cc2-8f40-62520b1fe336.png">

Создана новая схема 
<img width="473" alt="image" src="https://user-images.githubusercontent.com/42407837/228647652-6b598a18-43fb-4ffe-acb9-b10e792b2709.png">

Созданы VLAN порты на коммутаторе для взаимодействия коммутатора с маршрутизатором и подключены IP телефоны.
<img width="662" alt="image" src="https://user-images.githubusercontent.com/42407837/228647757-67051a62-4995-4f2a-a24a-ec6353e0a8da.png">
<img width="659" alt="image" src="https://user-images.githubusercontent.com/42407837/228647807-76c57625-32ad-430b-9a2d-280d07502973.png">
<img width="654" alt="image" src="https://user-images.githubusercontent.com/42407837/228647848-4c01023a-149e-4b1a-af99-a27fae69c99a.png">
<img width="654" alt="image" src="https://user-images.githubusercontent.com/42407837/228647883-5f62767a-f3db-4aa3-8530-3c53150b36a7.png">

Задан маршрут по умолчанию командой ip default-gateway.
<img width="655" alt="image" src="https://user-images.githubusercontent.com/42407837/228647966-cf6b39b7-84dd-4d6a-842a-a17efaf12642.png">

Настроен порт как канал типа trunk.
<img width="660" alt="image" src="https://user-images.githubusercontent.com/42407837/228648021-914747d6-8e00-4197-88fc-23e509a5b0f2.png">

Настроен DHCP сервера для передачи голоса и данных на маршрутизаторе Cisco 2811.
<img width="660" alt="image" src="https://user-images.githubusercontent.com/42407837/228648071-d1e944db-f00d-49d4-915d-d1fe12b01604.png">

Настроены услуги телефонии Cisco CallManager Express на маршрутизаторе.
<img width="678" alt="image" src="https://user-images.githubusercontent.com/42407837/228648123-0541404b-2f18-48af-9bfd-579ba4a40147.png">
<img width="667" alt="image" src="https://user-images.githubusercontent.com/42407837/228648152-745ceb98-d830-4b48-af88-c36467863467.png">

Осуществленна настройка IP-телефонов и конечных устройств, а также их соединение с коммутатором. После чего осуществленна проверка звонков между телефонами и пингов между кончеыми узлами.
<img width="1007" alt="image" src="https://user-images.githubusercontent.com/42407837/228648222-27757a12-df31-41ee-8c46-bd8da6c26ab9.png">

Вывод: Было изучено построение сети IP-телефонии с помощью маршрутизатора Cisco 2811, коммутатора Cisco catalyst 3560 и IP телефонов Cisco 7960.


