# 🚀 RELATÓRIO DE IMPLEMENTAÇÃO AWS
## 📊 Análise de Custos
Data: 02/01/2026 

Empresa: Abstergo Industries

Responsável: Kaliany Félix

<h2>Introdução</h2>
   Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Kaliany Félix. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:
<h3>Etapa 1: Otimização de Armazenamento</h3>

Nome da ferramenta: Amazon S3 Intelligent-Tiering
Foco da ferramenta: Redução de custos de armazenamento através de gerenciamento automático de ciclo de vida de dados
Descrição de caso de uso: Implementação do S3 Intelligent-Tiering para dados históricos da farmácia (logs de vendas, relatórios trimestrais e backups com mais de 90 dias). A ferramenta monitora automaticamente os padrões de acesso e move objetos entre classes de armazenamento (Standard, Infrequent Access e Archive), garantindo o menor custo por GB sem intervenção manual. Resultado esperado: redução de 60-70% nos custos de storage.

<h3>Etapa 2: Computação Serverless</h3>

Nome da ferramenta: AWS Lambda
Foco da ferramenta: Eliminação de custos de servidores ociosos através de computação sob demanda
Descrição de caso de uso: Migração de processos batch e tarefas agendadas (conciliação de estoque noturna, scripts de BI e alertas diários) de instâncias EC2 para funções Lambda. O modelo serverless cobra apenas pelo tempo efetivo de execução em milissegundos, eliminando custos de servidores rodando 24/7 com baixa utilização. Stack implementada: Python 3.11 com Pandas, EventBridge para agendamento e SNS para notificações. Resultado esperado: redução de 75-85% em custos de computação.

<h3>Etapa 3: Governança Financeira (FinOps)</h3>

Nome da ferramenta: AWS Cost Explorer com Budgets
Foco da ferramenta: Controle proativo de custos e prevenção de desperdícios através de análise e alertas automatizados
Descrição de caso de uso: Configuração do Cost Explorer para análise detalhada de gastos por serviço, tag e departamento, combinado com Budgets para estabelecer limites mensais ($5.000 global, com distribuição por serviço: EC2 $1.500, S3 $800, Lambda $200, RDS $1.000). Alertas automáticos via SNS/e-mail são disparados em 50%, 80% e 100% do budget, permitindo ação preventiva. Dashboard no QuickSight fornece visibilidade em tempo real e previsões com ML. Resultado esperado: visibilidade total de custos e redução de 15-25% em desperdícios identificados.


<h3>Conclusão</h3>
A implementação de ferramentas na empresa Abstergo Industries tem como esperado a otimização de custos operacionais em armazenamento e computação (redução projetada de 35-40%), estabelecimento de governança financeira efetiva através de visibilidade e alertas em tempo real, e modernização da arquitetura para modelo serverless escalável, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

<h4>Assinatura do Responsável pelo Projeto:</h4>

Kaliany Félix
