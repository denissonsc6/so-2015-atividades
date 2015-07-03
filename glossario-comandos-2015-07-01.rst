======================
Glossário de comandos
======================

:Disciplina: Fundamentos de Sistemas Operacionais
:Professor: Jurandy Soares
:Nome: Arthur Gabriel Matias Lima da Silva
:Matrícula: 20121144010605
:Data: 01/07/2015

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

