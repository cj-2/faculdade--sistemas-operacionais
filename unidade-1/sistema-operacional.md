# Sistema Operacional

O sistema operacional é composto por um conjunto de rotinas chamado kernel ou núcleo do sistema operacional. O kernel é o principal componente dos sistemas operacionais, pois ele é quem faz o gerenciamento dos recursos do computador (MACHADO; MAIA, 2007).

Quando o computador é ligado, o kernel executa programas que inicializam o computador e o conjunto de rotinas é executado ao mesmo tempo sem uma ordem pré-definida.

As principais funções do núcleo são (SIQUEIRA, 2018):

-   tratamento de interrupções e exceções.
-   gerenciamento, sincronização, comunicação e escalonamento de processos e threads.
-   gerenciamento da memória.
-   gerenciamento dos sistemas de arquivos.
-   gerenciamento dos dispositivos de entrada/saída.
-   auditoria e segurança do sistema.

## Arquiteturas dos Sistemas Operacionas

### Sistemas Monolíticos

No sistema monolítico, o sistema operacional é escrito como um conjunto de módulos compilados separadamente e depois agrupados em um arquivo executável, em que cada procedimento pode ser chamado por outro quando precisar, conforme apresentado na figura.

A vantagem do sistema monolítico refere-se à simplicidade e à eficiência em função da integração interna dos componentes, permitindo que os detalhes de hardware sejam explorados. Um exemplo de sistema monolítico é o sistema operacional MS-DOS.

### Sistemas em camadas

O sistema em camadas organiza o sistema operacional como uma hierarquia de camadas construídas umas sobre as outras. Cada camada oferece um conjunto de funções que podem ser utilizadas pelas camadas superiores (TANENBAUM, 2003).

### Máquinas Virtuais

Uma máquina virtual (VM) é similar a uma máquina real. Assim, um nível intermediário é criado entre o sistema operacional e o hardware. Esse nível intermediário cria várias máquinas virtuais independentes, cada qual possuindo uma cópia virtual do hardware. Em um mesmo hardware e em plataformas diferentes podem rodar mais de uma máquina virtual (MACHADO; MAIA, 2007). As principais vantagens das máquinas virtuais são o aproveitamento dos recursos das máquinas, a garantia da segurança e confiabilidade, pois se acontecer um problema com uma máquina virtual, as demais não serão impactadas, além de facilitar a recuperação de dados e backups.

### Modelo cliente-servidor

No modelo cliente-servidor a ideia é implementar a maior parte das funções em modo usuário.

Tudo o que o kernel faz é cuidar da comunicação entre cliente e servidor, conforme apresentado na figura “Modelo do sistema em camadas”, que também apresenta a divisão do sistema operacional em várias partes, como servidor de processos, de terminais, de arquivos e de memória, tornando cada parte gerenciável.

Todos os servidores executam em modo usuário e, com isso, caso ocorra um erro no servidor de arquivos, não impactará nos demais servidores (TANENBAUM, 2003).
