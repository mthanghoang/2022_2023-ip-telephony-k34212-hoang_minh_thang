University: [ITMO University](https://itmo.ru/ru/)  
Faculty: [FICT](https://fict.itmo.ru)  
Course: [IP-telephony](https://github.com/itmo-ict-faculty/ip-telephony) 
Year: 2022/2023  
Group: K34212  
Author: Hoang Minh Thang  
Lab: Lab2  
Date created: 21.09.2022  
Date finished: 04.10.2022
# 

## ЦЕЛЬ РАБОТЫ:
Иизучить построение сети IP-телефонии с помощью маршрутизатора Cisco 2811, коммутатора Cisco catalyst 3560 и IP телефонов Cisco 7960.
## ХОД РАБОТЫ:
### Часть 1
1. Собрать схему соединения.  
![image](https://user-images.githubusercontent.com/61542577/226306000-70299508-be8a-4fff-bf34-0cd308832ae7.png)
2. Изменить название маршру- тизатора на CMERouter.  
![image](https://user-images.githubusercontent.com/61542577/226304284-c7da6ea0-afd5-494f-a867-163b4a72e968.png)
3. Задать пароли для защиты маршрутизатора как в удаленном режиме, так и в режиме консоли.  
![image](https://user-images.githubusercontent.com/61542577/226304561-7968e149-73e6-46e0-855c-657310fe91e0.png)  
![image](https://user-images.githubusercontent.com/61542577/226304630-ffc4b5f4-4d79-4cc7-b2b6-ce5438c44ef9.png)
4. Настроить интерфейс fa0/0 на маршрутизаторе Cisco 2811.  
![image](https://user-images.githubusercontent.com/61542577/226305174-63f0a801-6336-41d0-9359-e7e0045e6dc0.png)
5. Настроить DHCP сервера для передачи голоса и данных на маршрутизаторе Cisco 2811.  
![image](https://user-images.githubusercontent.com/61542577/226305381-6561cdaf-cf1b-4cb8-a006-ecfee7c97fe6.png)
6. Настроить услуги телефонии Cisco CallManager Express на маршрутизаторе 2811.  
![image](https://user-images.githubusercontent.com/61542577/226306499-a5dbcbc0-c799-47e3-b349-65906f23d2bf.png)
7. Настроить VLAN для передачи голосовых трафиков на коммутаторе.  
![image](https://user-images.githubusercontent.com/61542577/226305840-499040f7-18c7-4d73-b6de-6e9da09f8ecc.png)
8. Настроить IP-телефоны, присвоить им номера на маршрутизаторе.  
![image](https://user-images.githubusercontent.com/61542577/226306632-14be141d-fb59-4c4f-b5f5-273dd9c08aed.png)

### Часть 2
1. Собрать схему соединения.  
![image](https://user-images.githubusercontent.com/61542577/226307776-03dc442a-13da-4b49-b42b-b4d02ca0b544.png)
2. Подключить ip-телефоны к источникам питания.  
![image](https://user-images.githubusercontent.com/61542577/226309743-7324018e-d86c-4615-8de9-a95f4e246a69.png)
3. Настроить VLAN 20 для передачи голосовых трафиков и VLAN 10 для обычных трафиков на коммутаторе.  
![image](https://user-images.githubusercontent.com/61542577/226308220-ecc09b96-75b6-4950-9e50-22931f3c58f0.png)
4. Настройте порт FastEthernet0/1 как канал типа trunk на коммутаторе.  
![image](https://user-images.githubusercontent.com/61542577/226308460-da884a15-5ffd-4ca2-ab6d-ea623dbe1bab.png)
5. На маршрутизаторе создать логические интерфейсы для VLAN 10 и VLAN 20 и задать соответствующие ip-адресы.  
![image](https://user-images.githubusercontent.com/61542577/226308923-d27c0084-e3e7-4bd1-b7b3-f413ae9057ed.png)
6. Настроить DHCP сервера для передачи голоса и обычных данных на маршрутизаторе.  
![image](https://user-images.githubusercontent.com/61542577/226309112-e1c373fb-6114-4e65-add6-a929dd8be346.png)
7. Настроить услуги телефонии Cisco CallManager Express на маршрутизаторе.  
![image](https://user-images.githubusercontent.com/61542577/226309322-f7bc3e6c-eb27-4f1f-86dc-ce6668c3bf3a.png)
8. Настроить IP-телефоны, присвоить им номера на маршрутизаторе.  
![image](https://user-images.githubusercontent.com/61542577/226309508-96783007-18fd-4d0d-a3ac-531760a5ce5b.png)

## РЕЗУЛЬТАТЫ
### Часть 1
Результаты звонков.  
![image](https://user-images.githubusercontent.com/61542577/226310108-4f7fa519-169d-4a1b-ade4-de7351982fe9.png)
![image](https://user-images.githubusercontent.com/61542577/226310242-001c6573-dac4-4406-948e-bf45acc07d75.png)
![image](https://user-images.githubusercontent.com/61542577/226310341-d89f7a24-0934-4eb6-af75-8365c2e77d34.png)

### Часть 2
Результаты пингов между компьютерами.  
![image](https://user-images.githubusercontent.com/61542577/226310690-1bf64164-8a22-4907-9805-509d661a7c57.png)
Результаты пингов между компьютером и ip-телефоном.  
![image](https://user-images.githubusercontent.com/61542577/226311006-0c05c80b-c09d-484c-b987-8a762b7f8eb9.png)
Результаты звонков.  
![image](https://user-images.githubusercontent.com/61542577/226311098-2e6aa882-24b9-4b00-80b5-209dc5503ce6.png)
![image](https://user-images.githubusercontent.com/61542577/226311182-e7bf49b5-9cb8-4a3c-b463-c6168893362b.png)
![image](https://user-images.githubusercontent.com/61542577/226311290-33408606-7527-4a76-9794-74b041a04b30.png)


