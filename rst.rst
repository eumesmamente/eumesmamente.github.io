.. header::
   Informática 4º de E.S.O. - Edición avanzada de textos 

.. footer::
    ###Page###

.. _Python: https://www.python.org/

.. _RestructuredText: http://docutils.sourceforge.net/rst.html

********************
Linguaxes de marcas
********************

---------------------------------------
Unha aproximación con ReStructuredText
---------------------------------------

    :Data: 7-Febreiro-2016
    :Revisión: 1
    :Autor: Manuel     
    :Email: eumesmo

.. raw:: pdf

   PageBreak oneColumn


.. contents:: Táboa de contidos
                
.. section-numbering::

.. raw:: pdf

   PageBreak oneColumn

Introdución 
============
As `linguaxes de marcas <https://es.wikipedia.org/wiki/Lenguaje_de_marcado>`_ 
permiten producir **documentos** de gran calidade especialmente 
orientados ao ámbito académico. Estas linguaxes son eficientes 
tanto para crear documentos de humanidades como científicos e de 
propósito xeral. A súa utilidade é moi ampla e vainos permitir, 
dependendo da linguaxe empregada, crear documentos sinxelos ou 
complexos preparados para impresión nos que podemos incluír 
desde complicadas fórmulas a todo tipo de estilos e formatos.

Ao contrario que outros sistemas de edición de textos **WYSIWYG**, 
o que ves é o que obtés, como *Microsoft Office* 
(licenza propietaria) ou *Libreoffice* (licenza libre), as
linguaxes de marcado seguen o paradigma **WYSIWYM**, é dicir, 
o que ves é o que queres dicir, facendo referencia á separación 
entre o contido e a presentación final que se deixa en mans dun 
intérprete de linguaxe de marcas para cada tipo de formato. 
O usuario só terá que preocuparse da estrutura do documento 
deixando a aparencia visual en mans do sistema de exportación.

Características das linguaxes de marcas
----------------------------------------
 	
Unha **linguaxe de marcado** ou **linguaxe de marcas** é unha 
forma de codificar un documento que, xunto co texto, incorpora 
etiquetas ou marcas que conteñen información adicional da estrutura 
do texto ou da súa aparencia.

Dependendo da linguaxe escollida, o usuario necesitará coñecer os 
diferentes tipos de marcas ou etiquetas para estruturar 
e organizar o documento. Entre as vantaxes deste 
sistema están a reflexión previa sobre a conveniente 
estrutura do que se quere comunicar, a edición nun editor 
de texto plano ou na terminal e o aforro de espazo en disco. 
Ademais, a separación entre aparencia e estrutura permite a xeración 
de distintos tipos de documentos finais partindo dun mesmo 
documento inicial. Deste xeito é posible converter un documento 
nun ficheiro pdf para imprimir, nunha presentación para 
ver nun proxector ou nunha páxina web entre moitas outras. Unha das linguaxes máis empregadas é Tex / Latex.

.. figure:: latex.png
    :align: center
    :width: 1800px
    
    Libros sobre LaTeX
    
Linguaxes de marcas
===================

Existen distintas linguaxes de marcas que se diferencian esencialmente 
no tipo de marcado que empregan para estruturar os documentos, na 
complexidade do seu marcado, na finalidade para a que foron deseñados 
e na súa versatilidade. 



Clasificación das linguaxes
----------------------------

As diferentes linguaxes poden clasificarse de seguinte forma:

#. **Para documentos en xeral**

    * EBML
    * YAML

#. **De presentación**

    * RTF
    * Tex/LaTeX
    * HTML

#. **Linguaxes lixeiros**, de doada edición nun editor sinxelo.

    * BBCode
    * Markdown
    * ReStructuredText [1]_ 

#. **Para manuais**

    * DocBook
    * LinuxDoc
    * AsciiDoc

#. **Linguaxes especializadas**, para matemáticas, gráficos, música, etc.

    * SVG
    * LilyPond
    * XMPP
    * MathML

.. [1] *Esta é a linguaxe empregada neste documento.*


Tipos de linguaxes de marcas
+++++++++++++++++++++++++++++

