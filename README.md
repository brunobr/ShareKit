ShareKit 2.0 - Customized
============

Sharers:
----------- 

 - Facebook
 - Twitter
 - Tumblr
 - Flickr
 - Foursquare
 - LinkedIn
 - Google reader

Instalação:
------------

 1. Clonar projeto
 2. Ir na pasta, pelo terminal, e executar: rm -r .git
 3. Copiar a pasta ShareKit para a pasta do Projeto em questão
 4. "Arrastar" o projeto do ShareKit para o seu
 5. Incluir no User Header Search Paths: $(SRCROOT)/ShareKit e marcar a check de recorrencia
 6. Incluir a flag -all_load no linker flags
 7. Adicionar  ao Target Dependencies, Static Library (ShareKit) e Resource Bundle (ShareKit)
 8. Adicionar ao Link Binary With Libraries, libShareKit.a
 9. Arrastar o ShareKit.bundle da pasta Products no projeto ShareKit para a parte Copy Bundle Resources

Documentation
-------------

The latest documentation and installation instructions can be found on the [ShareKit Wiki](https://github.com/ShareKit/ShareKit/wiki).

!!! Updated new service creation guidelines for contributors are [here](https://github.com/ShareKit/ShareKit/wiki/New-service-creator's-guidelines) !!!