======================
Glossário de comandos
======================

:Disciplina: Fundamentos de Sistemas Operacionais
:Professor: Jurandy Soares
:Nome: Denisson da Silva Cortês
:Matrícula: 20121144010559
:Data: 03/07/2015

cat
  Para exibir o conteúdo do arquivo na tela.
  
  Ex.: cat [opções] arquivo
  
  Ex.: cat arquivo
  
  Ex.: cat > arquivo (criar arquivo)

cd
  Change directory. Mudar diretório para padrão ou para outro diretório que o usuário queira.
  
  Ex.: cd -- (diretório inicial)
  
  Ex.: cd c4d1g0
  
  Ex.: cd - (volta para o diretório anterior)
  
  
cowsay
  
  Exibe uma vaca (ou outro animal usando -f "formato") com um balão contendo um texto que o foi digitado. 
  
  Ex.: cowsay -f dragon "Mensagem" | write "colega"
  
  Ex.: cowsay ENTER; "Mensagem"; ^D
  
echo
  O comando echo imprime (ou repete) seus argumentos para o termina.
  
  Ex.: echo $USER

env
  Exibe as variáveis de ambiente.
  
  Ex.: env

exit
  Terminar a sessão, ou seja, a shell.
  
  Ex.: exit

help
  Exibe todos os comandos e informações e suas informações, que podem ser utilizados no shell.
  
  Ex.: help

HISTTIMEFORMAT="%d/%m/%y"
  Acrescenta no comando history a data, mês e o ano em que os comandos foram digitados
  
  Ex.: HISTTIMEFORMAT="%d/%m/%y"

hostname
  Exibir o nome da máquina.
  
  Ex.: hostname

ifconfig
  Visualizar os ips da nossa máquina, entre outras funções relacionadas com ips.
  
  Ex.: ifconfig


last
  Indica o último login de utilizadores.
 
  Ex.: last

lastb
  Este comando exibe informações sobre as tentativas mal sucedidas de se logar ao sistema.

  Ex.: lastb

ls
  Listar arquivos que estão presente no diretório atual.
  
  Ex.: ls
  
  Ex.: ls -F
  
  Ex.: ls -F1
  
mkdir
  Criar diretório/pasta.
  
  Ex.: mkdir "Nome da Pasta"

nome="fulano"
  Cria variável.
  
  Ex.: professor="jurandy"

passwd
  Altera a senha do usuário.
  
  Ex.: passwd

pwd
  Present Working Directory. Retorna o diretório atual do usuário.
  
  Ex.: pwd

set
  Define variáveis da sessão, ou seja, da shell, na C shell, na bash ou na ksh.
  
  Ex.: set
  
ssh
  Sessão segura, vem de secure shell, e permite-nos logar num servidor através do protocolo ssh.
  
  Ex.: ssh gabriel@10.209.1.158

tree
  Exibe todos os diretórios, pastas e arquivos em formato de árvore. 
  
  Ex.: tree

tty (TeleTypeWriter)
  Este comando lhe informa qual o nome do arquivo conectado à entrada padrão.
  
  Ex.: tty

vim
  Editor de texto full-screen.
  
  Ex.: vim "nome do arquivo"

wait
  Espera um processo em segundo plano ser completado.
  
  Ex.:

wall
  Exibe uma mensagem ou um texto de um arquivo para todas máquinas interligadas.
  
  Ex.: sudo wall "arquivo"

which
  Mostra o caminho completo de um comando/script.
  
  Ex.: which cat

while
  Estrutura de repetição.
  
  Ex.: while command
       do
        Statement(s) to be executed if command is true
       done

who
  Mostra-nos quem está logado no sistema.
  
  Ex.: who

whoami
  Exibir nome do usuário logado na máquina.
  
  Ex.: whoami

write
  Escrever para outros utilizadores que estejam logados no momento
  
  Ex.: write colega "Mensagem"
       echo "Mensagem" | write colega
       cowsay -f koala "Mensagem" | write colega

Ctrl + L
  Comando responsável por limpar a tela, posicionando o prompt no canto superior esquerdo, para isso, digite: ctrl + l.
  
  
git
  Comando reponsável por informar todos os comandos referentes ao GitHub no terminal. Para visualizar os comandos disponível, digite: git + ENTER.
  
 
 
ssh
  É um programa que permite realizar logon e executar comandos em uma máquina remota. Para logar a uma máquina através de seu 'ip', por exemplo, digite: ssh seunome@ip + ENTER.
  
  
