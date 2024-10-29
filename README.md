# C115 - MININET
 MININET
1. Criação da topologia com o comando
 - sudo mn --topo tree,depth=4,fanout=2 --link tc,bw=25
![Captura de tela 2024-10-21 204818](https://github.com/user-attachments/assets/6cc61231-6d82-4054-b0f3-4cd595436a20)
 


2. Inspeção de informações das interfaces, endereços MAC, IP e portas
   - h1 ifconfig -> Para listar as interfaces de um host
   - dump -> Para visualizar o IP de todos os hosts:

![Captura de tela 2024-10-21 204957](https://github.com/user-attachments/assets/55284276-d813-4ff4-aa38-3b891bb7a5aa)


3. Testes de ping entre diferentes nós

![Captura de tela 2024-10-21 205026](https://github.com/user-attachments/assets/fdc0b57e-90e1-4951-b192-c621c3ff5df9)

5. Configuração de servidor e cliente TCP usando iperf

h1 iperf -s -p 5555

h2 iperf -c h1 -p 5555 -t 10 -i 1

![Captura de tela 2024-10-21 205227](https://github.com/user-attachments/assets/22529b61-56a4-41a5-ad08-9723db157285)

![Captura de tela 2024-10-21 204935](https://github.com/user-attachments/assets/e319b4f0-5e69-439a-bcb5-fb7cce9c0455)




