![Argumentação](../assets/Cenarios/Grafo.jpeg)

# Análise

## Identificando as Proposições: 
Verifica-se que cada nó do grafo identifica as proposições (P1, P2, P3, P4). Elas representam os pontos de vista ou hipóteses que estão sendo discutidas.
Identificando as Interpretações e Conclusões:
Os nós em azul no grafo representam instâncias de proposições (i).
Os nós verdes representam interpretações (It).
Os nós vermelhos representam contradições (C) ou conflitos.
Os nós amarelos representam preferências (P).

## Análise das Relações:
Verificando como as proposições (P1, P2, P3, P4) se relacionam com as interpretações e conclusões.
Como cada interpretação ou conclusão é formada com base nas proposições.

### Complementaridade de Proposições:
- P1 e P2 podem ser complementares, ou seja, podem fornecer informações que se completam mutuamente. Por exemplo, uma proposição pode estabelecer uma ideia inicial, enquanto a outra pode fornecer uma justificativa ou evidência adicional para a ideia.
No grafo, a junção de P1 e P2 em um nó de interpretação (It(i(P1), i(P2))) sugere que, para entender completamente o argumento ou a situação em questão, é necessário considerar ambas as proposições em conjunto.

- P3 e P4 parecem tratar de aspectos opostos de uma mesma decisão estratégica: uma decisão simplificaria a implementação (foco apenas no transporte público), enquanto a outra aumentaria a complexidade do sistema (integração com serviços de empresas privadas).
Essas proposições são complementares na medida em que oferecem dois lados da mesma moeda — o impacto da escolha entre focar somente em transporte público versus integrar serviços privados. Portanto, analisá-las juntas ajuda a entender o trade-off entre simplicidade e complexidade.


### Relação de Dependência:
- P1 e P2 podem ter uma relação de dependência lógica, onde o significado ou a validade de uma delas depende da outra. Por exemplo, P1 pode ser uma 
condição ou requisito para P2, ou vice-versa.

- A interpretação conjunta dessas proposições ajuda a entender como uma pode influenciar ou ser influenciada pela outra.
Existe uma relação de dependência lógica inversa entre P3 e P4. Se a proposição P3 ("focar apenas no transporte público") for verdadeira e escolhida como uma decisão estratégica, P4 ("integrar serviços de empresas privadas") naturalmente se torna menos relevante, pois esta integração não estaria nos planos.

- Portanto, a interpretação conjunta permite ver que a escolha de uma proposição implica a exclusão ou diminuição da relevância da outra.


### Construção de um Argumento Mais Forte:
- Combinar P1 e P2 pode servir para construir um argumento mais forte, no qual a interpretação considera múltiplas perspectivas ou dados que reforçam a conclusão desejada.
- Por exemplo, se P1 sugere uma ação e P2 reforça o benefício dessa ação, juntar ambas em uma interpretação cria um argumento mais convincente.

- Juntar P3 e P4 em uma interpretação permite que o decisor ou analista veja claramente os benefícios e desvantagens de cada opção estratégica. Se um argumento quer defender a simplificação da implementação, P3 e P4, juntos, fortalecem essa visão ao contrapor simplificação versus complexidade.
- Esta abordagem constrói um argumento claro sobre os prós e contras da estratégia de foco no transporte público versus a integração de serviços privados.

### Necessidade de Coerência:
- No grafo, ao combinar P1 e P2 em um nó de interpretação, pode-se verificar se há consistência entre elas ou se geram um conflito que precisa ser resolvido.

- P3 e P4 representam proposições que, se analisadas separadamente, podem parecer independentes. No entanto, ao serem interpretadas juntas, revelam um conflito de interesses ou uma tensão estratégica — entre simplificação e complexidade. É essencial analisar ambas juntas para determinar a coerência da estratégia geral.
- Por exemplo, se o objetivo do projeto for simplicidade e eficiência, P3 seria coerente, enquanto P4 indicaria uma direção conflitante. Juntas, ajudam a clarificar o caminho mais coerente a seguir.


## Verificando as Contradições e Preferências:
 - As contradições (C1, C2) indicam pontos em que duas proposições ou interpretações se contradizem.
- As preferências (P1) indicam um julgamento ou escolha sobre qual proposição é mais válida ou preferível.

### C1(i(P4,i(P2)))
#### Objetivos e Consequências Opostos:
- P2 sugere que integrar serviços de empresas privadas é uma decisão positiva porque "pode atrair mais usuários". Essa proposição foca no benefício potencial de aumentar a base de usuários do sistema.
- P4 aponta para um lado negativo da mesma decisão, afirmando que "aumentaria a complexidade do sistema". Ou seja, enfatiza o custo ou a desvantagem da integração de serviços privados.

#### Conflito Entre Vantagem e Desvantagem:
- P2 e P4 entram em contradição porque apresentam um conflito direto entre uma vantagem (atrair mais usuários) e uma desvantagem (aumentar a complexidade do sistema).
- Se o foco do sistema é a simplicidade, então a integração de serviços privados (P2) não seria desejável devido à complexidade adicional mencionada em P4. Por outro lado, se o objetivo é aumentar a base de usuários, a complexidade adicional mencionada em P4 pode ser vista como um preço aceitável a pagar.

