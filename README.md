# Relatório de Otimização da Cadeia de Suprimentos

## 1. Alocação das Demandas

### Passo 1: Determinar a alocação das demandas

Com base nos custos de transporte por unidade e a capacidade dos CDs, a alocação das demandas foi realizada da seguinte maneira para minimizar o custo total:

| Loja   | CD Abastecedor | Quantidade (unidades) | Custo por Unidade (R$) | Custo Total (R$) |
|--------|----------------|-----------------------|------------------------|------------------|
| Loja 1 | CD1            | 150                   | 5,00                   | 750,00           |
| Loja 2 | CD1            | 200                   | 7,00                   | 1.400,00         |
| Loja 3 | CD1            | 300                   | 6,00                   | 1.800,00         |
| Loja 4 | CD2            | 180                   | 4,50                   | 810,00           |
| Loja 5 | CD2            | 250                   | 6,00                   | 1.500,00         |
| Loja 6 | CD2            | 350                   | 5,50                   | 1.925,00         |
| Loja 7 | CD3            | 220                   | 4,00                   | 880,00           |
| Loja 8 | CD3            | 270                   | 6,50                   | 1.755,00         |
| Loja 9 | CD3            | 190                   | 5,00                   | 950,00           |
| Loja 10| CD3            | 160                   | 7,50                   | 1.200,00         |

---

## 2. Cálculo dos Custos Totais

### Passo 2: Cálculo do custo total de transporte

Somando os custos de todas as alocações:


**Custo Total de Transporte:** **R$ 12.970,00**

---

## 3. Simulação de Pico de Demanda

### Passo 1: Simular um aumento de 20% na demanda

Com o aumento de 20% nas demandas, temos as novas quantidades para cada loja:

| Loja   | Demanda Original (unidades) | 
|--------|-----------------------------|
| Loja 1 | 150                         |
| Loja 2 | 200                         | 
| Loja 3 | 300                         | 
| Loja 4 | 180                         |
| Loja 5 | 250                         |
| Loja 6 | 350                         |
| Loja 7 | 220                         | 
| Loja 8 | 270                         | 
| Loja 9 | 190                         |
| Loja 10| 160                         |

| Loja   | Nova Demanda (+20%) (unidades) |
|--------|--------------------------------|
| Loja 1 | 180                            |
| Loja 2 | 240                            |
| Loja 3 | 360                            |
| Loja 4 | 216                            |
| Loja 5 | 300                            |
| Loja 6 | 420                            |
| Loja 7 | 264                            |
| Loja 8 | 324                            |
| Loja 9 | 228                            |
| Loja 10| 192                            |

### Passo 2: Verificar a capacidade dos CDs

A verificação da capacidade dos CDs após o aumento de demanda mostrou o seguinte:

| CD      | Capacidade (unidades) | Demanda Alocada (unidades) | Capacidade Excedida (unidades) |
|---------|-----------------------|----------------------------|--------------------------------|
| **CD1** | 1000                  | 780                        | Não                            |
| **CD2** | 800                   | 936                        | **Sim** (Excedido em 136 unidades) |
| **CD3** | 1200                  | 1008                       | Não                            |

### Resultado:

- **Lojas atendidas:** Loja 1, Loja 2, Loja 3, Loja 7, Loja 8, Loja 9, Loja 10.
- **Lojas não atendidas:** Loja 4, Loja 5, Loja 6 (devido à capacidade excedida no CD2).

---

## 4. Planejamento de Expansão

### Passo 3: Propor uma estratégia de expansão

#### Análise de Custo-Benefício para Expansão

- **Proposta de Expansão:** Aumentar a capacidade do CD2 em 200 unidades para atender ao aumento de demanda.
- **Custo Estimado de Expansão:** R$ 50.000,00 (custo fixo de infraestrutura).
- **Benefícios:** A expansão permitirá atender à demanda aumentada sem precisar realocar lojas para outros CDs, mantendo os custos de transporte baixos.

#### Justificativa

A expansão do CD2 em 200 unidades será suficiente para cobrir a demanda extra de 136 unidades no cenário de pico. Isso também deixará uma margem adicional para futuros aumentos de demanda, evitando custos maiores de realocação ou aumento dos custos variáveis de transporte.

---

## 5. Conclusão
