Documenation for the synbiodex projects

Howto: make docs and publish them on synbiodex.github.com

Inside your repo setup:

docs/doxy_config
set the source: src
set the destination: build/documentation/doxy_javadoc

hit run

In synbiodex.github.com repo
edit the root index.html add your project info

make a dir for you project

libSBOLrdf/ <- once built my  doxy_javadoc/ dir goes there
libSBOLrdf/index.html <- This is your main page, since your docs will be built by doxy 
libSBOLxml/  <- once built you'll put docs here
libSBOLxml/index.html <- This is your main page, since your docs will be built by doxy 

