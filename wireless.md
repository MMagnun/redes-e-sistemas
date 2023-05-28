# Wireless
## Wireless
de 20 MHz  60 MHz 
Atualizar firmware e definir configurações de segurança, matendo níveis de segurança elevados; 

Configurando uma rede no Cisco Packet Tracer

Projeto: 
Será criada uma rede com o Cisco Packet Tracer
A rede será criada num switch, conectado num roteador, conectado numa rede em outro switch. 

A rede foi criada e testada. 
Foi criada uma rede A contendo um computador e um notebook com as respectivas configurações de rede: 

Rede A
Computador A
Ip: 192.168.10.2
Mask sub-rede: 255.255.255.0
Gateway: 192.168.10.1
DNS: 8.8.8.8

Notebook A
Ip: 192.168.10.3
Mask sub-rede: 255.255.255.0
Gateway: 192.168.10.1
DNS: 8.8.8.8

switch interface 0/0: 192.168.10.1
switch interface 0/1: 192.168.10.1
Subnet Mask: 255.255.255.0

Rede B
Computador B
Ip: 192.168.11.2
Mask sub-rede: 255.255.255.0
Gateway: 192.168.11.1
DNS: 8.8.8.8

Notebook A
Ip: 192.168.11.3
Mask sub-rede: 255.255.255.0
Gateway: 192.168.11.1
DNS: 8.8.8.8

Foram realizados testes de envio de mensagens entre as máquinas na mesma rede e em rede isolada. 
Os testes obtiveram êxito. 