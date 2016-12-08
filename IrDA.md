#IrDA

##Definição

Infrared Data Association, também conhecido por IrDA, é uma organização internacional que cria e promove padrões de conexão de dados de infravermelho de baixo custo e interoperáveis. Foi criada em 1993 por cerca de 50 empresas e possui um conjunto de protcolos de suporte a uma ampla gama de aparelhos de computação e dispositivos de comunicação. Estes protocolos são tipicamente destinados a fornecer altas velocidades, comunicação de curto alcance em linha de vista e transferência ponto-a-ponto de dados sem fios. Os protocolos IrDA utilizam o IrDA DATA como mecanismo de entrega de dados e o IrDA CONTROL como mecanismo de controlo.

##Motivação

Hoje em dia praticamente todas as pessoas possuem um dispositivo com suporte para comunicação por infravermelhos. A IrDA estima que existam mais de 300 milhões de dispositivos, tornando a comunicação por infravermelhos uma das tecnologias sem fios mais difundidas pelo globo terrestre. A motivação original da IrDA visa essencialmente fornecer uma tecnologia que possa substituir a utilização de cabos, bem como de outros padrões PAN (rede de área pessoal com fios). A ideia é que dois dispositivos possam comunicar simplesmente apontando-os um para o outro, o que tornaria a utilização de cabos completamente desnecessária.

##Aplicações

Dito isto, existem algumas áreas onde o infravermelho é frequentemente usado. O padrão IrDA CONTROL permite que os periféricos sem fio, como teclados, mouse, almofadas de jogos, joysticks e unidades apontadoras, interajam sem fio com um dispositivo host, muitas vezes um PC de mesa ou uma unidade de jogos. Um dispositivo host pode se comunicar com até oito periféricos simultaneamente. A taxa de transmissão de dados para IrDA CONTROL normalmente atinge um máximo de 75 Kbps, o que é facilmente rápido o suficiente para o tipo de dados que estão sendo transferidos por esses tipos de dispositivos.

##Especificações

* Alcance de comunicação de até 1 metro, embora uma distância de 2 metros muitas vezes pode ser alcançada.
* Uma opção de baixa potência para comunicação de até 20 centímetros. Isso requer 10 vezes menos energia do que a implementação completa.
* Comunicação bidirecional.
* Transmissão de dados de 9600 bps para uma velocidade máxima de 4 Mbps.

##Protocolos requeridos

##Funcionamento

O IrDA foi projetado para conexões ponto a ponto baratas, bidirecionais, de curto alcance e razoavelmente direcionais. Inicialmente até 115,2 kbps através de adições a uma porta serial RS232C, e até 4 Mbps. Eles usam retorno de banda base para zero modulação invertida. O esquema de 4 Mbps usa um esquema de modulação de posição de 4 pulsos de dois bits por impulso.

Controles remotos para TVs e similares são totalmente diferentes. Eles usam aproximadamente 40 kHz sinais e modulação de largura de pulso, com uma variedade de protocolos. Eles são personalizados para baixa velocidade, grande angular, uma forma, conexões de longo alcance. Estes não são compatíveis com IrDA. Você pode encontrar pacotes de transmissores receptores de uma peça para sinais remotos a baixo custo e dirigi-los de TTL. IrDA normalmente não pode fazer sinais de controle remoto de TV, e são de menor alcance, mas muitas vezes você pode falsificar os sinais em software. Conexões de infravermelho para teclados e similares não têm de seguir qualquer padrão, como o fabricante fornece ambas as extremidades da conexão.

##Vantagens

Uma das principais vantagens da IrDA a partir da perspectiva de um fabricante de dispositivos é o custo. As portas IR podem ser incorporadas em um dispositivo para tão baixo quanto $ 1 (EUA). Este é um custo muito baixo para a implementação de comunicação sem fio em um dispositivo em comparação com outros padrões WPAN.

##Limitações

Em teoria, usar IR para transferência de dados é uma ótima ideia. Infelizmente, mesmo com essa ubiquidade raramente é usada para sua intenção original. Isto pode ser devido a desafios técnicos em muitas implementações iniciais, ou mais plausivelmente, à restrição da linha de visão. Para que o IR funcione, os dispositivos de comunicação devem manter a linha de visão. Isto significa que eles têm de situado dentro da faixa de operação (tipicamente até 2 metros de distância), apontar um ao outro, e não têm impedimentos físicos. Na maioria dos ambientes de escritório, essa limitação não é prática para muitos periféricos, como impressoras ou scanners. Usar infravermelho para transferir dados entre dois dispositivos é mais realista. Dois usuários de dispositivos podem usar infravermelho para transferir informações, como cartões de visita eletrônicos, entre si. Usuários com dispositivos Palm chamar este tipo de transferência de transmissão, como em, "Você pode me transmitir suas informações de contato?" Além da transferência de dados de usuário para usuário, infravermelho não é comumente usado para transferência de informações, uma vez que a maioria dos usuários não usam dois dispositivos com portas IR. Enquanto quase todos os dispositivos portáteis têm um, a maioria dos desktops não. Mais uma vez, isto limita a eficácia do IR como um protocolo de transferência de dados do mercado de massa.

##Links

https://en.wikipedia.org/wiki/Infrared_Data_Association
https://pt.wikipedia.org/wiki/Infrared_Data_Association
http://www.hardware.com.br/termos/irda
http://www.staroceans.org/DC/HWBooks/USB%20Design%20By%20Example/chapter09/ir/overview.pdf
http://www.eix.co.uk/Articles/IrDA/Welcome.htm
http://www.rfwireless-world.com/Terminology/IrDA-advantages-and-disadvantages.html
http://www.ericlindsay.com/computer/irda.htm
http://etutorials.org/Mobile+devices/mobile+wireless+design/Part+One+Introduction+to+the+Mobile+and+Wireless+Landscape/Chapter+3+Wireless+Networks/Wireless+Personal+Area+Networks+WPANs/
http://br.ccm.net/contents/822-wpan-redes-pessoais-sem-fios
