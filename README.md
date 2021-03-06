# Desafio de arquitetura


#### Este desafio está relacionado ao artigo [Arquiteturas de software](https://fabriciodezain.wordpress.com/2021/02/01/arquiteturas-de-software/) publicado no [medium](https://medium.com/). Caso não tenha lido ou esteja buscando enriquecer seu repertório sobre o assunto, sugiro fortemente a leitura antes de embarcar nesse desafio.


# Motivação

É bastante comum encontrar por ai devs com dificuldades de como estruturar inicialmente seu projeto (me incluo nessa lista), e, ultrapassado essa barreira, é mais comum ainda não sabermos lidar com as mudanças de escope que ocorrem ao longa da vida útil do software.

> "O software foi inventado para ser soft. Foi planejado para ser um meio de mudar facilmente o comportamento das máquinas. Se quiséssemos que o comportamento das máquinas fosse difícil de mudar, nós o chamariamos de hardware" (Uncle Bob)


# Como participar

1. Criei um repositório no [github](https://github.com/)
2. Implemente os 3 casos de uso em pastas diferentes, com o código fonte dentro de uma pasta `src`
*  Exemplo: `use-case-1/src`, `use-case-2/src` e `use-case-3/src`  
3. No final, adicione o usuário `espigah-arch` ao repositório

## Implementação

A ideia é focar em como os objetos se relacionam e não no que eles fazem, ou seja, não se espera que alguém implemente de fato a logica para algum ação, não é isso que será "avaliado".

Nada muito complexo. Espera-se que se tenha 3 grandes unidades de software ("monólitos", o que não significa alto acoplamento), 1 para cada caso de uso.

Nem ao menos se espera algum projeto que compile. Ou que se tenha algum preocupação com testes, mocks, gerenciadores de dependências e etc.

O caso de uso pode ser um clone do anterior com as alterações, ou pode ser algo totalmente novo.


# Linguagens 

* Qualquer linguagem dita OOP (Java, Haxe, Kotlin, C# e etc)
* Preferivelmente Java

# Casos de uso

## Caso de uso 1

![Caso de uso 1](docs/use_case_1.jpg)

## Caso de uso 2

![Caso de uso 2](docs/use_case_2.jpg)

## Caso de uso 3

![Caso de uso 3](docs/use_case_3.jpg)


# Extra - UML

Deixar a linguagem que sera usado sem muitas amarras serve para tentar diminuir as barreiras para quem é iniciante ou para aqueles que não gostam do java.
Entretendo, para que seja possível colocar todos olhando pelo mesmo prisma, seria interessante que fosse disponibilizado para cada caso de uso um arquivo/imagem de um digrama (`/use-case-n/diagram.png`). Segue um exemplo: 

![Class Diagram Sample](docs/Class-Diagram-Sample.png)


* [draw.io](https://app.diagrams.net/), [visual-paradigm](https://www.visual-paradigm.com/) e [staruml](https://staruml.io/) fazem diagramas muito bem
* [modelio](https://www.modelio.org/) e [umldesigner](http://www.umldesigner.org/ref-doc/umlgen.html#:~:text=for%20your%20code.-,Java%20to%20UML,to%20generate%20the%20UML%20model.&text=Activity%20Generation%20%3A,tool%20generates%20no%20activity%20diagrams) prometem fazer Java to UML
# Etapa 2 (peer to peer)

Quando completarmos N (20?) projetos submetidos irei disponibilizar um link para que seja possível que todos os participantes conheçam as soluções submetidas e escolham a que mais lhe agrada.

# Boa sorte! 

:partying_face: :partying_face: