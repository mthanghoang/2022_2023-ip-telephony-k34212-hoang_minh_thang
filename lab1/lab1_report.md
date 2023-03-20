University: [ITMO University](https://itmo.ru/ru/)  
Faculty: [FICT](https://fict.itmo.ru)  
Course: [IP-telephony](https://github.com/itmo-ict-faculty/ip-telephony) 
Year: 2022/2023  
Group: K34212  
Author: Hoang Minh Thang  
Lab: Lab1  
Date created: 19.09.2023  
Date finished: 20.3.2023
# 

## ЦЕЛЬ РАБОТЫ:
Изучить рабочую среду Cisco Packet Tracer, ознакомиться с интерфейсами основных устройств, типами кабелей, научиться собирать топологию. Изучить построение сети IP-телефонии с помощью маршрутизатора, коммутатора и IP телефонов Cisco 7960 в среде Packet tracer
## ХОД РАБОТЫ:
### Часть 1
1. Собрать схему соединения  
![image](https://user-images.githubusercontent.com/61542577/226249591-78b3f2cf-07fa-4f46-9b49-8eb437cd99e6.png)
2. Присвоить компьютерам ip-адрес в диапазоне 192.168.0.1-192.168.0.7
На рисунке представлен пример присвоивания ip-адреса одному компьютеру.  
![image](https://user-images.githubusercontent.com/61542577/226250041-3af74878-de84-405b-ba60-b120260586c7.png)
3. После этого любой компьютер может передать пакеты посреством пинга любому компьютеру.
### Часть 2
1. Собрать схему соединения.  
![image](https://user-images.githubusercontent.com/61542577/226250768-1e2dd42d-0632-42c8-84e7-983eb3aa9da5.png)
2. Подключть ip-телефоны к источнику питания.  
![image](https://user-images.githubusercontent.com/61542577/226250955-aea98fa6-ca01-46ea-8b61-32e114e05df5.png)
3. Изменить имя маршрутизатора на CMERouter.  
![image](https://user-images.githubusercontent.com/61542577/226251090-4fe9d5dc-2f77-49b7-bd86-e539f7bf747c.png)
4. Настроить интерфейс fa0/0 на маршрутизаторе Cisco 2811 (CMERouter).  
![image](https://user-images.githubusercontent.com/61542577/226251346-b13df702-c5e3-4fc8-b0f7-40b9cc1dba8b.png)
5. Настроить DHCP сервера для передачи голоса и данных на маршрутизаторе - Cisco 2811.  
![image](https://user-images.githubusercontent.com/61542577/226251651-a3095f7f-811d-4df7-b80e-5c6c35f08435.png)
6. Настроить услуги телефонии Cisco CallManager Express на маршрутизаторе. 
![image](https://user-images.githubusercontent.com/61542577/226253582-7142511a-c789-4b25-aa50-d899a28f4045.png)
7. Настроить VLAN для передачи голосовых трафиков на коммутаторе.  
![image](https://user-images.githubusercontent.com/61542577/226253784-1a24d2c4-b2aa-477a-9b68-3f2432d6fce3.png)
8. Настроить IP-телефоны, присвоить им номера на маршрутизаторе.  
![image](https://user-images.githubusercontent.com/61542577/226253996-6934b7a3-52b2-4309-9535-da00796b7277.png)
## РЕЗУЛЬТАТЫ
### Часть 1
Результаты пингов между компьютерами.  
![image](https://user-images.githubusercontent.com/61542577/226254274-f5bc2e7e-9e64-4776-b72d-b590bdef8f4e.png)
### Часть 2
Результаты звонков.  
![image](https://user-images.githubusercontent.com/61542577/226254434-0a9e91b2-5720-4e9e-9b86-1402a27141bc.png)
![image](https://user-images.githubusercontent.com/61542577/226254512-689e22ed-42a0-47f3-919f-141ba5ae74cc.png)





