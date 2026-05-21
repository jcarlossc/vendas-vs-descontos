<div align="center">

# Análise de Vendas e Impacto de Descontos

### Pipeline Analítico de Vendas

Este projeto realiza uma análise estatística e financeira sobre o impacto dos descontos na rentabilidade de uma operação comercial.

<img src="https://img.shields.io/badge/Python-276DC3?style=for-the-badge&logo=r&logoColor=white" />
<img src="https://img.shields.io/badge/STATUS-EM%20DESENVOLVIMENTO-success?style=for-the-badge" />
<img src="https://img.shields.io/badge/LICENSE-MIT-blue?style=for-the-badge" />

</div>

## 📌 Visão Geral

O estudo investiga como diferentes níveis de desconto afetam:

* faturamento,
* lucro,
* margem,
* ticket médio,
* comportamento comercial,
* desempenho por região e categoria.

A proposta central do projeto é responder uma questão estratégica comum em negócios:

> até que ponto descontos ajudam a vender mais sem comprometer a lucratividade?

## 🎯 Objetivos

O projeto busca:

* Avaliar o impacto financeiro dos descontos;
* Comparar cenários com e sem desconto;
* Identificar limites economicamente saudáveis para concessão de descontos;
* Analisar comportamento de lucro e margem;
* Investigar diferenças entre regiões, categorias e canais de venda;
* Apoiar decisões estratégicas de pricing e política comercial.

## 📊 Principais Análises

O notebook contempla:

✔️ Qualidade dos dados:
* validação de nulos
* duplicados
* inconsistências
* datas inválidas
* regras de negócio

✔️ Criação de KPIs:
* faturamento
* lucro
* margem
* custo
* ticket médio

✔️ Estatística descritiva:
* média
* mediana
* dispersão
* distribuição

✔️ Dashboards analíticos:
* clientes
* canais
* métodos de pagamento
* vendedores
* regiões
* categorias

✔️ Diagnóstico financeiro:
* comparação entre cenários com e sem desconto
* evolução temporal
* impacto progressivo dos descontos

✔️ Simulações: 
* efeito incremental do desconto sobre lucro e margem
* identificação do ponto crítico de equilíbrio

## 🧠 Principais Descobertas
Descontos reduziram significativamente a rentabilidade
* O desconto médio observado foi de 15,24%
* A margem operacional passou de:
  * +9,22% sem desconto
  * para -6,96% com desconto
 
## ⚠️ Ponto crítico identificado

A análise mostrou que:

* até aproximadamente 9% de desconto
o negócio permanece próximo do equilíbrio;
* acima disso,
o lucro tende a se tornar negativo.

Impacto financeiro
| Cenário |	Resultado |
| ------- | --------- |
| Sem desconto | Lucro positivo |
| Com desconto | Prejuízo operacional |

## 🛠️ Tecnologias Utilizadas
Linguagem:
* Python 3
Bibliotecas:
* pandas
* numpy
* matplotlib

## 📈 Principais KPIs Criados
| KPI |	Descrição |
| --- | --------- |
| faturamento_sem_desc | Receita sem descontos |
| faturamento_com_desc | Receita líquida |
| custo	| Custo operacional |
| lucro_sem_desc | Lucro bruto sem desconto |
| lucro_com_desc | Lucro líquido com desconto |
| margem_com_desc |	Margem operacional |
| ticket_medio | Receita média por venda |

## 📊 Visualizações Desenvolvidas

O projeto contém gráficos para:

* evolução mensal
* desconto vs margem
* lucro por região
* lucro por categoria
* faturamento por canal
* impacto progressivo dos descontos
* dashboards comerciais

## 🔎 Metodologia

O projeto utiliza uma abordagem analítica baseada em:

1. Engenharia de métricas
* Construção manual de KPIs financeiros.

2. Estatística descritiva
* Análise de distribuição e dispersão.

3. Simulação financeira
* Avaliação do efeito progressivo do desconto sobre o lucro.

4. Diagnóstico de negócio
* Interpretação executiva orientada à tomada de decisão.

## 📌 Principais Conclusões

* ✔️ A operação é lucrativa sem descontos;
* ✔️ O desconto médio atual compromete a rentabilidade;
* ✔️ O problema principal não é volume de vendas;
* ✔️ O problema central é margem insuficiente;
* ✔️ A política de descontos deve ser segmentada.

## 🚀 Recomendações Estratégicas
Política sugerida:

| Faixa de desconto |	Recomendação |
| ----------------- | ------------ |
| Até 5% | Livre |
| 5% a 9% |	Requer justificativa |
| Acima de 9% |	Apenas casos estratégicos |

## 📌 Licença
Este projeto está licenciado sob MIT License.

## 📌 Desenvolvedor focado em:

- Data Engineering
- Analytics
- R Programming
- Python Programming
- Automação de processos
- Engenharia de Software

## 📌 Contato
* Autor: Carlos da Costa
* Recife, PE - Brasil
* Telefone: +55 81 99712 9140
* Telegram: @jcarlossc
* Blogger linguagem R: https://informaticus77-r.blogspot.com/
* Blogger linguagem Python: https://informaticus77-python.blogspot.com/
* Email: jcarlossc1977@gmail.com
* LinkedIn: https://www.linkedin.com/in/carlos-da-costa-669252149/
* GitHub: https://github.com/jcarlossc
* Kaggle: https://www.kaggle.com/jcarlossc/
* Twitter/X: https://x.com/jcarlossc1977
