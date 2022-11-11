  
  
  Descoberta de host ao vivo do Nmap


Quando queremos segmentar uma rede, queremos encontrar uma ferramenta eficiente para nos ajudar a lidar com tarefas repetitivas e responder às seguintes perguntas:

1- Quais sistemas estão ativos?
2- Quais serviços estão sendo executados nesses sistemas?
A ferramenta em que contaremos é o Nmap. A primeira pergunta sobre encontrar computadores ativos é respondida nesta sala. Esta sala é a primeira de uma série de quatro salas dedicadas ao Nmap. A segunda pergunta sobre descobrir serviços em execução é respondida nas próximas salas do Nmap que focam na varredura de portas.

Esta sala é a primeira de quatro desta série Nmap. Essas quatro salas também fazem parte do módulo Network Security.

1- Descoberta de host ao vivo do Nmap
3- Nmap Basic Port Scans
4- Varreduras Avançadas de Portas do Nmap
5- Nmap Post Port Scans
Esta sala explica os passos que o Nmap realiza para descobrir os sistemas que estão online antes do escaneamento de portas. Esse estágio é crucial porque tentar fazer a varredura de portas offline em sistemas apenas desperdiçará tempo e criará ruído desnecessário na rede.

Apresentamos as diferentes abordagens que o Nmap usa para descobrir hosts ativos. Em particular, cobrimos:

Varredura ARP : Esta varredura usa solicitações ARP para descobrir hosts ativos
Varredura ICMP: Esta varredura usa solicitações ICMP para identificar hosts ativos
Verificação de ping TCP /UDP: Esta verificação envia pacotes para portas TCP e portas UDP para determinar hosts ativos.
Também apresentamos dois scanners, arp-scane masscan, e explicamos como eles se sobrepõem com parte da descoberta de host do Nmap.

Como já mencionado, a partir desta sala, usaremos o Nmap para descobrir sistemas e serviços ativamente. O Nmap foi criado por Gordon Lyon (Fyodor), um especialista em segurança de rede e programador de código aberto. Foi lançado em 1997. Nmap, abreviação de Network Mapper, é um software livre e de código aberto lançado sob licença GPL. O Nmap é uma ferramenta padrão do setor para mapear redes, identificar hosts ativos e descobrir serviços em execução. O mecanismo de script do Nmap pode estender ainda mais sua funcionalidade, desde serviços de impressão digital até a exploração de vulnerabilidades. Uma varredura do Nmap geralmente segue as etapas mostradas na figura abaixo, embora muitas sejam opcionais e dependam dos argumentos de linha de comando que você fornece.

