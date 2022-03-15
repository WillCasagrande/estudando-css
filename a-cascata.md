# A cascata (cascading)

A escolha do browser de qual regra aplicar, caso haja muitas regras para o mesmo elemento.

* Seu estilo é lido de cima pra baixo.

É levado em consideração 3 fatores

1. Origem do estilo
2. Especifidade
3. Importância

### Origem do estilo

inline> tag style > tag link

### Especificade

É um cálculo matemático, onde, cada tipo de seltor e origem do estilo, possuem valores a serem considerados.

0. Universal selector, combinators e negation pseudo-class (:not())
1. Element type selector e pseudo-elements (::before, ::after)
10. Classes e attribute selectors ([type="radio"]])
100. ID selector
1000. Inline

### Regra !important;

-Não é uma boa prática;
-Evitar o uso;
-Quebra o fluxo natural da cascata.