Otimização da Cadeia de Suprimentos e Distribuição
Objetivo: Desenvolver um plano integrado de otimização para a cadeia de suprimentos e distribuição de uma empresa, considerando a minimização de custos, tempos de entrega e a utilização eficiente dos recursos.
Cenário
Você é o gerente de logística de uma grande empresa de varejo que opera em várias regiões de um país. A empresa possui três centros de distribuição (CDs) localizados em diferentes cidades e precisa abastecer 10 lojas espalhadas em diversas regiões. Sua tarefa é otimizar o processo de suprimento e distribuição, considerando as seguintes informações:
Centros de Distribuição (CDs):
Centro de Distribuição
Capacidade (unidades)
Localização
CD1
1000
A
CD2
800
B
CD3
1200
C
Lojas e Demanda:
Loja
Demanda (unidades)
Localização
Loja 1
150
X
Loja 2
200
Y
Loja 3
300
Z
Loja 4
180
W
Loja 5
250
V
Loja 6
350
U
Loja 7
220
T
Loja 8
270
S
Loja 9
190
R
Loja 10
160
Q
Custos de Transporte por Unidade (R$) entre CDs e Lojas:
CD -> Loja
Distância (km)
Custo por Unidade (R$)
CD1 -> X
100
5,00
CD1 -> Y
150
7,00
CD1 -> Z
120
6,00
CD2 -> W
90
4,50
CD2 -> V
130
6,00
CD2 -> U
110
5,50
CD3 -> T
80
4,00
CD3 -> S
140
6,50
CD3 -> R
100
5,00
CD3 -> Q
160
7,50
Restrições:
Abastecimento Único: Cada loja só pode ser abastecida por um único CD.
Capacidade dos CDs: As capacidades dos CDs não podem ser ultrapassadas.
Objetivo: Minimizar o custo total de transporte.
Tarefas
Alocação das Demandas:
Passo 1: Determine qual CD irá abastecer cada loja, respeitando as restrições de capacidade dos CDs e minimizando os custos de transporte.
Passo 2: Preencha a tabela abaixo com a alocação proposta.
markdownCopiar código
| Loja   | CD Abastecedor | Quantidade (unidades) | Custo Total (R$) |
|--------|----------------|-----------------------|------------------|
| Loja 1 | CD1            | 150                   | 750,00           |
| Loja 2 | CD1            | 200                   | 1400,00          |
| Loja 3 | CD2            | 300                   | 1800,00          |
| ...    | ...            | ...                   | ...              |


​
Cálculo dos Custos Totais:
Passo 1: Some os custos de todas as alocações para determinar o custo total de transporte.
markdownCopiar código
**Custo Total de Transporte:** R$ [valor total]


​
Simulação de Cenário de Picos de Demanda:
Passo 1: Simule um cenário onde as demandas de todas as lojas aumentam em 20%.
Passo 2: Determine se os CDs conseguem suprir a nova demanda e, em caso negativo, identifique quais lojas não serão atendidas.
markdownCopiar código
**Resultados da Simulação:**
- Lojas atendidas: [lista de lojas]
- Lojas não atendidas: [lista de lojas]
- Capacidade excedida no CD1: [quantidade excedida]


​
Planejamento de Expansão:
Passo 1: Com base na simulação de pico de demanda, proponha uma estratégia de expansão.
Passo 2: Inclua uma análise de custo-benefício para a expansão sugerida, como abaixo:
markdownCopiar código
## Análise de Custo-Benefício para Expansão

- **Proposta de Expansão:** Aumentar a capacidade do CD1 em 200 unidades.
- **Custo Estimado de Expansão:** R$ 50.000,00
- **Benefícios:** Atende ao aumento de demanda com menor custo adicional de transporte.


​
Documentação:
Passo 1: Escreva um relatório em Markdown que documente todas as etapas acima.
markdownCopiar código
# Relatório de Otimização da Cadeia de Suprimentos

## Alocação das Demandas

...

## Cálculo dos Custos Totais

...

## Simulação de Pico de Demanda

...

## Planejamento de Expansão

...

## Conclusão

...

