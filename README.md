<body>
  <center>
<h1 align="center">~ 💖 TRAMPO XD 💖 ~</h1>
<br>

```zsh
> lolware1.github.io/me/
```

<h2 align="center">            ~ ATIVAR W7 ~</h2>
se der algm erro: Como fazer a desinstação:
iniciar > painel de controle > windows update > atualizações instaladas (no canto inferior esquerdo da tela) > procura ou pesquisa a update "KB971033" > botão direito e desinstalar. 
Importante também a necessidade de tirar as atualizações automáticas do windows para que este arquivo não volte a ser baixado!
    
<h2 align="center">            ~ ATIVAR W10 ~</h2>
apenas abra o windows porwershell e coloque o seguinte comando:
<p>
    
```zsh
> irm https://massgrave.dev/get | iex
```
logo dps aperte 1 e pronto.

Se nao funcionar, baixe e abre o arquivo "licença digital.cmd" que deixei no github.

<h2 align="center">            ~ ERROS DE FORMATAÇAO ~</h2>
não pode ser instalado no disco estilo partição GPT: na tela inicial, vc vai apertar "shift + F10", vai abrir um cmd, escreva "diskpart", "list disk", "select", "select disk number 0"(ou o ssd), "clean", "convert gpt", "exit", deve funcionar. <p>

Eror: Bios/legacy boot of UEFI-only media
se aparecer isso com o meu pendrive, quer dizer que a vers que eu coloquei no rufus (bgl de instalar o win no pendrive) nao eh compativel com o computador, se isso acontecer vc tera que formatar o pendrive dnv so que no rufus voce vai selecionar o esquema de partiçao "MBR", deve funcionar.

<h2 align="center">            ~ TIRAR SENHA W10/W11 ~</h2>

1. Com o pc ligado na area de colocar a senha, segure o shift e aperte em reiniciar no canto inferior direito.
2. Se voce fez tudo certo vai aparecer a tela de configuraçoes avançadas, voce vai apertar na opçao de abrir o CMD (prompt de comando), com o CMD aberto vai digitar os seguintes comandos:
3. diskpart
4. list vol (aqui agente descobre qual disco precisamos,voce precisa saber qual disco esta instalado o windows)
5. exit
6. "disco com o windows":
exemplo: A: ou E:
7. cd Windows
8. cd system32
9. copy utilman.exe utilman1.exe
10. copy cmd.exe cmd1.exe
11. del utilman.exe
12. rename cmd.exe utilman.exe
13. exit
14. Aperte em continuar, assim o pc vai reiniciar com os arquivos que movemos com o CMD.
15. Depois do pc reiniciar voce vai aperta no "hominho" q fica perto do botao de desligar/reiniciar no canto inferior direito
16. "TUM", um CMD vai aparecer e voce vai ter que digitar mais um comando:
17. control userpasswords2
18. e ta ai, so clicar em redefinir senha e dps disso eh so historia :)

<h2 align="center">            ~ TABELA DE PREÇOS ~</h2>

```csharp
Tabela de preços v2.0.2: 破壊「はかい」
-------------------------------
Formatação Básica Formatação, Instalação Sistema Operacional, Ms Office e Antivírus. R$ 50,00 + 25 por unidade.

Formatação Completa Formatação, Instalação Sistema Operacional, Ms Office, Antivírus, Adobe Reader (PDF), navegador, etc. R$70,00

Instalação de Programa Instalação de Softwares (Básico) - Tempo de instalação até 30 min. R$ 40,00

Instalação de Programa Instalação de Softwares (Avançado) - Tempo de instalação maior que 30 min. R$ 60,00

Remoção de Vírus Remoção de vírus e melhoramento de desempenho. R$ 70,00

Reparação do Sistema Reparação de inicialização do Windows R$ 50,00

Melhoramento de Desempenho Melhoramento do Sistema Operacional R$60,00

Troca de Componentes simples Troca de Memória Ram, Fonte de Alimentação, HD, DVD, SSD etc. R$ 40,00

Troca de Hardware Avançado Troca de Placa Mãe, Processador e Cooler. R$ 70,00

Desmontagem e Montagem Completa, Desmontagem, Limpeza e Montagem Completa. R$ 100,00

Instalação de HD/SSD Troca de HD/SSD + Instalação do Windows R$ 150,00

Troca de Placa de Vídeo Instalação de Placa de vídeo + instalação de Driver R$ 70,00

Limpeza Limpeza Física Interna e Externa, Formatação e Backup R$ 150,00

Montagem de Desktop Cotação de preço + Montagem dos componentes e gabinete + instalação do S.O. + Softwares Básicos. R$100,00

Troca de Bateria Troca de bateria CR2032 R$ 15,00

Configuração de Roteadores Configuração básica de Roteador (Wi-fi, Repetidor, senha) R$ 50,00
```
    
