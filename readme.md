# Preparação de Ambiente
### Vamos preparar o ambiente para desnvolvimento de aplicações

#### Neste ambiente iremos instalar e configurar os seguintes recursos:
 - Marquina Virtual(Virtualbox)
 -Distribuição Linux (Ubuntu serve)
 Nasm
 - Compilador da limguagem C
 - configurar o ip e a porta de comunicação entre a máquina real e a virtual
 - Configurar o acesso via SSH entre o VScode e o ServidorLinux
 -Instalar as extensões: Material Icon, Nasm, SSH e Linguagem C/C++

 #### Máquina Virtual(Virtualbox)

 !["Logo VirtualBox"](virtualbox_png.png)

 Máquina Virtual é uma ferramenta que permite a criação de novos "computadores" e a instalação de sistemas operacionais, para estudo ou trabalho.

 Para o nosso estudo iremos usar o VirtualBox, da Oracle.
 Para instalar, basta fazer o download no link a seguir:
 <a href="https://www.virtualbox.org/wiki/Downloads" target="_blank">VirtualBox </a>

 ##### Criando a máquina Virtual para o nosso estudo 

 - Configuração
   > - Nome da Máquina: Servidor
   > - Memória: 4GB(4096)
   > - Processador: 2
   > - Disco: 100GB
   > - IP e Porta do Host: 127.0.0.1 e 22
   > - IP e Porta do convidaddo: 10.0.2.15 e 22
   
   - tela inicial de configuração
<img src=telainicial1.png width=500 height=400>
 
- tela de configuração do hardware
<img src=telaconfig2.png width=850 height=300>
 
 
 
- tela de configuração do disco
<img src=telaconfig3.png width=850 height=300>
 
 
- tela de configuração final
<img src=telaconfig4.png width=850 height=300>
 
- tela de configuração de rede
<img src=telaconfig5.rede.png width=550 height=400>
 
- tela de configuração do ip e das portas
<img src=telaconfig6.rede.png width=950 height=50>

#### Distribuiçao Ubuntu Server

<img src=ubuntu-2.png width=200 height200>

Para o nosso estudo iremos utilizar uma distribuição linux para servidores chamada Ubuntu.
Acompanhe o processo de instalação:

Faça o download aqui:
<a href="https://ubuntu.com/download/server"target="_blank">ubuntu Server </a>

- Acompanhe a instalação

-Tela de inicio de instalação
<img src=telaservidor1.png width=550 height=400>

- Tela de seleção de idioma
<img src=telaserver2.png width=550 height=400>

- Tela de seleção de teclado
<img src=telaservidor3.png width=550 height=400>

- Tela de tipo de instalação
<img src=telaservidor4.png width=550 height=400>

- Tela configuração de rede
<img src=telaservidor5.png width=550 height=400>

- Tela configuração do proxy
<img src=telaservidor6.png width=550 height=400>

- Tela pacotes de atualização
<img src=telaservidor7.png width=550 height=400>
- Tela configuraçao do disco
<img src=telaservidor8.png width=550 height=400>
- Tela configura do usuario
<img src=telaservidor.configuraçãodo.disco9.png width=550 height=400>

- Tela configuração do ssh
<img src=telaservidor1.png width=550 height=400>
- Tela do fim da instalação 