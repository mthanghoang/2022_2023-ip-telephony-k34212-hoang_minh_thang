University: [ITMO University](https://itmo.ru/ru/)  
Faculty: [FICT](https://fict.itmo.ru)  
Course: [IP-telephony](https://github.com/itmo-ict-faculty/ip-telephony) 
Year: 2022/2023  
Group: K34212  
Author: Hoang Minh Thang  
Lab: Lab4  
Date created: 19.03.2023  
Date finished: 20.03.2023
# 

## ЦЕЛЬ РАБОТЫ:
Изучить построение сети IP-телефонии между удаленными филиалами с помощью маршрутизаторов Cisco 2811
и коммутаторов Cisco 2950Т. Изучить построение сети IP-телефонии между удаленными филиалами с помощью маршрутизаторов Cisco 2811 и Cisco 2600XM.
## ХОД РАБОТЫ:
### Часть 1
**1. Собрать схему соединения.**
![image](https://user-images.githubusercontent.com/61542577/229104462-24b3bea4-860b-433b-977a-974daad7d9b9.png)

**2. Настроить интерфейсы f0/0 и s0/3/0 на обеих маршрутизаторах.**

Настройки на первом маршрутизаторе 

![image](https://user-images.githubusercontent.com/61542577/229104866-459aa74e-70bd-4777-bd98-d60bd099686b.png)

Настройки на втором маршрутизаторе 

![image](https://user-images.githubusercontent.com/61542577/229104988-1c827bac-4cd6-4d6c-80fc-af9923ddb603.png)

**3. Настроить DHCP сервера на маршрутизаторах для передачи голоса и данных между ними.**

Настройки на первом маршрутизаторе 

![image](https://user-images.githubusercontent.com/61542577/229105421-f3014cb7-aa78-4472-b69b-d72fbf4c5c22.png)

Настройки на втором маршрутизаторе 

![image](https://user-images.githubusercontent.com/61542577/229105487-fde51a32-ddb9-45ac-923f-9f2249838963.png)

**4. Настроить динамическую маршрутизацию RIP между маршрутизаторами для передачи информации друг другу.**

Настройки RIP на первом маршрутизаторе

![image](https://user-images.githubusercontent.com/61542577/229106058-3a8e8136-cd8a-43a8-82bb-4e60d02c3b8f.png)

Настройки RIP на втором маршрутизаторе

![image](https://user-images.githubusercontent.com/61542577/229106180-c7505271-b004-4679-abb6-329e00389485.png)

**5.Настроить услуги телефонии Cisco CallManager Express на маршрутизатах.**

Настройки на первом маршрутизаторе

![image](https://user-images.githubusercontent.com/61542577/229106757-aace3675-6e3f-4fa0-a5bf-eb3e6aa82544.png)

Настройки на втором маршрутизаторе

![image](https://user-images.githubusercontent.com/61542577/229106933-4a8e3354-fcdf-4257-88b4-de902b6fd930.png)

**6. Настроить voice vlan на коммутаторах**

Настройки на первом коммутаторе

![image](https://user-images.githubusercontent.com/61542577/229107488-84afa8c9-d152-442b-9840-a82c8ddafbab.png)

Настройки на втором коммутаторе

![image](https://user-images.githubusercontent.com/61542577/229107615-f0214d91-01e2-4291-b41f-7e3dd463c51b.png)

**7.Настроить IP-телефоны, присвоить им номера на маршрутизаторах.**

Настройки на первом маршрутизатое

![image](https://user-images.githubusercontent.com/61542577/229108686-d827baba-804b-4b17-82d3-ed340d44bf28.png)

Настройки на втором маршрутизатое

![image](https://user-images.githubusercontent.com/61542577/229108784-c4a687ad-ad31-49bc-976c-860216c4a26c.png)

**8. Завершить настройки с настройкой dial-peer на маршрутизаторах.**

Настройки на первом маршрутизатое

![image](https://user-images.githubusercontent.com/61542577/229109055-8f4c52ed-fe76-4993-a4bf-6484e92eb1a3.png)

Настройки на втором маршрутизатое

![image](https://user-images.githubusercontent.com/61542577/229109163-dffe1972-c9c8-45eb-8d4d-d02493878c28.png)




## РЕЗУЛЬТАТЫ
### Часть 1
Результаты звонка между телефоннами в одной сети

![image](https://user-images.githubusercontent.com/61542577/229107871-7199e1af-d185-4791-b64a-6ba10550ddfa.png)

Результаты звонка между телефоннами в разных сетях

![image](https://user-images.githubusercontent.com/61542577/229109332-cb450552-9d16-4af1-a15c-d0ba516f6790.png)

Результаты пингов между компютерами в разных сетях

![image](https://user-images.githubusercontent.com/61542577/229109511-74e1ebbf-a9c8-4b8f-a545-5c3d2dbcb4b3.png)







