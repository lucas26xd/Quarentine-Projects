# :mask: :coffee: :computer: Quarentine-Projects
[![GitHub author](https://img.shields.io/badge/author-lucas26xd-lightgray?style=flat-square)](https://github.com/lucas26xd)
[![GitHub last commit](https://img.shields.io/github/last-commit/lucas26xd/Quarentine-Projects?color=lightgray&style=flat-square)](../../commits/master)
![GitHub repo size](https://img.shields.io/github/repo-size/lucas26xd/Quarentine-Projects?color=lightgray&style=flat-square)
[![GitHub license](https://img.shields.io/github/license/lucas26xd/Quarentine-Projects?color=lightgray&style=flat-square)](LICENSE)
![GitHub top language](https://img.shields.io/github/languages/top/lucas26xd/Quarentine-Projects?color=lightgray&style=flat-square)
![GitHub count language](https://img.shields.io/github/languages/count/lucas26xd/Quarentine-Projects?color=lightgray&style=flat-square)

## Links para os meus pequenos e simples projetos desenvolvidos durante o período de quarentena do novo coronavírus.

## Lista dos projetos
- [#Quarentine Project #0 - Brilho automático](#QP0)
- [#Quarentine Project #1 - Jogo da Forca e Velha](#QP1)
- [#Quarentine Project #2 - Posso sair de casa?](#QP2)
- [#Quarentine Project #3 - Caixa jogo de tabuleiro](#QP3)
- [#Quarentine Project #4 - Extensão WhatsApp Web](#QP4)
- [#Quarentine Project #5 - Urna eletrônica](#QP5)
- [#Quarentine Project #6 - Personalização do README](#QP6)

# <a name="QP0"></a>**Quarentine Project #0** - Ajuste automático de brilho de acordo com a iluminação externa.
### A partir de um sensor LDR conectado a uma Arduino, capta-se a intensidade luminosa da ambiente e altera proporcionalmente o brilho da tela do computador.
![Esquemático](https://www.aranacorp.com/wp-content/uploads/pr-sensor-scheme_bb.png)

# <a name="QP1"></a>**Quarentine Project #1** - Jogo da Forca e Joga da Velha.
### Este projeto foi bastante nostálgico, pois consegui recuperar dois códigos que fiz como trabalho final da disciplina de Programação Computacional em 2015.2. São implementações muito simples feitas em C e com toda interação do usuário feita pelo console. O primeiro conta com um arquivo para ser a base de palavras a serem sorteadas e então executar o jogo da forca como todos conhecem. O segundo código implementa o jogo da forca com dois possíveis modos de jogar: contra um amigo ou contra o computador, escolhendo o local onde deseja marcar o :x: ou :o: pelos números de 1 a 9.
<img src="https://t1.uc.ltmcdn.com/pt/images/7/3/3/jogo_da_forca_29337_0_600.jpg" width="400" alt="HangMan"/> <img src="https://upload.wikimedia.org/wikipedia/commons/8/89/Jogo_da_velha_-_tic_tac_toe.png" width="400" alt="tic-tac-toe"/>

# <a name="QP2"></a>**Quarentine Project #2** - Página simples para passar mensagem clara durante a pandemia.
### A página web é bem simples, apenas HTML e JS, e utiliza uma API de localização simples para pegar o nome da cidade/estado de quem está acessando e revela um meme em forma de gif.
<img src="https://twemoji.maxcdn.com/2/svg/1f637.svg" width="300" alt="Máscara"/>

### Acesse a página pelo link [https://lucas26xd.github.io/possosairdecasa/](https://lucas26xd.github.io/possosairdecasa/).

# <a name="QP3"></a>**Quarentine Project #3** - Controle de caixa de um jogo de tabuleiro.
### Trata-se de uma aplicação para controle de caixa de até quatro jogadores em jogos de tabuleiro baseado no famoso Monopoly.
### Desenvolvi a aplicação baseando-se no jogo de tabuleiro Googolopoly, que é uma versão com mesma jogabilidade do Monopoly.
![Googolopoly Logo](https://pbs.twimg.com/media/CDV5dhTWEAAaFNp.jpg)

### Foram construídas duas aplicações:
- ### Uma Desktop desenvolvida inteiramente na linguagem de programação Java com interfaces gráficas feitas em JFrame e,
- ### Outra simples construída em HTML e Javascript para poder funcionar no seu navegador, tanto em dispositivos móveis quanto em computadores. A página está hospedada em [https://lucas26xd.github.io/Googolopoly/](https://lucas26xd.github.io/Googolopoly/).

# <a name="QP4"></a>**Quarentine Project #4** - Extensão para o Google Chrome.
### A WhatsApp Simple Tools é uma extensão para o Google Chrome ainda não publicada, desenvolvida em Javascript, que conta, até o momento, com dois botões que realizam ações simples na página web no lado do cliente. Como ainda não está na Chrome Store, é necessário a instalação no Chrome como modo desenvolvedor. Abaixo um GIF exemplificando a instalação e suas funcionalidades.
![Tutorial](https://github.com/lucas26xd/WhatsApp-Simple-Tools/blob/master/Instala%C3%A7%C3%A3o%20extens%C3%A3o.gif?raw=true)
### Em resumo, as funcionalidades extendidas são:
- ### **Aceleração da taxa de reprodução dos áudios.** Contando com 5 níveis de aceleração dos áudios. Dê adeus aos custosos áudios recebidos.
- ### **Alternancia entre tema claro e escuro no WhatsApp Web.** Onde utiliza sua conta logada no Chrome para salvar a ultima configuração feita, assim toda vez que você reabrir a página, a extensão já lhe devolverá com a configuração de sua preferência.

# <a name="QP5"></a>**Quarentine Project #5** - Urna eletrônica criada em 2014.
### Mais um momento nostálgico revendo este código. Este projeto inicialmente foi desenvolvido em meados de 2014 juntamente com um amigo durante o ensino médio. Trata-se de uma urna eletrônica para computar os votos em uma eleição para o grêmio estudantil. A mesma foi desenvolvida inteiramente na linguagem de programação Java, mas também conta com um funcionalidade de comunicação com um Arduino que serve, para o mesário da seção, desbloquear os botões da tela principal da urna para o próximo votante, evitando assim multiplos votos de um mesmo indivíduo.
<img src="https://www.opiniaomt.com.br/wp-content/uploads/2018/02/urna-eletr%C3%B4nica.jpg" width="400" alt="Urna Eletrônica"/>

### Também é possível visualizar os votos parciais computados no banco de dados e gerar um relatório como comprovante.

# <a name="QP6"></a>**Quarentine Project #6** - Criação de emblemas simples personalizados para o repositório.
### Criei este projeto como forma de primeiro contato com criação de interfaces gráfica com PyQt5 e como forma de padronização das documentações de meus repositórios.
### O código foi desenvolvido inteiramente em Python, onde o usuário passando apenas seu usuário no GitHub e qual repositório o mesmo deseja personalizar. Então o usuário pode escolher algumas configurações para os emblemas como estilo e cor. Ao clicar no botão OK o código de criação dos emblemas em MarkDown é criado.
### Segue o exemplo dos emblemas do repositório.
[![GitHub author](https://img.shields.io/badge/author-lucas26xd-brightgreen?style=flat-square)](https://github.com/lucas26xd)
[![GitHub last commit](https://img.shields.io/github/last-commit/lucas26xd/Easy-Badges-MD?color=brightgreen&style=flat-square)](../../commits/master)
![GitHub repo size](https://img.shields.io/github/repo-size/lucas26xd/Easy-Badges-MD?color=brightgreen&style=flat-square)
[![GitHub license](https://img.shields.io/github/license/lucas26xd/Easy-Badges-MD?color=brightgreen&style=flat-square)](LICENSE)
![GitHub top language](https://img.shields.io/github/languages/top/lucas26xd/Easy-Badges-MD?color=brightgreen&style=flat-square)
![GitHub count language](https://img.shields.io/github/languages/count/lucas26xd/Easy-Badges-MD?color=brightgreen&style=flat-square)
#### Ps.: A aplicação também foi usada para criação de todos os emblemas desta leva de projetos de quarentena, como este próprio repositório.