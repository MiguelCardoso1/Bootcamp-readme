📊 Relatório de Implementação de Serviços AWS
Redução de Custos – Distribuidora Farmacêutica

Empresa: Abstergo Industries
Responsável: Miguel Malton
Data: 11/02/2026

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Miguel Malton. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos na infraestrutura tecnológica da distribuidora farmacêutica, otimizando armazenamento de dados, processamento de sistemas internos e uso de servidores.

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1:

Nome da ferramenta: Amazon S3 com Intelligent-Tiering

Foco da ferramenta: Armazenamento otimizado e redução de custos com dados

Descrição de caso de uso:

A distribuidora farmacêutica armazena notas fiscais, registros de lotes, documentos regulatórios da Anvisa, relatórios logísticos e históricos de vendas. Atualmente, esses dados estão armazenados em servidores locais com alto custo de manutenção.
Com a implementação do Amazon S3 utilizando a classe Intelligent-Tiering, os arquivos são automaticamente movidos para camadas de armazenamento mais baratas conforme a frequência de acesso diminui.
Isso reduz custos com infraestrutura física, energia, manutenção de servidores e backup, além de garantir alta durabilidade e escalabilidade.

Etapa 2:

Nome da ferramenta: Amazon EC2 com Auto Scaling e Savings Plans

Foco da ferramenta: Otimização de servidores e redução de custos operacionais

Descrição de caso de uso:

Os sistemas de gestão de estoque e pedidos da distribuidora apresentam picos de uso em horários comerciais e quedas significativas durante a madrugada.
Com o uso do Auto Scaling, os servidores aumentam automaticamente durante horários de pico e reduzem quando a demanda cai. Além disso, a contratação de Savings Plans permite desconto significativo para uso previsível de instâncias.
Essa combinação evita pagamento por capacidade ociosa e reduz custos com servidores superdimensionados.

Etapa 3:

Nome da ferramenta: AWS Lambda

Foco da ferramenta: Processamento sob demanda e eliminação de servidores dedicados

Descrição de caso de uso:

Diversas rotinas internas, como validação de pedidos, geração de relatórios diários e envio automático de notificações para farmácias clientes, podem ser executadas de forma automatizada.
Com AWS Lambda, essas funções são executadas apenas quando acionadas, sem necessidade de manter servidores ativos 24 horas por dia.
O modelo de cobrança por execução reduz drasticamente custos operacionais, especialmente para tarefas intermitentes.

A implementação de ferramentas na empresa Abstergo Industries tem como esperado a redução imediata de custos com infraestrutura física, servidores ociosos e armazenamento de dados.
Além da economia financeira, as soluções proporcionam maior escalabilidade, segurança e disponibilidade, aumentando a eficiência e a produtividade da empresa.
Recomenda-se a continuidade da utilização das ferramentas implementadas e a análise constante de novos serviços AWS que possam aprimorar ainda mais os processos logísticos, operacionais e administrativos da distribuidora farmacêutica.

Assinatura do Responsável pelo Projeto:

Miguel Malton

