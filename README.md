# C115 - MININET
 MININET
1. Criação da topologia com o comando
 - sudo mn --mac --topo tree,depth=4,fanout=2 --link tc,bw=25

![criandotopologia](https://github.com/user-attachments/assets/9206c691-c6f4-4b54-95b3-c4277b4c274e)

2. Inspeção de informações das interfaces, endereços MAC, IP e portas

   - h1 ifconfig -> Para listar as interfaces de um host

![Captura de tela 2024-10-30 114725](https://github.com/user-attachments/assets/ae6f63f7-feb6-4579-aa58-841af18e0b16)

![Captura de tela 2024-10-30 114823](https://github.com/user-attachments/assets/839cf670-80ed-458e-a67d-86ec24c51fb1)

![Captura de tela 2024-10-30 114848](https://github.com/user-attachments/assets/c715ba56-67a6-45db-b01d-1fbcd317c14c)

![Captura de tela 2024-10-30 114911](https://github.com/user-attachments/assets/61521a98-458a-4ec7-8012-0665a4b9c9d6)


![Captura de tela 2024-10-30 114935](https://github.com/user-attachments/assets/b3e11312-2bb8-410d-95e4-ab56c7ac2635)


![Captura de tela 2024-10-30 114952](https://github.com/user-attachments/assets/61896c78-faef-46fd-9fed-6a7135e8de8b)


![Captura de tela 2024-10-30 115006](https://github.com/user-attachments/assets/7aaa4676-b50d-4ccc-ab57-f2f33a361cef)


![Captura de tela 2024-10-30 115022](https://github.com/user-attachments/assets/17d9ae75-f74d-4c0f-9594-359d0001c5ff)

![Captura de tela 2024-10-30 115040](https://github.com/user-attachments/assets/80ab7d91-3bc5-4267-831e-22edde9e1acb)


   


  - dump -> Para visualizar o IP de todos os hosts:

![DUMP](https://github.com/user-attachments/assets/e5ae9185-7c39-449d-8304-bb6fa1c6b39f)
  - net -> Para visualizar a conectividade entre os nós, incluindo endereços IP e portas conectadas:

![NET](https://github.com/user-attachments/assets/558ba49b-c60d-4071-82df-1c4907a0d220)

  - nodes -> Para listar todos os nós (hosts, switches e controlador) na topologia:

![NODES](https://github.com/user-attachments/assets/246641df-4644-4599-ba3a-364f048cbca5)

 - Testes de ping entre diferentes nós

![PINGALL](https://github.com/user-attachments/assets/9c6c6e28-5d47-4861-a848-9b694b61bdb1)


3. Configuração de servidor e cliente TCP usando iperf



![printtcp](https://github.com/user-attachments/assets/d752b952-7121-451d-90b4-651d9cdbd800)






