# COMO A INTERNET FUNCIONA 
A internet é uma rede de redes.

## CONCEITOS BÁSICOS

- **Pacote**: Pequena unidade de dados transmitida pela internet. Um pacote é uma parte fragmentada de um arquivo ou mensagem maior, enviada individualmente e reconstituída no destino.  
- **Roteador**: Dispositivo que direciona pacotes de dados entre diferentes redes. Ele decide a melhor rota para enviar os pacotes de dados para seus destinos.  
- **IP**: Número exclusivo atribuído a cada dispositivo dentro de uma rede, usado para identificar e comunicar com outros dispositivos na rede. O IP pode ser IPv4 ou IPv6.  
- **Nome de Domínio**: Nome legível que identifica um site na internet. Exemplos incluem "google.com" ou "wikipedia.org".  
- **DNS**: Sistema de Nomes de Domínio, responsável por traduzir nomes de domínio em endereços IP, permitindo que navegadores localizem e carreguem sites.  
- **HTTP**: Protocolo de Transferência de Hipertexto, usado para transferir dados entre um cliente (navegador) e um servidor, geralmente em páginas web.  
- **HTTPS**: Versão segura do HTTP, com criptografia SSL/TLS, que protege a integridade e a confidencialidade dos dados trocados.  
- **SSL/TLS**: Protocolos usados para fornecer uma comunicação segura na internet, garantindo que os dados transmitidos entre o cliente e o servidor sejam criptografados e protegidos contra interceptação.  

## Construindo Aplicações Com TCP/IP

Ao criar aplicativos com TCP/IP, é importante entender alguns conceitos-chave:

- **Portas**: Usadas para identificar um serviço ou aplicativo específico em um dispositivo. Cada serviço em execução em um dispositivo utiliza uma porta específica, permitindo a comunicação correta.  
- **Sockets**: Combinação de um endereço IP e um número de porta. Sockets são usados para estabelecer conexões entre dispositivos, permitindo a troca de dados entre aplicativos.  
- **Conexões**: Estabelecidas entre dois sockets quando dois dispositivos desejam se comunicar. Uma conexão TCP é uma via de mão dupla, que precisa ser estabelecida antes que os dados possam ser transferidos.  
- **Transferência de Dados**: Após a conexão ser estabelecida, os dados podem ser trocados entre os aplicativos em execução nos dispositivos conectados.  