Existen diferentes tipos de linguaxes de marcado que se clasifican 
dependendo da súa funcionalidade: [2]_

 * Marcado de presentación.
 * Marcado de procedementos. 
 * Marcado descritivo.

 .. [2] *Véxase:* `Lenguaje de marcado <https://es.wikipedia.org/wiki/Lenguaje_de_marcado>`_ .

Comparativa dalgunhas linguaxes
===============================

A continuación veremos unha comparación de diferentes linguaxes para producir resultados similares:

En **HTML**
::

    <h1>Título</h1>

En **LaTeX**
::

     \section{Título}

En **ReStructuredText**
::

    Título
    ======

En **MarkDown**
::

    # Título


Cada linguaxe ten a unha forma propia de especificar o 
formato do texto pero algúns como MarkDown [3]_ e RestructuredText_ 
son máis sinxelos e poden ser lidos sen problemas na terminal 
ou nun editor de texto plano.

 .. [3] *MarkDown é tan sinxelo que está a ser moi empregado en internet para blogs e páxinas web.*


Características comparadas
--------------------------

As diferentes linguaxes teñen distintos niveis de dificultade 
e complexidade. Os de maior nivel teñen moitas máis 
posibilidades na creación de documentos mentres que os máis lixeiros 
teñen unha curva de aprendizaxe menor e son lexibles a primeira vista.


=================== ========== ========================================
**Linguaxe**        **Nivel**       **Difusión**
=================== ========== ========================================
Tex/Latex           Alto        DVI, PDF, e moitos outros
RestructuredText_   Medio       HTML, PDF, ODT, Epub, Latex 
 MarkDown           Lixeiro     LaTeX, PDF, DocBook, ODT, Epub, RTF
=================== ========== ========================================


Linguaxes de marcas lixeiros
==============================

As chamadas linguaxes lixeiras caracterízanse por  ocupar pouco espazo 
en disco, estar máis ou menos estandarizados e ser doadamente editables.

Algunhas destas linguaxes son:

* BBCode
* Markdown
* ReStructuredText
* Textile
* txt2tags
* Lout
* AsciiDoc


.. role:: rubric

:rubric:`ResTructuredText` 
=============================


RestructuredText_ é unha linguaxe de marcas lixeiro creado 
para escribir textos con formato definido de xeito cómodo 
e rápido. É parte do proxecto Docutils dentro da comunidade
de Python_ e `Sphinx <http://www.sphinx-doc.org/en/stable/>`_. Ten a principal vantaxe de que ese texto pode 
usarse para xerar documentos equivalentes en HTML, LaTeX, 
docbook, etc. É unha evolución de Structured Text.

.. figure:: rst.png
    :align: center
    :width: 1800px
    
    Sphinx é o xerador de docunetación de Python_

A miúdo, o término RestructuredText_ é abreviado como 
ReST ou reST. Este documento está escrito en ReST. 



Características e sintaxe
--------------------------

Destacamos as seguintes:

* Sintaxe sinxela. 
* Documento primario en texto plano moi lexible. 
* Lixeiro.
* Aforra espazo en disco.
* Ten saída a múltiples formatos. 
* Apto para impresión de alta calidade.
* Nivel medio de funcionalidades apto para documentos académicos.
* Entre outras admite: 

     * Diferentes estilos e tipos.
     * Modelos 
     * Táboas de contidos, ligazóns, notas, citas, referencias...
     * Matemáticas con Latex
     * Resaltado de código 

Exemplos
-----------------------------

* Matemáticas

.. math::
   
   x=\frac{1+y}{1+2z^2}+\sqrt{a^2+b^2}\int_0^\infty e^{-x^2} dx


* Bloques de código con resaltado de sintaxe. 

.. code-block:: php

    <?php
    if(isset($_POST['nome'])) {
        $nome=$_POST['nome'];
        echo "Benvido" . $nome . "";
        }

* Cadros de notas, avisos...

    .. important::

        O corpo desta caixa é un parágrafo indentado.


Bibliografía
============
 
 - *ReStructuredText* - http://docutils.sourceforge.net/rst.html
 - *Latex CoockBook* - http://www.personal.ceu.hu/tex/cookbook.html
 - *Documentación con ResT* - http://code.nabla.net/es/rest.html
 - *Lenguaje de marcado* - https://es.wikipedia.org/wiki/Lenguaje_de_marcado
 - *Lightweight markup language* - https://en.wikipedia.org/wiki/Lightweight_markup_language



