# Лабораторная работа №5
Настройка безопасного административного доступа


## Часть 1 Конфигурирование основных настроек устройств
 
1.	Топология

![alt-текст][Топология]

[Топология]:https://github.com/b00mmer/lab5/blob/main/Lab5.jpg "Топология"

2. Таблица адресации

![alt-текст][Таблица]

[Таблица]:https://github.com/b00mmer/lab1/blob/main/%D0%A2%D0%B0%D0%B1%D0%BB%D0%B8%D1%86%D0%B0%20%D0%B0%D0%B4%D1%80%D0%B5%D1%81.JPG "Таблица адресации"

3. [Сетевые параметры маршрутизатора R1](https://github.com/b00mmer/lab1/blob/main/R1_running-config.txt)
4. [Сетевые параметры маршрутизатора R2](https://github.com/b00mmer/lab1/blob/main/R2_running-config.txt)
5. [Сетевые параметры маршрутизатора R3](https://github.com/b00mmer/lab1/blob/main/R3_running-config.txt)
6. Сетевые параметры Server 0

`FastEthernet0 Connection:(default port)

 Connection-specific DNS Suffix..: 
 
 Physical Address................: 00E0.A35B.677C 
 
 Link-local IPv6 Address.........: FE80::2E0:A3FF:FE5B:677C 
 
 IPv6 Address....................: :: 
 
 IPv4 Address....................: 192.168.1.3
 
 Subnet Mask.....................: 255.255.255.0
 
 Default Gateway.................: 192.168.1.1
 
 DHCP Servers....................: 0.0.0.0
 
 DHCPv6 IAID.....................: 
 
 DHCPv6 Client DUID..............: 00-01-00-01-91-3B-D8-21-00-E0-A3-5B-67-7C
 
 DNS Servers.....................: :: 
  
 0.0.0.0 
 

 ## Часть 2 Настройка и шифрование паролей на роутерах R1 и R3`

 Проверка доступности роутера R1 с R2 по TELNET  
 
   
  
R2>telnet 10.1.1.1  
Trying 10.1.1.1 ...Open  
  
[Connection to 10.1.1.1 closed by foreign host]  
R2>  
  
После настройки TELNET на VTY 0 4  

  
  
R2>telnet 10.1.1.1  
Trying 10.1.1.1 ...Open  
  
  
User Access Verification  
  
Password:   
R1>  
  
  ## Часть 4 Настройка SSH Server на роутерах R1 и R3


![alt-текст][SSH]

[SSH]:https://github.com/b00mmer/lab1/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA1_4.JPG "SSH Server"



