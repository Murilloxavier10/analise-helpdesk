📊 Projeto End-to-End: Inteligência Operacional em Help Desk
📋 Sobre o Projeto
Este projeto simula uma operação real de suporte técnico (Help Desk), onde o objetivo foi transformar dados brutos de atendimento em insights estratégicos para a gestão. O projeto resolve dores comuns como: identificação de gargalos de tempo, análise de satisfação do cliente (CSAT) e otimização de escala de funcionários.

🛠️ Tecnologias Utilizadas
Python: Extração, limpeza e enriquecimento dos dados (Pandas, Numpy).

MySQL: Armazenamento e estruturação da base de dados relacional.

Power BI: Criação de Dashboards interativos e cálculos de métricas (DAX).

🚀 Etapas do Projeto
1. Engenharia e Preparação de Dados (Python)
Geração de dados sintéticos realistas baseados em padrões de atendimento.

Tratamento de datas e cálculo de Tempo de Resolução (TMR).

Enriquecimento da base com métricas de Satisfação (CSAT) e Reaberturas.

Conexão via SQLAlchemy para persistência dos dados no MySQL.

2. Modelagem e Armazenamento (SQL)
Criação de esquemas de banco de dados (meu_projetohelpdesk).

Consultas para validação de integridade e exportação de views para o BI.

3. Business Intelligence (Power BI)
O Dashboard foi dividido em 5 visões estratégicas:

Panorama Executivo: KPIs macro de volume, SLA e satisfação geral.

Performance de Equipe: Ranking de eficiência e produtividade por agente.

Voz do Cliente: Análise de sentimento e correlação entre reaberturas e notas.

Diagnóstico de Gargalos: Identificação de categorias com maior lentidão.

Planejamento de Demanda: Heatmap de picos de horários e dias da semana.

📈 Principais Insights Gerados
Identificação de Gargalos: O setor de "Software" apresentou o maior TMR, indicando necessidade de treinamento técnico.

Impacto na Satisfação: Clientes com tickets reabertos 2x ou mais apresentam queda de 25% no CSAT.

Eficiência de Escala: Identificamos picos de abertura de chamados entre 10h e 11h, sugerindo ajuste na escala de almoço da equipe.

📁 Estrutura do Repositório
/scripts: Código Python (.ipynb ou .py) usado no tratamento.

/sql: Comandos para criação e consulta no MySQL.

/dashboard: Arquivo .pbix do Power BI.

/docs: Prints das páginas do Dashboard.

Desenvolvido por: [Murillo Xavier Bizerra] Analista/cientista de Dados em Formação