========== Instalador_Card_Manager  ==========

------------------------
--- Card_Manager_API ---
------------------------

Card_Manager � uma biblioteca para manipula��es b�sicas
sobre um baralho de cartas comum.
O seu deck � composto por 52 cartas.

Opera��es b�sicas s�o:
 - Ver baralho, consultar quantidade, embaralhar, 
 - Criar monte de descarte, mover cartas do in�cio ao fim,
 - do fim ao in�cio e cortar deck ao meio.

-----------------------------
--- Requisitos de Sistema ---
-----------------------------

Java 1.5 ou vers�o superior => [http://www.java.com/pt_BR/download/]
IzPack 4.3.5 ou vers�o superior => [http://izpack.org/downloads/]
  Certifique-se que o diret�rio 'bin' do IzPack est� no 'path' 
  de execu��o de seu sistema, por exemplo: 

	;C:\Program Files\IzPack\bin
 
 Reinicie seu sistema operacional apos a inclus�o do caminho no 'path'.

Mem�ria:
  N�o h� um m�nimo estipulado.
Disco:
  N�o h� um m�nimo estipulado.
Sistema Operacional:
  Multplataformas, 
Internet:
  N�o � necess�rio uma conex�o com a Internet.
  
--------------------------------
--- Composi��o da Biblioteca ---
--------------------------------

  A biblioteca � composta dos seguintes arquivos .java:
  - Baralho_Cartas.java
  - Carta.java

  O arquivo 'Jogador.java' � uma classe-java que faz uso das funcionalidades da biblioteca.

-------------------------------
--- Instalando a Biblioteca ---
-------------------------------
 
1) Abra uma janela DOS-cmd(Windows) ou Terminal(Unix),

2) Navegue at� o diret�rio raiz do projeto e digite:
 
	compile install.xml -b . -o install.jar -k standard
	
3) Aguarde alguns segundos, apos a gera��o do arquivo 'install.jar', 
de um clique duplo sobre ele e execute a instala��o seguindo os passos da GUI.

========== Instalador_Card_Manager  ==========