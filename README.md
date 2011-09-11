Documenation for the synbiodex projects

Howto: Make docs and publish them on synbiodex.github.com

Inside your repo setup:

copy docs/ dir from libSBOLrdf

Use doxy_wizard to generate docs from sources
docs/doxy_config/config.Doxyfile
set the source: src
set the destination: build/documentation/doxy_javadoc
edit the project specific stuff

docs/pages contains the static files for doxy docs - tutorial, main page, etc



click RUN

In synbiodex.github.com repo

edit the root index.html add your project info

make a dir for you project

libSBOLrdf/ <- once built my  doxy_javadoc/ dir goes there
libSBOLrdf/index.html <- This is your main page, since your docs will be built by doxy 
libSBOLxml/  <- once built you'll put docs here
libSBOLxml/index.html <- This is your main page, since your docs will be built by doxy 

