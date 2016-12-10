#Bluetooth

##Definição

O Bluetooth, também conhecido por IEEE 802.15.1, é um tipo de tecnologia WPAN sem fios, que estabelece uma comunicação de curta distância e baixo custo. Tem como objetivo o estabelecimento de conexão e troca de informação entre dispositivos, como telemóveis, computadores, impressoras, câmeras e até consolas de jogos, utilizando para isso uma frequência de rádio de curto alcance. Foi lançada em 1994 pela Ericsson, embora outras companhias como a Nokia, a IBM, a Intel e a Toshiba também se tenham juntado à empresa sueca em 1998, formando um grupo chamado Bluetooth SIG (Special Interest Group), com o intuito de desenvolver, promover e expandir a tecnologia. Nos dias de hoje, milhares de empresas já se juntaram ao grupo, entre elas estão nomes fortes como a Samsung,a Microsoft, a Motorola, a Dell, a HP, a Phillips, a Siemens ou a Texas[1].

##Especificações

Ao contrário da tecnologia de infra-vermelhos, o Bluetooth não requer obrigatoriamente linha de vista para funcionar, sendo capaz de comunicar através de barreiras físicas. Conta tipicamente com um alcance de 10 metros, embora este valor possa ser amplificado. Opera na faixa de licença-livre ISM (Industrial, Scientific, Medical) a aproximadamente 2,45 GHz, com um débito máximo de 720 Kbps, que se estima que possa ser aumentados para perto dos 10 Mbps, com futuras especificações. O protocolo Bluetooth divide ainda a faixa de 2,45 GHz em 79 canais e muda de canal cerca de 1600 vezes por segundo, de forma a evitar possíveis interferências com outros protocolos que usem a mesma faixa.[2]

##Como funciona?

O Bluetooth é uma tecnologia sem fios, baseada numa camada física de saltos de frequência, que permite que dispositivos portáteis formem redes ad hoc wireless de curto alcance. Isto é, redes sem fios formadas por nós que cooperam entre si para encaminhamento de pacotes na rede. Os hosts Bluetooth não são capazes de comunicar a menos que se tenham previamente descoberto uns aos outros através da sincronização dos seus padrões de tempo e frequência. Assim, mesmo que todos os nós estejam próximos uns dos outros, apenas os nós que estão sincronizados com o transmissor podem ouvir a transmissão. Para suportar comunicação any-to-any, os nós devem ser sincronizados de modo a que os pares de nós, que se podem comunicar uns com os outros, formem um gráfico conectado.

