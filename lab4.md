University: ITMO University

Faculty: FICT

Course: IP telephony technology

Year: 2023

Group: K34202

Author: Кудинов Александр Вадимович

Lab: Lab4

Date of create: 05.04.2022

Date of finished:

Тема работы: Построение сети ip-телефонии между удаленными маршрутизаторами

Цель работы: Изучить построение сети IP-телефонии между удаленными филиалами с помощью маршрутизаторов Cisco 2811 и коммутаторов Cisco 2950Т.Изучить построение сети IP-телефонии между удаленными филиалами с помощью маршрутизаторов Cisco 2811 и Cisco 2600XM.

Ход работы: Собрана схема соединения, указанная на рисунке 1. 

<img width="917" alt="image" src="https://user-images.githubusercontent.com/42407837/230175068-d23bdbf6-dce6-412e-a6ac-5f18a4a12d8b.png">

Настроен интерфейс fa0/0 на маршрутизаторах Cisco 2811. 

<img width="687" alt="image" src="https://user-images.githubusercontent.com/42407837/230175153-fd2fbd32-2cda-45d1-9ea1-988c45e48c65.png">

Настроен интерфейс s0/3/0 на маршрутизаторах Cisco 2811. 

<img width="680" alt="image" src="https://user-images.githubusercontent.com/42407837/230175266-ab8a4bec-51e7-46d7-b303-e8ea27363fa5.png">

<img width="680" alt="image" src="https://user-images.githubusercontent.com/42407837/230175321-403feeff-481d-4708-9f4c-46328ce53d01.png">

Настроен маршрутизатор Cisco 2811, коммутатор Cisco 3950Т, IP-телефоны аналогично лабораторной работе №2. 

<img width="680" alt="image" src="https://user-images.githubusercontent.com/42407837/230175420-eba21e4b-8056-4158-b158-882cfc81fbb1.png">

<img width="656" alt="image" src="https://user-images.githubusercontent.com/42407837/230175493-2f52b593-fa1c-4ac3-8ad9-8fda6af5aa4b.png">

<img width="652" alt="image" src="https://user-images.githubusercontent.com/42407837/230175547-dc383e20-a5b7-49a7-b70b-b4ca705241ad.png">

Настроены DHCP сервера на маршрутизаторах для передачи голоса и данных между ними. 

<img width="651" alt="image" src="https://user-images.githubusercontent.com/42407837/230175631-9c5fbbb3-46a6-4271-9050-6fff46caff2a.png">

Настроена динамическая маршрутизация RIP между маршрутизаторами для передачи информации друг другу. 

<img width="649" alt="image" src="https://user-images.githubusercontent.com/42407837/230175696-35d613ba-b614-4acc-8468-bc0dc34c7f0a.png">

Настроены услуги телефонии Cisco CallManager Express на маршрутизаторе 2811. 

<img width="648" alt="image" src="https://user-images.githubusercontent.com/42407837/230175803-579d56a0-a55d-408d-be53-5cb78b0a6d33.png">

<img width="650" alt="image" src="https://user-images.githubusercontent.com/42407837/230175832-0c76f6b7-8035-4d48-b59b-5f69ed9bcadd.png">

Проверены вызовы между удаленными IP-телефонами и пинги между удаленными хостами. 

<img width="687" alt="image" src="https://user-images.githubusercontent.com/42407837/230175923-ecb06e74-ca72-44a5-9465-830d85a6bc47.png">

<img width="1010" alt="image" src="https://user-images.githubusercontent.com/42407837/230175979-0fa76545-2e7d-4988-84e6-ba0d7c3ae926.png">

Вывод: В ходе выполнения лабораторной работы было изучено построение сети IP-телефонии между удаленными филиалами с помощью маршрутизаторов Cisco 2811 и коммутаторов Cisco 2950Т, при помощью инструментов Cisco Packet Tracer.

Ход работы: Собрана схема соединения, указанная на рисунке 1. 
