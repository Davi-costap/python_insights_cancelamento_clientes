# Python Insights - Analisando Dados com Python

# Case Fictício - Cancelamento de Clientes

### Descrição

Este projeto foi desenvolvido para analisar dados de uma empresa fictícia com mais de 800 mil clientes. A empresa observou que uma grande parte de sua base de clientes é composta por clientes inativos que cancelaram o serviço. O objetivo deste projeto é entender os principais motivos desses cancelamentos e identificar as ações mais eficientes para reduzir esse número.

A análise inclui:

Carregamento e exploração inicial dos dados
Limpeza e preparação dos dados
Análise exploratória para identificar padrões e tendências
Modelagem preditiva para prever cancelamentos futuros
Base de dados e arquivos adicionais estão disponíveis aqui: https://drive.google.com/drive/folders/184kEgAWCTjsbtDkhlYjO_JNsOkSKLI36?usp=sharing

### Instalação

1.**Iniciar a instalação da biblioteca pandas**:
   ```bash
   pip pandas as pd
   ```

### Passo a Passo do projeto

1. Importar a base de dados
2. Visualizar a base de dados
     -> Entender quais informações eu tenho disponível
     -> Identificar os problemas da base de dados
3. Tratamento de Dados 
     -> Corrigir os problemas da base de dados
4. Analisar o cancelamento dos clientes
5. Analisar a causa de cancelamento dos clientes
6. Propor soluções



### Identificando as causas do cancelamento por meio de gráficos

1. ![assinatura](https://github.com/Davi-costap/python_insights_cancelamento_clientes/assets/148830331/233d4c6e-c4c4-4d37-af62-0783db7d52b1)
2. ![dias_atraso](https://github.com/Davi-costap/python_insights_cancelamento_clientes/assets/148830331/95723087-22ac-46f7-8aab-176cb5a2898b)
3. ![duracao_contrato](https://github.com/Davi-costap/python_insights_cancelamento_clientes/assets/148830331/460ee204-afdc-4743-b0e3-92658dcec591)
4. ![frequencia_uso](https://github.com/Davi-costap/python_insights_cancelamento_clientes/assets/148830331/5986b462-fb96-4923-8599-f4a95b0005b6)
5. ![idade](https://github.com/Davi-costap/python_insights_cancelamento_clientes/assets/148830331/7d8fce93-fd83-4669-9239-f6b9b6409d44)
6. ![ligacoes_callcenter](https://github.com/Davi-costap/python_insights_cancelamento_clientes/assets/148830331/b21d70c7-dabf-4108-9ea1-3b6707e64563)
7. ![meses_ultima_interacao](https://github.com/Davi-costap/python_insights_cancelamento_clientes/assets/148830331/68f0ba4e-ea23-484e-b8c3-f3a4d6448d2c)
8. ![sexo](https://github.com/Davi-costap/python_insights_cancelamento_clientes/assets/148830331/12fba0b7-d0be-4645-8611-af7b7611c01a)
9. ![tempo_como_cliente](https://github.com/Davi-costap/python_insights_cancelamento_clientes/assets/148830331/ab9d44fd-e683-4339-a2bf-bd5d1e54204a)
10. ![total_gasto](https://github.com/Davi-costap/python_insights_cancelamento_clientes/assets/148830331/c0712e07-b651-4372-92b7-ed2b8c347675)


### Conclusões

De acordo com os gráficos, temos:

Clientes do contrato mensal TODOS cancelam -> Solução: Oferecer desconto nos planos anuais e trimestrais

Clientes que ligam mais do que 4 vezes para o call center, cancelam -> Solução: Criar um processo para resolver o problema do cliente em no máximo 3 ligações

Clientes que atrasaram mais de 20 dias, cancelaram -> Solução: Política de resolver atrasos em até 10 dias (equipe financeira)