type
  Comando usado para descobrir se o comando é arquivo binário interno ou externo, digite: type comando + ENTER;
  
  
cp
  Comando responsável por copiar arquivos e diretórios. Por exemplo, você possui um arquivo chamado 'imagem1.jpg' e deseja duplicalo, basta digitar: cp imagem1.jpg imagem2.jpg + ENTER. Assim, será criada uma cópia chamada 'imagem2.jpg'.
  Caso seja necessário duplicar uma arquivo para diretórios diferentes, digire: cp ~/Web/Historico/historico.txt ~/Web + ENTER. Nesse caso, o arquivo 'historico.txt', que está no diretório '/Web/Historico', será copiado para o diretório '/Web'.
  Também é possível copiar, por exemplo, vários arquivos de uma mesma extensão, digite: cp ~/pictures/picture-*.jpg ~/picture-backup + ENTER. Nesse caso, todos os arquivos 'picture-' de extensão '.jpg' serão copiados de '/pictures' para '/picture-backup'.
  
  
  
wc -l
  Com este comando é possível contar o número de linhas de um determinado arquivo, digite: wc -l arquivo + ENTER.
  
 
 
pstree
  Comando responsável por mostrar a árvore de processos de um determinado usuário, digite: pstree nomeusuario + ENTER.
  


gunzip
  Comando responsável por descompactar um arquivo, por exemplo, um diretório possui um arquivo compactado 'arquivo.txt.gz' para descompacta-lo, digite: gunzip arquivo.txt.gz + ENTER. Então, será criado um novo arquivo descompactado no diretório chamado: arquivo.txt.
  
  
rm
  Comando responsável por excluir um ou mais arquivos.
  
  Argumentos:
  
  -d, --directory
  
  Remova diretórios, mesmo que eles não estando vazios. Disponível apenas para um usuário privilegiado.

  -f, --force
  
  Remover arquivos protegidos contra gravação sem avisar.

  --help
  
  Imprimir uma mensagem de ajuda e depois sai.

  -i, --interactive
  
  Solicitar y (remover o arquivo) ou n (não remover o arquivo).

  -no-preserve-root
  
  Não trate raiz (/) especialmente. Este é o padrão.

  --preserve-root
  
  Não opere de forma recursiva na raiz (/).

  -r, -R, --recursive
  
  Se arquivo for um diretório, remover todo o diretório e todo o seu conteúdo, incluindo subdiretórios. O uso desta opção pode ser perigoso.

  -v, --verbose
  
  O modo detalhado (imprimir o nome de cada arquivo antes de removê-lo).

  --version
  
  Informação sobre a versão e depois sai.

  -
  
  Marcar o fim de opções. Utilize esta opção quando você precisa fornecer um nome de arquivo que começa com -.
  


sort
  Comando reponsável por organizar linhas de comandos de arquivos.
  
  Argumentos:
  
  -d, --dictionary-order
  
  Classificar em ordem dicionário.
  
  -n
  
  Classificar em ordem aritmética.
  
  -g, --general-numeric-sort
  
  Classificar em ordem numérica geral.
  
  -u, --unique
  
  Linhas idênticas no arquivo de entrada aparecem apenas uma vez na saída.
  
  Exemplos:

  Listar os arquivos por número decrescente de linhas:
  wc -l * | sort -r

  Alfabetizar uma lista de palavras, remova duplicatas, e imprimir a frequência de cada palavra:
  sort -fd wordlist | uniq -c

  Organizar o arquivo de senha numericamente pelo terceiro campo (ID do usuário):
  sort -nk3,4 -t: /etc/passwd
  
  
awk
  É um utilitário responsável por processar arquivos de texto. 
  
  Exemplos:
  
  Cria um arquivo com argumentos concatenados no formato 'string + comando', a partir das informações de histórico armazenadas em outro arquivo.
  
  awk '{print "Comando: " $2}' historico.txt | sort -u > historico2.txt  + ENTER.
  
  Utlizia o mesmo princípio anterior, no entanto, adicionando títulos as colunas de cada argumento.
  
  awk 'BEGIN {printf "%-10s %s\n", "Name", "Number" 
  
  printf "%-10s %s\n", "----", "------"} 
  
  {printf "%-10s %s\n", $1, $2}' historico.txt > historico2.txt + ENTER.
  
  
id
  Comando responsável por mostrar o identificador de usuário na máquina(UID) e o GID(Grupo), digite: id + ENTER.
