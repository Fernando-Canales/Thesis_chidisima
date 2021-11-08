# Thesis_chidisima :book:
## Created by [Fernando Gutiérrez-Canales](https://twitter.com/ferdunkand)
e-mail: carl.cfgc@gmail.com
## Last Update: 2-Nov-2021

The thesis template presented in here can be used, modified and/or shared
freely without my permission. I have compiled all the .tex files in
the Linux Terminal of Ubuntu 20.04 LTS. This template is based on the
_tesis_chida_ template by Dr. Oscar Barragán, that can be consulted
in its [github repo](https://github.com/oscaribv/thesis_chida)

## Contents
* P: This directory contains the packages used in this template, as well as the
commands used. All in two files:
	* packages.tex: In this file all the needed packages for writing a thesis
	are present. If you need any other packages, call them in this file.
	* commands.tex: In this file usefuls commands and abreviations are written.
	Put your own commands and abreviations in this file. 

* front: This directory contains the files that are in the first pages of the thesis
	* title_page.tex: The title page of your thesis can be easily done
	with this .tex file.
	* abstract.tex: Put the abstract here, where the '...' are. Also,
	I added the questions that any good abstract have to answer, according
	to Dr.Oscar Barragán.
	* dedicatory.tex: Put the name of that special person here :heart: 
	* epigraphs.tex: If you are a little bit pretentious like myself 
	(just a little bit!) then you can add some epigraphs to your thesis 
	with the command `\epigraph{}`. I already put some epigraphs on this
	file as an example of how they look on the resulting pdf

* chapters: This directory contains the files for the chapters of your thesis.
	* introduction.tex: Put the introduction here. In this file I added
	an epigraph at the beginning to show that you can add an epigraph for 
	each chapter.
	* chapters02.tex: In this file I put two citation examples.
	* conclusions.tex: Put the conclusions here.

* appendix: This directory contains a sample of an appendix.
	* ap1.tex: Put the appendix here.

* biblios : This directory contains two files. The first one is the .bib file
	in which all the references has to be. The second one a .bst file that
	is used as the bibliography style file.
	* reference.bib: This file contains two cites using the bibtex 
	bibliography style as an example. The cites come from
	[ADS](https://ui.adsabs.harvard.edu/)
	* yahapj.bst: This file is written in the BST language. Is an  ApJ bibtex style file.
	This means that we can mimic the ApJ style by using this file as the
	bibliography style of our thesis document. All the details can be
	found in Peter William's [github repo](https://github.com/pkgw/tex-stuff/)

* images: This directory contains an image of the Arkham Asylum. This is the
	image of the title of the thesis. If you want to put the 'logo' of
	your Uni, put it here.
