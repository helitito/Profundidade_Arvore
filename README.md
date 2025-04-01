# Profundidade_Arvore
A profundidade de uma árvore binária é a mesma independentemente da ordem de travessia, já que a profundidade máxima é determinada pela quantidade de níveis na estrutura da árvore e não pela forma como percorremos os nós.

### Explicação:
1. As funções `profundidade_pre_ordem`, `profundidade_em_ordem` e `profundidade_pos_ordem` seguem uma abordagem recursiva para calcular a profundidade à medida que percorrem a árvore na ordem definida.
2. Cada função aumenta a profundidade conforme explora os nós esquerdo e direito, mantendo o máximo encontrado.
3. Mesmo que a profundidade da árvore seja invariável, essas funções demonstram como o número de níveis pode ser interpretado em diferentes ordens de travessia.

