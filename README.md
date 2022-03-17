# practice_with_flex_direction
CSS lexbox


Posicionando elementos com Flexbox em CSS

# Flex Container

● display
● flex-direction
● flex-wrap
● flex-flow
● justify-content
● align-items
● align-content

# Flex item
Propriedades relacionadas


● flax-basis
● flex-shrink
● flex-grow
● flex
● order
● align-self

# Diplay flex

Torna a tag um elemento do tipo flex container, e assim
automaticamente todos os seus filhos diretos desta tag, tornam-
se em flex items.

# Flex direction

É a propriedade que estabelece o eixo principal do container,
definindo assim a direção que os flex items são colocados no flex
container.
* column:
* column-reverse
* row
* row-reverse

# Flex wrap

* nowrap: é o padrão, não permite a quebra de linha.
* wrap: permite a quebra de linha assim que um dos flex itens não puder mais ser compactado.
* wrap-reverse: permite a quebra de linha assim que um dos fles itens não puder mais ser compactado, porém na direção contratia da linha acima.

# Flex flow
É um atalho para as propriedades flex-direction e flex-wrap.
Porém seu uso não é tão comum, visto que, quando mudamos o
flex-direction para column, mantemos o padrão do flex-wrap que
é nowrap.

# Justify Content

Essa propriedade vai se encarregar de alinhar os itens dentro do
container de acordo com a direção pretendida e tratar da
distribuição de espaçamento entre eles.

* Flex-start: início do container.
* Flex-end: final do container.
* Center: ao centri do container.
* Space-between: cria um espaçamento igual entre os elementos.
* Space-around: os espaçamentos do meio são duas vezes maiores que o inicial e final.


# Align-items

Trata do alinhamento dos flex itens de acordo com o eixo do
container.

O alinhamento é diferente para quando os itens estão em colunas
ou linhas.

Permite o alinhamento central no eixo vertical.
* center: alinhamneto dos item ao centro
* stretch: padrão, e os flex itens cresçam igualmente.
* flex-start: alinhamento dos itens no início.
* flex-end: alinhamento do itens no final
* baseline; alinhamento de acordo com a linha base da tipografia dos itens.

# Align-content

* center: alinhamneto dos item ao centro
* stretch: padrão, e os flex itens cresçam igualmente.
* flex-start: alinhamento dos itens no início.
* flex-end: alinhamento do itens no final
* Space-between: cria um espaçamento igual entre os elementos.
* Space-around: os espaçamentos do meio são duas vezes maiores que o inicial e final.

# flex-grow
Define a proporcionalidade de crescimentos dos itens,
respeitando o tamanho de seus conteúdos internos.

Por padrão a flex-grow vem em 0, a class foi criada por questão de aprendizado.
justify-content so so altera onde o flex-grow e zero Default;

# flex-basis

* auto: caso o item não tenha tamanho, este será proporcional ao conteúdo do item.
* px, % em, ...: são valores exatos previamente definidos
* 0 (zero): terá relação com a definição do flex-grow

# flex-shrink

È a propriedade que estabelecer a capacidade de redução ou compressão do tamanho de um item.

# flex

Esta propriedade é um atalho ou abriviação de escrita para as propriedades: grow, shrink e basis.

# order 

Ordernação do itens 


# aling self

È a propriedade que estabelece o alinhamento de modo individual sobre um determinado item.
-> VALORES POSSIVEIS <-
* auto: valor padrão, irá respeitar a definião de align-items do container.

* flex-start: ao início do container.
* flex-end: ao final do container.
* center: relativo ao centro de acordo com o eixo.
* stretch: ocupa todo os espço relativo.
* basiline: utiliza a linha base da tipografia.

# Flex_project
projeto final


Creditos:
# Karen Santos
# Digital Innovation one
# Bootcamp Philips Fullstack Developer 










