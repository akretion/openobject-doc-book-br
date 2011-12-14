
.. index::
   single: Real Case

.. _ch-real:

***********************************
How does it apply to your Business?
***********************************

 *Agora que voc� descobriu algumas das muitas possibilidades de OpenERP de uma turn� do
  banco de dados de demonstra��o, voc� ir� desenvolver um caso real. Um banco de dados vazio proporciona o ponto de partida
  para testar um fluxo de trabalho cl�ssico de vendas de produtos para compra,
  completar a sua visita guiada e se familiarizar com seu OpenERP.*

Um banco de dados carregado com dados de demonstra��o � muito �til para compreender OpenERP geral do
capacidades. Mas para explorar OpenERP atrav�s de uma lente de necessidades de sua pr�pria empresa, voc� deve come�ar
com um banco de dados vazio. Voc� vai trabalhar neste cap�tulo sobre um banco de dados m�nimos que n�o contenham
dados de demonstra��o, de modo que n�o h� confus�o sobre o que voc� criou. Voc� vai manter o
banco de dados que voc� criou, para que voc� possa construir sobre ela todo o resto deste livro
se voc� quiser.

Voc� ir� desenvolver um caso real atrav�s das fases seguintes:

	#. Especificar um caso real;

	#. Descrever as necessidades funcionais;

	#. Configurar o sistema com os m�dulos essenciais;

	#. Realizar o carregamento de dados necess�rios;

	#. Testar o sistema com seu banco de dados.

TO caso � deliberadamente simples para lhe fornecer uma base para o mais complexo
situa��es voc� pode ter que lidar em sua empresa. Ao longo deste cap�tulo, assumimos que voc� acessa o OpenERP atrav�s sua interface web. E admitindo-se tamb�m (como no restante deste livro) que voc� est� usando a �ltima vers�po baixada do OpenERP (vers�o 6), a vers�o de produ��o est�vel no momento de escrever (n�o a vers�o do tronco, o que � prov�vel que tenha recursos novos e potencialmente inst�vel).

.. raw:: html

    <div class="all-toctree">

.. toctree::

    1_3_Real_Case_use_case
    1_3_Real_Case_db_setup
    1_3_Real_Case_testing_wf

.. raw:: html

    </div>

.. Copyright � Open Object Press. Todos os direitos reservados.

.. Voc� pode levar c�pia eletr�nica desta publica��o e distribu�-lo se voc� n�o
.. mudar o conte�do. Voc� tamb�m pode imprimir uma c�pia para ser lido somente por voc�.

.. Temos contratos com editoras diferentes em pa�ses diferentes para vender e
.. distribuir vers�es em papel ou eletr�nicas baseadas deste livro (traduzido ou n�o)
.. em livrarias. Isso ajuda a distribuir e promover os produtos OpenERP. Tamb�m
.. nos ajuda a criar incentivos para pagar os colaboradores e autores com
.. os direitos do autor com essas vendas.

.. Devido a isso, concede a traduzir, modificar ou vender este livro � estritamente
.. proibido, a menos que Tiny SPRL(representando Open Object Press) lhe der uma
.. autoriza��o por escrito para isso.

.. Muitas das designa��es usadas pelos fabricantes e fornecedores para distinguir seus
.. produtos s�o as marcas registradas. Onde essas designa��es aparecem neste livro,
.. e Open Object Press tinha conhecimento de uma reivindica��o da marca registrada, as designa��es foram
.. nas letras mai�sculas iniciais.

.. Embora toda precau��o foi tomada na prepara��o deste livro, a editora
.. e os autores n�o assumem nenhuma responsabilidade por erros ou omiss�es, ou por danos
.. resultantes do uso das informa��es aqui contidas.

.. Publicado por Open Object Press, Grand Rosi�re, B�lgica
