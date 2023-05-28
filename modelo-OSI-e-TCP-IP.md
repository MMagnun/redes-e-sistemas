#  Modelo OSI e TCP/IP

O modelo OSI (Open Systems Interconnection) é uma padronização, um modelo conceitual que serve de base para criar outros modelos. Ele possui 7 camadas¹²³. Já o modelo TCP/IP é baseado em protocolos padrão desenvolvidos para a Internet e está dividido em 4 camadas. Algumas camadas do modelo OSI foram combinadas em uma só¹².

O modelo OSI é conhecido como abordagem horizontal, enquanto o TCP/IP é conhecido como abordagem vertical. O modelo TCP/IP é mais confiável que o modelo OSI. O OSI é independente de protocolo e genérico, enquanto o TCP/IP possui regras padrão que ajudam a desenvolver a Internet¹.

## Modelo OSI
O modelo OSI é composto por 7 camadas. As camadas são: Aplicação (Application), Apresentação (Presentation), Sessão (Session), Transporte (Transport), Rede (Network), Dados (Data Link) e Física (Physical)  .

A camada de aplicação é responsável por fornecer serviços de rede para aplicativos. 
A camada de apresentação é responsável pela tradução, compressão e criptografia dos dados. 
A camada de sessão é responsável por estabelecer, gerenciar e encerrar conexões entre aplicativos. 
A camada de transporte é responsável por fornecer comunicação confiável entre hosts. 
A camada de rede é responsável pelo roteamento dos pacotes. 
A camada de dados é responsável pela transmissão confiável dos pacotes entre dispositivos. 
A camada física é responsável pela transmissão dos bits brutos através do meio físico  .

## TCP/IP e UDP
TCP/IP é um conjunto de protocolos que possibilita a comunicação entre computadores e servidores, formando a Internet. Ele combina o Protocolo de Controle de Transmissão (TCP), responsável pela transmissão de dados, com o Protocolo de Internet (IP), que identifica os computadores e servidores⁴.

O TCP é um protocolo orientado a conexão e exige que os dados sejam consistentes no destino. Ele é usado principalmente em HTTP, HTTPs, FTP, SMTP e Telnet¹. Já o UDP é um protocolo sem conexão e não exige que os dados sejam consistentes ou não precisem que uma conexão seja estabelecida com o host para consistência dos dados. Ele é eficiente para o tipo de transmissão de rede de broadcast e multicast¹.

##Fontes

(1) Diferença entre OSI e TCP/IP - Diferenciario. https://bing.com/search?q=Defini%c3%a7%c3%b5es+para+modelo+OSI+e+TCP%2fIP.
(2) Qual a Diferença entre Modelo OSI e TCP/IP? | DlteC do Brasil. http://www.dltec.com.br/blog/redes/diferenca-entre-modelo-osi-e-tcp-ip/.
(3) Modelos OSI e TCP/IP: Principais Diferenças - Estratégia Concursos. https://www.estrategiaconcursos.com.br/blog/redes-computadores-modelos-osi-tcp-ip/.

(1) O Que é o Protocolo TCP/IP e Como Ele Funciona? - Hostinger. https://www.hostinger.com.br/tutoriais/tcp-ip.
(2) Entenda as diferenças entre os protocolos TCP e UDP. https://www.eletronet.com/blog/entenda-as-diferencas-entre-os-protocolos-tcp-e-udp/.
(3) O DNS funciona em TCP e UDP - Windows Server | Microsoft Learn. https://learn.microsoft.com/pt-br/troubleshoot/windows-server/networking/dns-works-on-tcp-and-udp.
(4) UDP e TCP: qual a diferença e o que é cada Protocolo | Alura. https://www.alura.com.br/artigos/quais-as-diferencas-entre-o-tcp-e-o-udp.
(5) Uma introdução a TCP, UDP e Sockets | Blog TreinaWeb. https://www.treinaweb.com.br/blog/uma-introducao-a-tcp-udp-e-sockets/.
