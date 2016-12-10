#IrDA

##Definição

Infrared Data Association, também conhecido por IrDA, é uma organização internacional que cria e promove padrões de conexão de dados de infravermelho de baixo custo e interoperáveis. Foi criada em 1993 por cerca de 50 empresas e possui um conjunto de protocolos de suporte a uma ampla gama de aparelhos de computação e dispositivos de comunicação. Estes protocolos são tipicamente destinados a fornecer altas velocidades, comunicação de curto alcance em linha de vista e transferência ponto-a-ponto de dados sem fios. Os protocolos IrDA utilizam o IrDA DATA como mecanismo de entrega de dados e o IrDA CONTROL como mecanismo de controlo.[1]

##Motivação

A motivação original da IrDA visa essencialmente fornecer uma tecnologia que possa substituir a utilização de cabos, bem como de outros padrões PAN (rede de área pessoal com fios). A ideia é que dois dispositivos possam comunicar simplesmente apontando-os um para o outro, o que tornaria a utilização de cabos completamente desnecessária. Hoje em dia praticamente todas as pessoas possuem um dispositivo com suporte para comunicação por Infravermelhos. A IrDA estima que existam mais de 300 milhões de dispositivos, tornando a comunicação por Infravermelhos uma das tecnologias sem fios mais difundidas pelo globo terrestre.[2]

##Aplicações

O padrão IrDA CONTROL permite que os dispositivos de hardware, como teclados, ratos, joysticks ou apontadores, interajam com um dispositivo host (que pode comunicar com um máximo de 8 dispositivos ao mesmo tempo) sem utilização de fios. A taxa de transmissão de dados para IrDA CONTROL normalmente atinge um máximo de 75 Kbps, rápido o suficiente para o tipo de dados que são transferidos por esses tipos de dispositivos.[2]

##Especificações

* Alcance de comunicação de até 1 metro, embora uma distância de 2 metros muitas vezes pode ser alcançada.
* Uma opção de baixa potência para comunicação de até 20 centímetros. Isso requer 10 vezes menos energia do que a implementação completa.
* Comunicação bidirecional.
* Transmissão de dados de 9600 bps para uma velocidade máxima de 4 Mbps.

##Protocolos requeridos

Uma pilha de protocolos IrDA é o conjunto de camadas de protocolos das comunicações infravermelhas ponto-a-ponto. Os protocolos de comunicação tratam de várias funcionalidades, e por isso são geralmente partidos em camadas. Cada uma destas camadas lida com um conjunto de responsabilidades e fornece recursos necessários para as camadas acima e abaixo. Quando se colocam camadas sobre outras camadas, obtém-se o que se chama de pilha de protocolos.[4]

As camadas necessárias de uma pilha de protocolos IrDA são as seguintes:

* Physical Layer: Camada física. Especifica características óticas, codificação de dados e enquadramento para várias velocidades;
* IrLAP (Link Access Protocol): Protocolo de Ligação de Acesso. Estabelece a conexão confiável básica;
* IrLMP (Link Management Protocol): Protocolo de Gerenciamento de Link. Multiplexa serviços e aplicativos na conexão LAP;
* IAS (Information Access Service): Serviço de Acesso à Informação. Fornece umas "páginas amarelas" de serviços num dispositivo.

A utilização das camadas opcionais depende da aplicação em particular. Os protocolos opcionais são:

* TinyTP (Tiny Transport Protocol): Protocolo de transporte minúsculo. Adiciona controlo de fluxo por canal para manter as coisas em movimento sem problemas. Esta é uma função muito importante e é necessária em muitos casos;
* IrOBEX (The Object Exchange Protocol): O protocolo de troca de objetos. Fácil transferência de arquivos e outros objetos de dados;
* IrCOMM: Emulação de porta serial e paralela, permitindo que os aplicativos existentes que usam comunicações seriais e paralelas usem o IR sem alterações;
* IrLAN (Local Area Network access): Acesso à rede de área local, permitindo o acesso IR LAN sem fios para laptops e outros dispositivos.

Imagem: http://i.imgur.com/c9Kotc3.png

##Vantagens

Uma das principais vantagens da IrDA a partir da perspetiva de um fabricante de dispositivos é o seu baixo custo. As portas de infravermelhos podem ser incorporadas num dispositivo por valores inferiores a 1€, o que representa um custo muito baixo para a implementação de comunicação sem fios num dispositivo, em comparação com outros padrões WPAN. Para além disto, existem outros benefícios da tecnologia IrDA, como a maior segurança e independência face às ondas de rádio e o facto de os dispositivos serem leves, consumirem pouco e serem fáceis de usar.[3]

##Limitações

O uso de Infravermelhos para transferência de dados é uma excelente ideia, em teoria. No entanto, mesmo com esta ubiquidade, a tecnologia raramente é utilizada para satisfazer a sua intenção original, ou seja, a transferência de dados. Isto porque, para que o IR funcione, os dispositivos de comunicação têm de estar em linha de vista, o que pode ser um problema em vários cenários. Num ambiente de escritório, esta limitação não é prática para muitos periféricos, como impressoras ou scanners, que não mantêm a obrigatoriedade de estarem em linha de vista. Para além deste problema, o Infravermelhos também peca pelo facto de os dispositivos não se poderem mover enquanto a transmissão está em progresso e pela ideia de que a maioria dos utilizadores não tem dois dispositivos com portas IR. Enquanto quase todos os dispositivos portáteis tem suporte para IrDA, a maioria dos desktops não possui esse mesmo suporte, o que limita a eficácia da tecnologia como protocolo de transferência de dados.[2]

##Referências

1- http://www.ericlindsay.com/computer/irda.htm
2- http://etutorials.org/Mobile+devices/mobile+wireless+design/Part+One+Introduction+to+the+Mobile+and+Wireless+Landscape/Chapter+3+Wireless+Networks/Wireless+Personal+Area+Networks+WPANs/
3- http://www.rfwireless-world.com/Terminology/IrDA-advantages-and-disadvantages.html
4- http://www.staroceans.org/DC/HWBooks/USB%20Design%20By%20Example/chapter09/ir/overview.pdf

##Links

https://en.wikipedia.org/wiki/Infrared_Data_Association
https://pt.wikipedia.org/wiki/Infrared_Data_Association
http://www.hardware.com.br/termos/irda
http://www.eix.co.uk/Articles/IrDA/Welcome.htm
http://br.ccm.net/contents/822-wpan-redes-pessoais-sem-fios
