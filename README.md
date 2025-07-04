# Análise de Simulação de Processo de Fabricação

Este projeto foi desenvolvido utilizando o software Arena para analisar um processo de fabricação composto por etapas de produção (MAQ.A), inspeção e reparo.

## 🎯 Objetivo

O objetivo da simulação foi identificar a taxa de ocupação dos servidores, o tamanho e tempo médio das filas, e o tempo médio de produção de uma peça, a fim de localizar o principal gargalo do sistema.

## 🛠️ Parâmetros e Ferramentas

* **Software:** Arena
* **Tempo de Simulação:** 1.000 minutos
* **Chegada de Pedidos:** Exponencial (média 23 minutos)
* **Produção (MAQ.A):** Uniforme (15, 25 minutos)
* **Inspeção:** Triangular (15, 17, 20 minutos), com 30% de falhas
* **Reparo:** Uniforme (10, 15 minutos)
* **Deslocamento:** 2 minutos entre todas as etapas.

## 📊 Análise e Resultados Chave

* **Gargalo Identificado:** O recurso **MAQ.A** foi claramente identificado como o principal gargalo do sistema.
* **Taxa de Ocupação:** A MAQ.A apresentou uma altíssima taxa de ocupação de **89,08%**, operando próximo à sua capacidade máxima. A Inspeção teve 77,84% e o Reparo apenas 12,92%.
* **Filas:** A fila da MAQ.A foi a mais expressiva, com um tamanho médio de **1,82 peças** aguardando. As demais filas foram mínimas.

## 💡 Conclusão e Recomendações

A análise dos resultados permitiu a identificação inequívoca do gargalo do sistema na MAQ.A, suportada pelas altas taxas de ocupação e pelo acúmulo de peças em sua fila.

**Recomendação Principal:** Para otimizar o processo, sugere-se o **aumento da capacidade da MAQ.A**, seja através de uma nova máquina, melhoria da eficiência da existente ou redução de seu tempo de processamento.
