## Desafio: Criar um Assistente de Delivery com AWS Step Functions


Neste desafio tive que criar um assistente de delivery que permite ao usuário fazer pedidos e receber sugestões para complementar uma experiência gastronômica em um jantar romântico. O que o assistente de delivery foi capaz de executar:
- Recebeu o pedido do usuário;
- Gerou sugestões  de combinações de itens para o pedido;
- E armazenou o histórico de conversação para referência futura.

O código-fonte está localizado na pasta "src".


### AWS Step Functions

O AWS Step Functions é um serviço de orquestração de fluxos de trabalho que permite automatizar e gerenciar processos em diversas aplicações e serviços AWS. Ele facilita a coordenação de tarefas sequenciais e paralelas, ajudando a construir aplicações escaláveis e robustas.

### Workflow Studio

O Workflow Studio é uma ferramenta visual para criar, editar e gerenciar fluxos de trabalho de maneira intuitiva. Ele permite aos usuários desenhar processos de negócios, automatizar tarefas e integrar diferentes sistemas e serviços, tudo através de uma interface gráfica amigável. Isso facilita a orquestração de processos complexos sem a necessidade de codificação extensiva.

### AWS State Language (ASL)

A AWS State Language (ASL) é uma linguagem baseada em JSON usada para definir os fluxos de trabalho no AWS Step Functions. Ela permite descrever estados, transições e comportamentos de uma máquina de estados de forma clara e estruturada.

### AWS Bedrock

O AWS Bedrock permite que você utilize modelos de IA generativa de alta performance em suas aplicações, conectando fontes de dados privadas e personalizando os modelos com técnicas como ajuste fino e geração aumentada de recuperação (RAG).


### Links Úteis

- [AWS Step Functions](https://aws.amazon.com/pt/step-functions/) - Introdução ao AWS Step Funcions.
- [AWS Step Functions Examples](https://github.com/aws-samples/aws-stepfunctions-examples) - Exemplos de aplicações do AWS Step Funcions.
- [Serverless e Amazon Bedrock](https://aws.amazon.com/pt/blogs/aws-brasil/como-criar-um-assistente-virtual-de-baixa-latencia-com-multiplos-modelos-usando-serverless-e-amazon-bedrock/) - Criando um Assistente Virtual de Baixa Latência com Múltiplos Modelos Usando Serverless e Amazon Bedrock.