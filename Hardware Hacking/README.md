# Autoestudo de Hardware Hacking

Feito por: [Getúlio Victor](https://github.com/GetulioVictor)

## Emenda

Nesse roadmap será apresentado os conteúdos necessários para aprofundar-se no assunto isso engloba:
- Pré-requisitos
- Conteúdos específicos
- Ferramentas de Hardware e Software

Os conteúdos das semanas 1 a 3 englobam em grande parte os pré-requisitos da área de Hardware Hacking, é indispensável dominar essas habilidades antes de prosseguir nos estudos.
Lembrando que o intuito desse roadmap é apresentar sobre conceitos básicos de Hardware Hacking que devem ser estudados, para especializar nesse área, assim como outros, é preciso de muita dedicação e estudo.

### Semana 1 (Dia 1 - 7)

#### Eletrônica Analógica

Para entender como ataques complexos são realizados é preciso possuir uma base forte em eletrônica, em especial, no que refere-se ao mundo analógico. Entender sobre lei de Ohm, Leis de Kirchoff, Thévenin, funcionamento de Amplificadores, Transistores (TBJs), Capacitores, Transistores de Efeito de Campo (FETs), Análise DC e AC, são apenas alguns dos exemplos dos tópicos abordados em eletrônica analógica. É um conteúdo que exige muita dedicação para dominar, porém caso deseje ter um conhecimento básico sobre o assunto, estudar durante uma semana toda será o suficiente apenas para reconhecer o que será abordado.

### Semana 2 (Dia 8 - 14)

#### Eletrônica Digital

Atualmente o mundo da computação, em sua maioria, é composto por circuitos digitais. Aqui estão alguns exemplos do que se é necessário saber para dominar a eletrônica diigital, podemos citar a álgebra boolenaa, mapa de Karnaugh, circuitos combinacionais, circuitos sequenciais, portas lógicas (AND, OR, NOT, XOR), Latches, Flip-Flops, Registradores, Memória ROM, Memória RAM, Linguagens de Descrição de Hardware (Verilog). 
Podemos observar a aplicação dos sistemas digitais em DLPs, CLPDs, FPGAs, CPUs, GPUs, etc.

### Semana 3 (Dia 15 - 21)

##### Programação em C e Assembly

Após possuir a base em eletrônica analógica e digital é preciso estabelecer bem as bases em programação na linguagem C. A linguagem C é caracterizada pela sua alta velocidade e possiblidade de gerenciar os recursos de memória de modo compreensível aos seres humanos.
Entender como funcionam seus tipos, sintaxe, loops while e for, funções, structs, unions, ponteiros, alocação de memória, listas, pilhas, filas, etx, auxiliam no processo de teste de penetração em dispositovs IoT, na engenharia reversa de dispositivos, dentre outros.
Ao descer mais um nível chegamos na linguagem de montagem (Assembly), indispensável para entender mais a respeito de sistemas de baixo nível e restritos em recursos. O tipo de 'Assembly' pode variar de acordo com a sua arquitetura
como x86 (utilizando amplamente em desktops), ARM (dispositivos móveis) e RISC-V (Reduced Instruction Set Computer V).

Aprender sobre os protocolos de comunicação serial como I2C e UART auxiliaram imensamente nas an

### Semana 4 (Dia 22 - 30)

Após desenvolver toda base em eletrônica e programação podemos abordar os tópicos específicos de Hardware Hacking. Isso inclui explorar mais sobre JTAGs (Joint Test Action Group), Fault Injetctions, Engenharia Reversa em Hardware, Bus Pirate, RF (Radio Frequência), Ataques a nível de PCBs (Placas de Circuito Impresso),
Side Channel Attacks, Ataques baseados em Eletromagnetismo, ChipWhisperer, etc.

## Ferramentas 

### Hardware

- Osciloscópio: Equipamento eletrônico que exibe o sinal analisado ao decorrer do tempo,

- Multímetro: Equipamento utilizado para medições de grandezas como tensão, corrente elétrica, resistência, dentre outros.

- Gerador de Sinais: Equipamento que gera sinais de onde, de diferentes formatos,

- Bus Pirate: Ferramenta multiuso usado em sistemas embarcados que tem como função a análise de protocolos de comunicação, geração de formas de onda, captura de sinais analógicos, dentre outros.

- [Arduino](https://www.arduino.cc/): Plataforma que possibilita a criação de protótipos eletrônicos de modo fácil, barato e acessivel.

- [Raspberry Pi](https://www.raspberrypi.com/): Computador portátil (single-board) com foco em baixo custo, modularidade e design aberto.

- [Proxmark3](https://github.com/Proxmark/proxmark3): Ferramenta utilizada para análise, clonagem e emulação de dispositivos RFID 

- ESP32 MCU: Plataforma de desenvolvimento IoT modular e portátil, baseada no microcontrolador ESP32.

- [HackRFOne](https://greatscottgadgets.com/hackrf/one/) (Rádio definido por Software): Utilizada em testes de segurança, pesquisas com ênffase em comunicações sem fio e radiofrequência, etc. 

- Analisador Lógico: Utilizado para captura e análise de sinais digitais em um sistema. Amplamente utilizado para visualizar e depurar a comunicações entre microcontroladores, memórias, etc. 

### Software

Grande parte dos ataques e análises necessitam das ferramentas em Hardware, porém é preciso possuir um repertório de ferramentas baseadas em Software, pois elas irão automatizar e facilitar
o trabalho em muitas ocasiões. Dentre algumas ferramentas podemos citar:

- Linguagem C 
- GDB 
- KVM
- [Binwalk](https://github.com/ReFirmLabs/binwalk)
- [Firmadyne](https://github.com/firmadyne/firmadyne)
- [Firmwalker](https://github.com/craigz28/firmwalker)
- [Radare2](https://github.com/radareorg/radare2)
- [Python](https://www.python.org/) (Scripts)
- [NMap](https://nmap.org/)
- [Burp Suite](https://www.kali.org/tools/burpsuite/)
- [ZMap](https://zmap.io/)

## Recursos

Nessa secção estão presentes alguns recursos, não se limitem apenas ao que está aqui!

### Videos e Playlists
- [Hardware Hacking - Julio Della Flora](https://youtube.com/channel/UCEyOwgMMfo8aJc4vZm6mYWw) 
- [Binary Freaks - Hardware Hacking Playlist](https://youtube.com/playlist?list=PLL8bstVVO1fCsO46wrpYvgNqXTcDIxy4P) 
- https://youtube.com/playlist?list=PLbuL3Aqx_G3Hh4zn_BK5Cen5zsFI4QRbS 
- [Hardware Hacking Playlist 2](https://youtube.com/playlist?list=PLuyjXiwnBIa3uiLCO9DKNWQcgG_vJ-gaz) 
- [Roadsec - Hardware Hacking](https://youtube.com/playlist?list=PLGdaaZUNDlN6ntfjur2GZPyQiR6-bU2_e) 
- [Neso Academy - Playlists](https://www.youtube.com/@nesoacademy/playlists)  

### Sites

- [Hardware Hacking Training](https://securinghardware.com/articles/BlackHat-Hardware-Training-Roadmap/)
- [Embedded and IoT Security Resources](https://github.com/fkie-cad/awesome-embedded-and-iot-security#readme)
- [Electronics Resources](https://github.com/kitspace/awesome-electronics#readme)
- [Securing Hardware](https://securinghardware.com/)
- [Car Hacking](https://github.com/jaredthecoder/awesome-vehicle-security#readme)

### Livros

#### Eletrônica Analógica
- Introdução à Análise de Circuitos - Robert L. Boylestad
- Dispositivos Eletrônicos e Teoria de Circuitos - Robert L. Boylestad e Louis Nashelsky
- Eletrônica: Volume I  - Albert Malvino e David Bates
- Eletrônica: Volume II - Albert Malvino e David Bates

#### Eletrônica Digital
- Sistemas Digitais: Fundamentos e Aplicações - Floyd
- Sistemas Digitais: Princípios e Aplicações - Ronald J. Tocci, Neal S. Widmer e Gregory L. Moss
- Digital Design and Verilog HDL Fundamentals - Joseph Cavanagh
- Circuitos Digitais, Análise e Síntese Lógica: Aplicações em FPGA - Tales Cleber Pimenta

#### Linguagem C e Assembly
- Low-Level Programming: C, Assembly, and Program Execution on Intel 64 Architecture - Igor Zhirkov
- C Primer Plus - Stepehn Prata
- Linguagem C: Completa e Descomplicada - André Backes
- Beginning X64 Assembly Programming: From Novice to Avx Professional - Jo Van Hoey

#### Hardware Hacking
- IoT Penetration Testing Cookbook – Aaron Guzman e Aditya Gupta
- Hardware Hacking: Have Fun While Voiding Your Warranty –  Joe Grand, Ryan Russell e Kevin Mitnick
- The Hardware Hacker: Adventures in Making and Breaking Hardware – Andrew "bunnie" Huang
- Hacking Exposed Industrial Control Systems: ICS and SCADA Security Secrets & Solutions – Clint Bodungen, Bryan Singer e Aaron Shbeeb
- The IoT Hacker's Handbook: A Practical Guide to Hacking the Internet of Things – Aditya Gupta

### Profissionais e Pesquisadores da área

- [Julio Della Flora](https://www.instagram.com/juliodellaflora/reels/)
- [Andrew "bunnie" Huang](https://github.com/bunnie)
- [Joe Grand](https://www.youtube.com/c/JoeGrand)
- [Colin O'Flynn](https://twitter.com/colinoflynn)
- [Travis Goodspeed](https://twitter.com/travisgoodspeed)
- [Michael Ossmann](https://hackaday.com/tag/michael-ossmann/)
