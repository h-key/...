# Mosquitto-Broker-a-win7-a-Service

install Mosquitto
ok now it will run right?
open :makes Mosquitto Broker a win7 a Service.reg" with notepad or a text editor
this what it says


Windows Registry Editor Version 5.00

[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\services\mosquitto]
"Type"=dword:00000010
"Start"=dword:00000002
"ErrorControl"=dword:00000001
"ImagePath"=hex(2):43,00,3a,00,5c,00,50,00,72,00,6f,00,67,00,72,00,61,00,6d,00,\
  20,00,46,00,69,00,6c,00,65,00,73,00,5c,00,6d,00,6f,00,73,00,71,00,75,00,69,\
  00,74,00,74,00,6f,00,5c,00,6d,00,6f,00,73,00,71,00,75,00,69,00,74,00,74,00,\
  6f,00,2e,00,65,00,78,00,65,00,20,00,72,00,75,00,6e,00,00,00
"DisplayName"="Mosquitto Broker"
"ObjectName"="LocalSystem"
"Description"="MQTT v3.1.1 broker"
"FailureActions"=hex:00,00,00,00,00,00,00,00,00,00,00,00,03,00,00,00,14,00,00,\
  00,01,00,00,00,60,ea,00,00,01,00,00,00,60,ea,00,00,01,00,00,00,60,ea,00,00
"DelayedAutostart"=dword:00000001


this will be added to your Windows Registry
after this you can find it 
Control Panle.....Admin tools....services
it's is "Mosquitto Broker"


Mosquitto Broker runs in the background
