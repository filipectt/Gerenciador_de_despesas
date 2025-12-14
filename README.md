AGENDAMENTO INTELIGENTE DE CONTAS A PAGAR

A gestão de contas a pagar é um desafio financeiro. Ao lidar com um alto volume de faturas, é necessário priorizar pagamentos por vencimento e otimizar o uso da disponibilidade de caixa mensal. Fazer isso manualmente pode levar a atrasos e perda de oportunidades de desconto.

**O que ele faz:**

Leitura e Agendamento: O script solicita o Ano Fiscal, o valor TOTAL de caixa disponível no mês e o mês de agendamento. Em seguida, ele carrega a planilha de dívidas (CSV).
Priorização Estratégica: Prioriza as faturas com o status VENCIDO ou MAIS PRÓXIMO DO VENCIMENTO, e seleciona as de MENOR VALOR primeiro, garantindo que o orçamento (disponibilidade de caixa) seja utilizado de forma otimizada.
Seleção Otimizada: Seleciona pagamentos até atingir o limite de caixa informado.
Distribuição Semanal: Agenda os pagamentos selecionados em dias úteis específicos do mês (Segunda, Quarta e Sexta-feira), distribuindo a carga de trabalho.
Exportação Final: Gera um arquivo Excel (agenda_pagamentos_...xlsx) com abas separadas por semana, contendo apenas as dívidas agendadas e os resumos de saldo.

**Bibliotecas:**
pandas: Essencial para a manipulação e limpeza de dados (DataFrames).
datetime e numpy: Utilizados para o cálculo de datas de vencimento, priorização e determinação das semanas do mês.

**Observações finais:** Este código foi pensado pra resolver um problema da minha rotina e de um contexto financeiro específico, talvez não funcione pra você.

**Acesso:** https://colab.research.google.com/drive/1VDxmJ50qVFoH-gkAQz_P4Y3KzbclNJWI?usp=sharing