#### Impacto na Decisão Estratégica:
- P2 pode levar a uma decisão estratégica de expandir o sistema para incluir serviços privados, o que implica que o sistema deve lidar com a complexidade extra (contradizendo P4).
- P4 sugere que a decisão de não integrar serviços privados deve ser considerada para evitar complicações e complexidades adicionais, o que se opõe à ideia defendida em P2 de que essa integração é positiva para atrair mais usuários

#### Implicações Práticas de Implementação:
- Se P2 é verdade (integrar serviços privados atrai mais usuários), pode ser um argumento a favor de aceitar a complexidade mencionada em P4 como um "mal necessário".
- No entanto, se P4 é considerada uma limitação importante (a complexidade deve ser evitada), então P2 torna-se menos desejável ou até inaceitável, pois contraria a necessidade de manter o sistema simples.
Conclusão
- P2 e P4 são contradições porque representam objetivos conflitantes: uma visa maximizar o engajamento de usuários por meio da integração de serviços privados, enquanto a outra visa minimizar a complexidade do sistema ao evitar essa integração. Portanto, elas não podem ser satisfeitas simultaneamente sem comprometer o objetivo de uma ou da outra.

### C2(P1, C1(i(P4), i(P2)))
#### Objetivos em Conflito:
- P1 sugere a expansão do sistema para incluir suporte a serviços adicionais (como carros por aplicativos externos e locais de bicicletas/patinetes compartilhados). Isso indica uma orientação para integrar mais serviços, o que pode implicar uma maior complexidade e uma abordagem de inclusão.
- C1 (que reflete a contradição entre P4 e P2) expressa que existe uma tensão entre a complexidade adicional e o potencial de atrair mais usuários através da integração de serviços privados. Portanto, C1 sugere que aumentar a integração (como proposto em P1) pode ser visto de duas maneiras: pode ser positivo para atrair mais usuários (como sugerido por P2), mas também pode adicionar complexidade ao sistema (como sugerido por P4).

#### Impacto na Decisão Estratégica:
- Se P1 propõe que o Moovit deve suportar carros de aplicativos externos e serviços compartilhados, isso está alinhado com a proposição P2 (integrar mais serviços para atrair usuários).
- No entanto, isso contradiz P4 porque adicionar mais serviços como suporte a aplicativos externos ou locais de bicicletas/patinetes aumentaria, inevitavelmente, a complexidade do sistema, justamente o que P4 critica.

#### Incompatibilidade de Implementação:
- P1 requer que o sistema do Moovit suporte e integre serviços adicionais (carros de aplicativos, bicicletas, patinetes), o que claramente adiciona novas camadas de complexidade, gestão e recursos.
- C1 expressa que, enquanto adicionar esses serviços (como sugerido em P1) pode ser vantajoso para atrair usuários (P2), ele também aumenta a complexidade (P4). Assim, ao adotar P1, o argumento de que a complexidade do sistema deveria ser evitada (P4) não pode ser mantido.

#### Conclusão do Conflito:
- A contradição entre P1 e C1 surge porque P1 está diretamente alinhada com um dos lados do conflito representado por C1 (ou seja, a integração de mais serviços), mas contrária ao outro (a necessidade de evitar complexidade).
- Portanto, se P1 for adotada, ela favorece o lado do argumento que apoia a integração de serviços para atrair mais usuários (P2) e desconsidera a preocupação com a complexidade adicional (P4). Isso cria uma contradição com o argumento equilibrado representado por C1, que leva em conta tanto o benefício quanto a desvantagem da integração de serviços.


## Examinando os Fluxos de Argumentação:
Seguir os fluxos entre os nós do grafo para entender a sequência lógica do argumento (tabela abaixo).

Por exemplo, veja como "It1(P1, P2)" se relaciona com "i(P2)" e "C1(i(P4), i(P2))".


### Tabela 
| Proposição | Representação no Grafo	| Satisfeito? |	Observações |
| :-: | :-: | :-: | :-: | 
| P1 | i(P1), It(i(P1), i(P2)) | X | Adequadamente representada na conjunção com P2. |
| P2 | i(P2), It(i(P1), i(P2)) | X | Representada na conjunção e na contradição. |
| P3 | i(P3), It(i(P3), i(P4)) | X | Representada na conjunção com P4. |
| P4 | i(P4), C1(i(P4), i(P2)) | X | Está representada na contradição com P2. |
| C1 | C1(i(P4), i(P2))	| X | Representa a contradição entre P4 e P2, conforme esperado. |
| C2 | C2/P1, C1(i(P4), i(P2)) | X | Adequadamente representada como contradição derivada de C1. |
| Conclusão | P1(i(P2), i(P4)) | X | A conclusão está consistente com as informações representadas. |

| Autor| Versão          |Data| Descrição |
|------|-----------------|-----|---------- |
|[Marcos Castilhos](https://github.com/Marcosatc147) | 1.0 |11/09/2024 | Inclusão da Análise de Argumentação|



