Objetivo Final:
Realizar a criação de 2 redes diferentes e realizar a comunicação via ICMP entre uma e outra.

Rede A (Alunos)
192.168.0.0/24 192.168.10.254 (Gateway) 192.168.10.253 (DHCP e DNS)

Criação de Outras 4 máquinas dentro da Rede Interna A utilizando DHCP para desktops, e IP fixo para Servidores.

Rede B (Alunos)
172.15.0.254/24 172.15.0.254 (Gateway) 172.15.0.253 (DHCP e DNS) 172.15.0.252 (Servidor Web)

Criação de Outras 5 máquinas dentro da Rede Interna B utilizando DHCP para desktops, e IP fixo para Servidores.

Equipamentos:
1 Router 1841 3 Switches 2960 24TT

Explicação:
O objetivo final, é que um dos Desktops da Rede A, consiga colocar em seu navegador interno, o endereço do Site do Servidor WEB que está na REDE B, e a página possa ser carregada corretamente, validando deste modo o Roteamento entre as Redes, DNS e a camada da Aplicação funcionando corretamente.
