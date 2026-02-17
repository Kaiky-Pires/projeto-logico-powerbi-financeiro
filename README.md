# projeto-logico-powerbi-financeiro
Este repositório foca-se na arquitetura de dados e lógica de negócio, servindo como blueprint para a implementação no Power BI Desktop.

# Planejamento Estratégico de Dashboard: Vendas e Lucratividade

# 1. Objetivo do Relatório
Este projeto apresenta o planejamento para a transformação de dados brutos de vendas (Financial Sample) em indicadores visuais para suporte à decisão gerencial. O foco é estruturar uma análise geográfica e segmentada para identificar a rentabilidade da operação por país e setor.

# 2. Engenharia e Preparação dos Dados (ETL)
O processo lógico de tratamento de dados foi estruturado nas seguintes etapas:
Importação: Conexão com a base de dados em formato Excel.
Tratamento: Verificação de tipos de dados, garantindo que colunas de Sales (Vendas) e Profit (Lucro) estejam configuradas como Moeda e que a coluna Country (País) esteja categorizada como localidade geográfica para integração com mapas.
Métricas Chave: Definição de KPIs de faturamento total, volume de unidades vendidas e margem líquida de lucro.

# 3. Arquitetura da Terceira Página (Análise Personalizada)
A disposição dos visuais foi projetada para responder a questões críticas de negócio:
Análise de Volume e Vendas por País (Mapa 1):
Visual: Mapa coroplético.
Lógica: Utilização de Sales e Units Sold para identificar a relação entre faturamento e volume físico de mercadorias por região.

# Análise de Lucro Geográfico (Mapa 2):
Visual: Mapa de bolhas.
Lógica: Escalonamento do campo Profit para demonstrar visualmente onde a empresa retém maior margem, diferenciando faturamento bruto de resultado líquido.
Rentabilidade por Segmento (Gráfico de Pizza):
Visual: Gráfico de setores.

# Lógica: Distribuição percentual do lucro por segmento de mercado (Governo, Empresas, Pequenos Negócios), permitindo a identificação da fatia mais lucrativa da operação.

# 4. Conclusão e Insights Esperados
A solução proposta permite ao gestor identificar, de forma centralizada, a discrepância entre faturamento e lucratividade real. O projeto demonstra a viabilidade de converter registros financeiros em uma ferramenta estratégica de gestão por meio da arquitetura de dados correta.
