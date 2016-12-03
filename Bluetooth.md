#Bluetooth

##Definição

O Bluetooth é um tipo de tecnologia WPAN sem fios, que estabelece uma comunicação de curta distância e baixo custo. Tem como objetivo o estabelecimento de conexão e troca de informação entre dispositivos, como telemóveis, computadores, impressoras, câmeras e até consolas de jogos, utilizando para isso uma frequência de rádio de curto alcance. Foi lançada em 1994 pela Ericsson, embora outras companhias como a Nokia, a IBM, a Intel e a Toshiba também se tenham juntado à empresa sueca em 1998, formando um grupo chamado Bluetooth SIG (Special Interest Group), com o intuito de desenvolver, promover e expandir a tecnologia. Nos dias de hoje, milhares de empresas já se juntaram ao grupo, entre elas estão nomes fortes como a Samsung,a Microsoft, a Motorola, a Dell, a HP, a Phillips, a Siemens ou a Texas.

##Especificações

Ao contrário da tecnologia de infra-vermelhos, o Bluetooth não requer obrigatoriamente linha de vista para funcionar, sendo capaz de comunicar através de barreiras físicas. Conta tipicamente com um alcance de 10 metros, embora este valor possa ser amplificado. Opera na faixa de licença-livre ISM (Industrial, Scientific, Medical) a aproximadamente 2,45 GHz, com um débito máximo de 720 Kbps, que se estima que possa ser aumentados para perto dos 10 Mbps, com futuras especificações. O protocolo Bluetooth divide ainda a faixa de 2,45 GHz em 79 canais e muda de canal cerca de 1600 vezes por segundo, de forma a evitar possíveis interferências com outros protocolos que usem a mesma faixa.

##Como funciona?

O Bluetooth é uma tecnologia sem fios, baseada numa camada física de saltos de frequência, que permite que dispositivos portáteis formem redes ad hoc wireless de curto alcance. Isto é, redes sem fios formadas por nós que cooperam entre si para encaminhamento de pacotes na rede. Os hosts Bluetooth não são capazes de comunicar a menos que se tenham previamente descoberto uns aos outros através da sincronização dos seus padrões de tempo e frequência. Assim, mesmo que todos os nós estejam próximos uns dos outros, apenas os nós que estão sincronizados com o transmissor podem ouvir a transmissão. Para suportar comunicação any-to-any, os nós devem ser sincronizados de modo a que os pares de nós, que se podem comunicar uns com os outros, formem um gráfico conectado.

O sistema de saltos de frequência, em que o Bluetooth se baseia, define vários canais para comunicação, sendo que cada canal é baseado numa sequência de salto de frequência diferente. Assim, um grupo de dispositivos que compartilham um mesmo canal é chamado de piconet. Cada piconet tem uma unidade mestre que seleciona uma sequência de salto de frequência para o piconet e controla o acesso ao canal. Os outros participantes do grupo, conhecidos como unidades escravas (slaves), são sincronizados com a sequência de salto do piconet master. Dentro de um piconet, o canal é compartilhado usando um slotted Time Division Duplex (TDD), em que um mestre usa um protocolo de pesquisa para alocar faixas horárias para os nós escravos. O número máximo de escravos que podem ser simultaneamente ativos num piconet é sete. Quando os vários piconets são interconectados, forma-se uma rede wireless chamada scatternet, como ilustrado na figura (http://www.gta.ufrj.br/grad/09_1/versao-final/bluetooth/image5691.jpg). Isto é possível, pois cada piconet utiliza uma sequência de salto diferente, o que faz com que múltiplos piconets possam coexistir numa área comum. Os piconets são então interligados através de uns nós especiais, chamados de nós ponte, que podem ser construídos entre dois nós mestre, como podemos ver na figura (http://images.slideplayer.com/15/4633194/slides/slide_62.jpg), entre um nó mestre e um escravo ou entre dois nós escravos. Dada uma coleção de dispositivos Bluetooth, é necessário um protocolo explícito de construção de topologia para formar piconets, atribuir escravos a piconets e interconectar piconets através de pontes, de modo que o scatternet resultante seja conectado. Tal protocolo deve ser assíncrono, distribuído e pode começar com nós que não têm qualquer informação sobre o seu ambiente.

##Aplicações

##Benefícios

##Versões

##Requisitos

##Bluetooth vs. Wi-Fi

##Links
http://grenoble.ime.usp.br/movel/monografia_bluetooth.pdf
http://etutorials.org/Mobile+devices/mobile+wireless+design/Part+One+Introduction+to+the+Mobile+and+Wireless+Landscape/Chapter+3+Wireless+Networks/Wireless+Personal+Area+Networks+WPANs/
https://pt.wikipedia.org/wiki/Bluetooth
https://www.youtube.com/watch?v=IKAhKJjoa8w
http://pt.slideshare.net/DilumBandara/wireless-personal-area-networks
http://br.ccm.net/contents/822-wpan-redes-pessoais-sem-fios
https://pdfs.semanticscholar.org/1e45/1c35db078fba05cc9b6daf8c21592f98c388.pdf
