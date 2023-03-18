p>
<br>  Digital Innovation One 
<br>  Segurança da Informação em Python
<br>  Introdução a Socket e cliente TCP/UDP e Server
<br>  Instrutor:  Bruno Dias
<br>  Aluna: Mirian Ajiki Molicawa
<br>  Data: 17/03/2023

<p>

<h2> Tecnologias </h2>
<br> - [x] [Colab](https://colab.research.google.com/)
<br> - [x] Python V3 


<h2> Biblioteca Socket </h2> 

<br> Esta biblioteca fornece acesso de baixo nível à interface de rede, ou seja, o sistema operacional fornece a API interface de Programação de Aplicação socket que <br> relaciona o programa com a rede.

<br> Na rede, a representação de um socket se dá por ip: porta, por exemplo: 127.0.0.1:4477 (IPv4). Um socket que usa rede é um Socket TCP/IP.

<br> Todo cliente deve conhecer o socket do servidor (conjunto ip e porta) para se comunicar, mas o servidor só vai conhecer o socket do cliente quando este realizar <br> uma conexão com ele, ou seja, a conexão no modelo cliente-servidor é sempre iniciada pelo cliente.

<br> Existem quatro tipos de sockets: Stream Sockets, Datagram Sockets, Raw Sockets e Sequenced Packet Sockets
<br> Stream Sockets (SOCK_STREAM): Esse tipo usa TCP/IP, que engloba os protocolos IP (da camada de rede). Deste modo tem-se a garantia da entrega e ordem, orientado à <br> conexão etc;
<br> Datagram Sockets (SOCK_DGRAM): Esse tipo usa UDP User Datagram Protocol (da camada de transporte), portanto, não é orientado à conexão, não garante entrega <br> completa dos dados.

<h2>TCP vs UDP</h2>
<br> Ambos são protocolos da camada de transporte e, quando precisamos de confiabilidade no transporte do dado, usamos o protocolo IP associado ao TCP (que garante a <br> entrega das informações). Quando priorizamos mais velocidade e menos controle, associamos o protocolo IP ao UDP (tráfego de voz e vídeo são bons exemplos onde o <br> UDP teria boa aplicabilidade, ademais, perdendo um ou outro pacote, não interfere totalmente no todo, permanecendo inteligível).

<h2> Conclusão</h2> 

<br> Sockets estão presentes em quase tudo o que fazemos na internet, naquele jogo multiplayer, em algum chat e muito mais. As linguagens de programação (ou extensões <br> delas) abstraem grande parte da programação com sockets.





