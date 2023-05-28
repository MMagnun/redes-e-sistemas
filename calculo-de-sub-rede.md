# Cálculo de Sub Rede

## Classes de Endereço IP
As classes são A, B, C, D e E 

As classes D e E são mais utilzadas por Departamentos governamentais, não muito usadas por usuário final


Ex.: 192.168.10.1 = 11000000.10101000.00001010.00000001 cada grupo possui 8 elementos (8 bits)
192/128=1 e sobra 64. 64/64=0. Como n'ao há restos, os restantes dos ultimos numeros sao 0. 
128 = 2^7 
64 = 2^6
32 = 2^5
16 = 2^4
8 = 2^3
4 = 2^2
2 = 2^1
0 = 2^0

Fórmulas de hosts de redes: 2^b-2
2^8-2 = 254 Hosts disponíveis em rede. 


Sites para ajudar a fazer cáclulos de subnetes

Site24x7 = Calculadora de rede IPV4
https://www.site24x7.com/

Exemplo: 

Bloqueio de Endereço Ip: 192.168.10.0/24 (simbolizando 24bits)
Máscara de sub-rede 255.255.255.0/24
Número de Hosts ou sub-redes 64
Número de sub-redes 4 

É feita as divisões dos Hosts exemplo de ips para 4 hosts: 
____________________________________________________________________________________________________
|Subnet ID     |      Subnet Adress      |         Host Address Range       |     Brodcast Addresss |
|______________|_________________________|__________________________________|_______________________|
|    1         |      192.168.10.0       |    192.168.10.1-192.168.10.62    |    192.168.10.63      |
|______________|_________________________|__________________________________|_______________________|
|    2         |      192.168.10.64      |    192.168.10.65-192.168.10.126  |    192.168.10.127     |
|______________|_________________________|__________________________________|_______________________|      
|    3         |      192.168.10.128     |    192.168.10.129-192.168.10.190 |    192.168.10.191     |
|______________|_________________________|__________________________________|_______________________|    
|    4         |      192.168.10.192     |    192.168.10.193-192.168.10.254 |    192.168.10.255     |
|______________|_________________________|__________________________________|_______________________|      
    
