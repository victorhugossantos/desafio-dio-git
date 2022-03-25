### Introdução ao Tema

- Primeiro domínio criado: https://symbolics.com/

- Primeiro Blog: Open Diary

- Primeira compra feita pela internet: CD de Sting(Ten Summoner's Tales) 11/08/94

- site mais antigo em atividade: NORDUnet

***

#### O que são redes !?

##### Backbone

- Espinha dorsal
- Costelas
- Poucas
- Espalhadas pelo mundo

##### Provedor de acesso

- Empresas telefônicas
- Contratam o sinal do backbone e o repassam ao usuário final

###### Provedor de serviço

- Dial-up
- ADSL (banda larga)
- Fibra Ótica
- Rádio
- Satélite
- Móvel
- P2P (peer to peer)

###### Caminho inverso

- www
- DNS
- IP
- Classes de redes
- 127.0.0.1

****

#### TCP/IP, portas, roteadores, switches e modems

##### TCP/IP

- Protocolos de comunicação entre computadores em rede
  - Transmission Control Protocol - Protocolo de Controle de Transmissão
  - Internet Protocol- Protocolo de Internet

- Modelo de camadas
  - 4 camadas
    1. Física (ex.: placa de rede)
    2. Rede (ex.: IP)
    3. Transporte(ex.: TCP, UDP)
    4. Aplicação (ex.: FTP, SMTP, HTTP)

###### TCP x UDP

- UDP
  - Rápido
  - Não confiável
  - Carro do ovo
  - Livestream
- TCP
  - Voltado à conexão
  - Handshake
  - Integridade, ordem dos dados
  - Aplicativo de mensagens de texto

##### Portas

- As "portinhas" por onde dados sairão e chegarão
- 20: FTP
- 22: SSH
- 25: SMTP
- 53: DNS
- 80: HTTP
- 443: HTTPS

##### Modem

- Modulator-demodulator
- Hardware que converte dados em um formato que possa ser transmitido de um computador para outro e lido por outro

##### Roteador

- Distribui internet para um ou mais dispositivos de uma rede
- Pode fazer a comunicação entre redes
- Pode ser "burro"

##### Switch

- Distribui internet para um ou mais dispositivos de uma rede
- Criado para ser "inteligente"

###### Exercícios

Portas Gmail: 25, 465, 587

Portas MySql: 3306

Portas Apache: 433

****

#### Celular, Internet e outros dispositivos

##### SMS

- Quanto custa, para uma operadora de telefonia móvel, enviar um SMS ?
  - 0. Nada. Vazio. null
- O celular troca, naturalmente, alguns bits com as torres de comunicação

##### MMS

- Transmissão de mensagens multimidia(áudio, vídeo) por meio de uma espécie de conexão de dados primitiva.

##### Conexões móveis

- 1G (analógico): 10Kbps
- 2G (digital) (GSM (Global System for Mobile Communication)) : 97Kbps
- GPRS (General Packet Radio Service) / "2.5G": 32 - 80 Kbps - dados + voz
- EDGE (Enhanced Data Rates for GSM Evolution) / "2,75G" : 128- 236 Kbps
- 3G (7Mbps), 4G(22,1 Mbps), 5G (10Gbps)

##### Wi-Fi

- IEEE 802.11: 2,4 GHz, 2Mbps
- IEEE 802.11a: 5 GHz, 54Mbps
- IEEE 802.11b: 2,4 GHz, 11Mbps (diminuição de interferência)
- IEEE 802.11g: 2,4GHz, 54Mbps
- IEEE 802.11n: 2,4GHz/5 GHz, 150-600Mbps

##### Segurança

- WEP: chaves de 64 bits e de 128 bits
- WPA: chave trocada periodicamente
- WPA2 (AES) (802.11i)
  - +segurança
  - +processamento

##### Dispositivos na rede

- Impressora
- Scanner
- Chromecast

##### Bluetooth

- Conexão ponto-a-ponto

  Classe | Potência máx | Alcance

  ----------|---------------------|------------ 

  1			 100mW				100m

  2			  2,5mW				 10m

  3			  1mW					1m

---

#### Browser, sites, aplicativos e webserver

##### Browser

- Sabe identificar várias LP, linguagem de marcação e conteúdo multimedia
- Hoje, os browsers fazem muito mais que isso: existem plug-ins, ou add-ons, que ajudam na navegação
- Cache e cookies

##### Site

- Página da Internet
- Diversos propósitos
- Podem ser feitas em diversas LP
- D/XHTML caindo em desuso

##### Aplicativo

- Um software que é executado no navegador
- Um aplicativo de celular, muitas vezes, nada mais é do que uma espécie de navegador
- Hoje em dia, já quase não existe diferença entre site e aplicativo, e o primeiro está em declínio
- Outro diferença terminológico que está sumindo é entre programa/software e aplicativo

##### E-commerce

- "e", assim como um "e-mail", significa "electronic"
- Comércio eletroônico
- Site de compra e venda com sistema de pagamento
- PicPay, Boleto, PagSeguro, PayPal, Mercado Pago

##### Web-server

- Existem 2 tipos: estático e dinâmico
  - Estático: Servidor físico onde são armazenados arquivos, softwares, e/ou banco de dados
  - Dinâmico: Softwares que estão presentes no servidor fisico

###### Web-server dinamico

- Arquivos (file server)
- Aplicações (application server)
- Banco de dados (database)
- Tudo junto e misturado
- Um site, ou aplicativo, precisa estar hospedado em um servidor para poder ser acessado
- Os dados de um site precisam estar em um servidor
- O  banco de dados de um site ou aplicativo precisa estar em um servidor

##### Web-service

- Interface disponível para fazer requisições e consultas em banco de dados inacessíveis (Correios, Governo)

---

#### Stacks

##### O que é

- Pilhas de tecnologia
- Conjunto de softwares necessários e suficientes para executar um aplicativo/programa
- Linguagens de programação
- Ambientes e ferramentas de interação com o app/sw
- Capacidade e limitação de performance
- Pontos fortes e fracos do app/sw

##### Importância

- Os líderes de projetos precisam das informações das equipes de desenvolvimento
- Os desenvolvedores precisam saber as limitações e capacidades das ferramentas e ambientes que têm disponíveis
- Sistemas, bancos de dados, linguagens de programação, protocolos de comunicação
- Estratégias de negócios
- Maturidade
- Contratações, planos de mitigações de riscos, aumento da capacidade, uso dos dados

##### Front-end

- "Parte da frente"
- Site, software, aplicativo, web service
- Interface, UI, UX
- Lógica de programação, HTML, CSS, jQuery/JS/AJAX, PHP, Bootstrap/outros frameworks

##### Back-end

- "Partes de trás"
- Servidores, bancos de dados
- "meio-de-campo" entre interface e bancos de dados, regras de negócios, validações
- MySQL, Oracle, protocolos de comunicação, PHP, Java, node.js

##### Full Stack

- Profissional que sabe trabalhar em todas as camadas das tecnologias de desenvolvimento/execução de um app/sw

---

#### LPs e termos

##### Principais linguagens

- HTML
- CSS
- JavaScript (JQuery, AJAX, diversas libs)
- PHP
- .NET
- ASP
- Java
- Ruby (on Rails)
- Python
- Perl
- C/C++/C#
