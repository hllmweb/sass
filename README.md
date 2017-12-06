Primeiro instalar ruby-cli
sudo apt-get install ruby-full

Verificando a versão do ruby
ruby -v

Instalar sass 
sudo gem install sass


Comando para compilar estrutura sass em css
sass --watch nome-pasta-scss/arquivo.scss:nome-pasta-css/arquivo.css

Exemplo: 
sass --watch scss/estilo.scss:css/estilo.css


Comando para compilar estrutura e compactar tamanho 
sass --watch nome-pasta-scss/arquivo.scss:nome-pasta-css/arquivo.css --style opcao-comando-saida

opcao-comando-saida
:nested
:expanded
:compact
:compressed

Exemplo:
sass --watch scss/estilo.scss:css/estilo.css --style compressed



Documentação completa
http://sass-lang.com/documentation/file.SASS_REFERENCE.html#Output_Style

Vídeo
https://www.youtube.com/watch?v=lQsNpIZAJ1A&t=376s
