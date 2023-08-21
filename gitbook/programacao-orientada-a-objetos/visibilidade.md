# Visibilidade dos recursos

## Modificadores
Em Java, utilizamos três palavras reservadas e um conceito default (sem nehuma palavra reservada) para definir os quatro tipo de visibilidade de atributos, métodos e até mesmo classes, no que se refere ao acesso por outras classes. Iremos ilustrar do mais visível, ao mais restrito tipo de visibilidade nos arquivos em nosso projeto.
Para uma melhor ilustração, iremos representar os conceitos de visibilidade de recursos, através do contexto em uma lanchonete, que vende lanche natural e suco.

## Modificador de acesso: public
Como o próprio nome representa, quando nossa classe, método e atributo é definido como public, **qualquer outra classe em qualquer outro pacote**, poderá visualizar tais recursos.
OBS: Dentro de um arquivo .java, só pode existir uma classe do tipo public, e está classe precisa obrigatoriamente ter o mesmo nome que o nome do arquivo .java.

## Modificador de acesso: protected
Protected é um modificador um pouco mais restritivo que o public.  Com este tipo modificador, podemos declarar que um atributo ou método é **visível apenas para as classes do mesmo pacote ou para as subclasses daquela classe**.

## Modificador de acesso: default (ou package)
Default é um modificador um pouco mais restritivo que o protected. Este tipo de modificador é aplicado a todas as classes, atributos ou métodos, os quais, **não tiveram o seu modificador explicitamente declarado**.Este modificador permite que **apenas classes do mesmo pacote** tenham acesso as propriedades que possuem este modificador.

## Modificador de acesso: private
private é um modificador de acesso que **restringe totalmente o acesso aquele recurso da classe de todas as demais classes**, sejam elas do mesmo pacote, de outros pacotes ou até subclasses. Este modificador pode ser aplicado a atributos e método.
