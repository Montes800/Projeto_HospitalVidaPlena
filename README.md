## 🏥 Análise de Dados Hospitalares - Hospital Vida Plena
Este projeto foi desenvolvido durante o curso de Ciência de Dados aplicada à gestão hospitalar. O objetivo principal foi analisar a ocupação de leitos, o perfil dos pacientes e a eficiência operacional do Hospital Vida Plena, utilizando uma abordagem multiferramentas para o tratamento e visualização de dados.


#📌 Objetivos do Projeto

Monitorar a taxa de ocupação hospitalar em tempo real.

Analisar o perfil demográfico dos pacientes (idade, gênero, tipo de internação).

Identificar gargalos operacionais (leitos em manutenção ou limpeza).

Prover insights para tomadas de decisão estratégicas e alocação de recursos.

#🛠️ Tecnologias e Ferramentas Utilizadas

1. Microsoft Excel & Power Query
Importação e Extração: Consolidação de bases de dados (Pacientes, Leitos e Movimentação).

Tratamento de Dados: Criação de Chaves Primárias (ID_Paciente, ID_Leito) e padronização de códigos (ex: converter "paciente 28" em P00028).

Modelagem: Criação de relacionamentos entre tabelas e análise inicial via Tabelas Dinâmicas.

2. Python (Pandas, Matplotlib & Seaborn)
ETL Avançado: Limpeza de dados nulos (fillna), tratamento de erros com try/except e conversão de tipos de dados (to_datetime).

Engenharia de Recursos: Criação de novas categorias de idade (Menor de idade, Adulto, Melhor idade) baseadas em lógica condicional.

Análise Estatística: Agrupamentos (value_counts) para entender a distribuição de leitos por setor.

Visualização de Dados: Geração de gráficos de contagem (countplot) para identificar picos de manutenção e limpeza por setor (UTI, Pediatria, etc).

3. Microsoft Power BI
Data Modeling: Construção de um modelo estrela (Star Schema) conectando tabelas de fatos e dimensões.

DAX (Data Analysis Expressions): Criação de medidas inteligentes como:

Contagem de Pacientes

Leitos Livres / Ocupados

Taxa de Ocupação % (considerando apenas leitos operacionais).

Dashboard Interativo: Desenvolvimento de painéis visuais com filtros de segmentação de dados, gráficos de picos históricos e indicadores de performance (KPIs).

#📊 Insights Gerados

Perfil de Internação: Identificou-se que a UTI possui um índice de ocupação crítico, especialmente para pacientes da "Melhor Idade" e "Menor de Idade".

Eficiência de Leitos: O dashboard revelou que setores como Pediatria apresentavam um número alto de leitos em manutenção, impactando a capacidade de atendimento.

Sazonalidade: Através do gráfico de linhas, foi possível observar picos de ocupação que sugerem a necessidade de reforço de equipe em períodos específicos.
