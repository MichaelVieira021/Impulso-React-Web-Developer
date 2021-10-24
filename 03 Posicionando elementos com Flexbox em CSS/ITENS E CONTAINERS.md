<h1 align="center">FLEX CONTAINER</h1>

<h2 align="center">tag que envolve os itens, será nela que iremos aplicar a propriedade <i>"display:flex"</i>.Transforma todos os seus itens filhos em flex itens.</h2>

<h5 align="center">Flex container pode ser usado em qualquer tipo de tag.</h5>

- **display** - Inicializador do container.

  

- **flex-direction** - Faz o direcionamento dos itens. (*linha ou coluna*)

  

- **flex-wrap** -  Para quebra de linha ou não.

  

- **flex-flow** - Abreviação para o direction e wrap.   *(Seu uso não é tão comum, visto que, quando mudamos o flex-direction para column, mantemos o padrão do flex-wrap que é nowrap.)*

  

- **justfy-content** - Alinha os itens do container de acordo com sua direção.  (*caso seus itens estejam ocupando 100% de todo o container, ela não se aplica.*)

  **variações**

  flex-start: Início do container.

  flex-end: Final do container.

  center:ao Centro do container.

  space-between: Cria um espaçamento igual entre os elementos. (*inicio e fim próximos a borda*)

  space-around: Os espaçamentos do meio são duas vezes maiores que o inicial e final.

  

- **align-items** - Alinha os itens de acordo com o eixo do container.

  **Tipos de alinhamento**

  center:  Alinhamento dos itens ao centro.

  stretch: Padrão, e os flex itens cresçam igualmente.

  flex-start: Alinhamento dos itens no início.

  flex-end: Alinhamento dos itens no final.

  baseline: Alinhamento de acordo com a linha base da tipografia dos itens.

  

- **align-content** - Alinha as linhas do container.

  **Precisamos que:**

  O container utilize quebra de linhas.

  A altura do container seja maior que a soma das linhas dos itens.

  **Tipos de alinhamentos**

  center: Alinhamento dos itens ao centro.

  stretch: Padrão, e os flex itens cresçam igualmente.

  flex-start: Alinhamento dos itens no início.

  flex-end: Alinhamento dos itens no final.

  space-between: Cria um espaçamento igual entre os elementos. (*inicio e fim próximos a borda*)

  space-around: Os espaçamentos do meio são duas vezes maiores que o inicial e final.

<h1 align="center">FLEX ITEM</h1>

<h2 align="center">São os elementos filhos diretos do flex container. E também podem se tornar flex container.</h2>

- **flex-grow** - Define a proporcionalidade de crescimento dos itens, respeitando o tamanho de seus conteúdos internos. (*Não irá funcionar caso tenhamos adicionado justify-content ao nosso flex container*)

  

- **flax-basis** - É a propriedade que estabelece o tamanho  inicial do item antes das distribuições de espaço restantes dentro dele, usando como base o conteúdo interno disposto.

  **Valores possíveis**

  auto: Caso o item não tenha tamanho, este será proporcional ao conteúdo do item.

  px, %, em, ...: São valores exatos previamente definidos.

  0(ZERO): Terá relação com a definição do flex-grow.

  

- **flex-shrink** - Define a capacidade de redução ou compressão do tamanho de um item.

  

- **flex** - Abreviação de grow; basis; shrink;.

  

- **order** - Relacionado a ordem e listagem dos itens.

  

- **align-self** - Define o alinhamento de um itens especifico do container.

  **Valores possíveis**

  auto: Valor padrão, irá respeitar a definição de align-items do container.

  flex-start: Ao início do container.

  flex-end: Ao final do container.

  center: Relativo ao centro de acordo com o eixo.

  stretch: Ocupa todos os espaços relativos.

  baseline: Utiliza a linha base da tipografia. 

  