O sistema de saltos de frequência, em que o Bluetooth se baseia, define vários canais para comunicação, sendo que cada canal é baseado numa sequência de salto de frequência diferente. Assim, um grupo de dispositivos que compartilham um mesmo canal é chamado de piconet. Cada piconet tem uma unidade mestre que seleciona uma sequência de salto de frequência para o piconet e controla o acesso ao canal. Os outros participantes do grupo, conhecidos como unidades escravas (slaves), são sincronizados com a sequência de salto do piconet master. Dentro de um piconet, o canal é compartilhado usando um slotted Time Division Duplex (TDD), em que um mestre usa um protocolo de pesquisa para alocar faixas horárias para os nós escravos. O número máximo de escravos que podem ser simultaneamente ativos num piconet é sete. Quando os vários piconets são interconectados, forma-se uma rede wireless chamada scatternet, como ilustrado na figura (http://www.gta.ufrj.br/grad/09_1/versao-final/bluetooth/image5691.jpg). Isto é possível, pois cada piconet utiliza uma sequência de salto diferente, o que faz com que múltiplos piconets possam coexistir numa área comum. Os piconets são então interligados através de uns nós especiais, chamados de nós ponte, que podem ser construídos entre dois nós mestre, como podemos ver na figura (http://images.slideplayer.com/15/4633194/slides/slide_62.jpg), entre um nó mestre e um escravo ou entre dois nós escravos. Dada uma coleção de dispositivos Bluetooth, é necessário um protocolo explícito de construção de topologia para formar piconets, atribuir escravos a piconets e interconectar piconets através de pontes, de modo que o scatternet resultante seja conectado. Tal protocolo deve ser assíncrono, distribuído e pode começar com nós que não têm qualquer informação sobre o seu ambiente.[3]

##Aplicações

Algumas das aplicações mais relevantes do Bluetooth são:

* Controlo e comunicação entre telemóveis e auscultadores sem fios, ou sistemas de voz para carros
* Comunicação sem fios entre PCs num espaço pequeno, onde uma banda pequena é necessária
* Comunicação sem fios entre PCs e dispositivos de I/O, como ratos, teclados e impressoras
* Substituição de dispositivos tradicionalmente com fios para equipamentos sem fios, como recetores GPS, equipamentos médicos, leitores de código de barras e dispositivos de controlo de tráfego
* Controlo sem fios em consolas de jogos, como Wii e PlayStation
* Acesso à Internet através de um telemóvel
* Envio de fotos de uma câmera para um computador, para poupar memória
* Comunicação entre dispositivos dentro de uma residência, para simples funcionamentos como acender as luzes ou abrir a porta

##Benefícios

Com o Bluetooth as conexões através de cabos tenderão a desaparecer, o que evita o problema da interligação dos cabos de conexão, que muitas vezes não são compatíveis com certos equipamentos. A tecnologia direciona-se para um maior aproveitamento das capacidades de conectividade, podendo-se envolver todos os equipamentos de uma pequena área (fixos e móveis) para interagirem entre si. O consumo de cada transmissor Bluetooth é de aproximadamente 50mA, dentro do limite de 10 metros de distância, o que representa cerca de 3% do consumo total de um telemóvel, valor que é quase irrisório comparado com outras tecnologias sem fios. Este baixo consumo permite que os dispositivos venham já com a tecnologia de fabrico, sem comprometer a autonomia das baterias. Os developers do projeto depressa perceberam que muito mais seria possível fazer aproveitando a tecnologia do Bluetooth. Se transmitir informação entre um computador e uma impressora era uma realidade, também o poderia ser transmitir dados de um telemóvel para uma impressora, ou mesmo entre impressoras. E com o baixo custo de um chip Bluetooth (cerca de 5 euros) e o baixo consumo de energia da tecnologia, o número de aplicações e benefícios da tecnologia rapidamente se tornaram inimagináveis.[2]

##Classes e Versões

O Bluetooth possibilita a comunicação entre dispositivos enquanto estão dentro do raio de alcance. Os dispositivos não precisam de estar em linha de vista um do outro, desde que a transmissão recebida tenha a potência suficiente para a comunicação via rádio funcionar.

Existem atualmente 3 classes da tecnologia, numeradas de 1 a 3. A classe 1 é a mais potente, permitindo consumos até 100 mW com um alcance de 100 metros. A classe 2, por seu lado, possibilita cerca de 2.5 mW de potência máxima, com um alcance de 10 metros. Já a classe 3 permite 1 mW de potência, transmitindo numa distância de cerca de 1 metro.

Versões também exisitam 3 até há pouco tempo, mas recentemente foi lançado o Bluetooth 4, que traz vantagens no consumo de energia, velocidade e segurança, entre outros. A versão 3 era até então a versão com maior taxa de transmissão - cerca de 24 Mbits/s -, enquanto que as versões 2 e 1.2 se ficavam pelos 3 e 1 Mbits por segundo, respetivamente.[1]

##Bluetooth vs. Wi-Fi

Resumidamente, embora o Bluetooth utilize a mesma banda de 2,45 GHz do 802.11b e do 802.11g, o Wi-Fi continua a ser uma melhor opção, já que uma rede Bluetooth é muito mais lenta e, para além de suportar poucos dispositivos, é ainda menos segura. O Wi-Fi, por sua vez, apesar de requerer mais configurações, é melhor para operar redes de alta-escala pelo simples facto de suportar conexões rápidas e seguras com melhor potência de transmissão e receção.[4]

##Referências

[1] https://pt.wikipedia.org/wiki/Bluetooth
[2] http://grenoble.ime.usp.br/movel/monografia_bluetooth.pdf
[3] https://pdfs.semanticscholar.org/1e45/1c35db078fba05cc9b6daf8c21592f98c388.pdf
[4] http://www.diffen.com/difference/Bluetooth_vs_Wifi
