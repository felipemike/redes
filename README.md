# Objetivo Final

Realizar a criação de duas redes diferentes e estabelecer a comunicação via ICMP entre ambas.

## Rede A (Alunos)
- Endereço IP: 192.168.0.0/24
- Gateway: 192.168.10.254
- DHCP e DNS: 192.168.10.253

Criação de outras 4 máquinas dentro da Rede Interna A utilizando DHCP para desktops e IP fixo para servidores.

## Rede B (Alunos)
- Endereço IP: 172.15.0.254/24
- Gateway: 172.15.0.254
- DHCP e DNS: 172.15.0.253
- Servidor Web: 172.15.0.252

Criação de outras 5 máquinas dentro da Rede Interna B utilizando DHCP para desktops e IP fixo para servidores.

## Equipamentos
- 1 Router 1841
- 3 Switches 2960 24TT

## Explicação

O objetivo final é que um dos desktops da Rede A consiga, por meio de seu navegador interno, acessar o endereço do site do servidor web localizado na Rede B. A página deve ser carregada corretamente, validando assim o roteamento entre as redes, o funcionamento adequado do DNS e a camada de aplicação.
