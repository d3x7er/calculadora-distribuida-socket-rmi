# calculadora-distribuida-socket-rmi
Calculadora distribuida usando Sockets e RMI

Disciplina de Sistemas Distribuídos - FACAPE

O projeto é composto de algumas etapas, que foram avaliadas separadamente e também em conjunto.

O sistema/programa foi desenvolvido em Java e executado no Linux/ Windows.

O sistema é composto de:
- um servidor concorrente principal que recebe requisições via socket e encaminha as mesmas, via RMI para servidores zumbis
- servidores zumbis que se registram no servidor principal e serão encarregados de realizar as operações
- algoritimo para decisão para escolha do servidor zumbi
- servidores zumbis especializados que receberão requisições específicas, delegadas pelos servidor principal
- clientes que farão requisições para o servidor principal
- As 4 operações básicas devem ser executadas nos servidores zumbis básicos
- As operações de Porcentagem, raiz quadrada e potenciação devem ser executadas nos servidores zumbis especiais

Equipe: Williaan Souza (dex_tter), Lairson Angelo, Jadson Martins, Gustavo Rogrigues e Lucas Felipe.