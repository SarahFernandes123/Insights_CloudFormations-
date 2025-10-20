# Repositório de Anotações e Insights - Cloud Formations
#### Este repositório contém anotações, insights e pontos-chave adquiridos durante a prática de criação de stack atráves do CloudFormation. 

## Visão Geral da Solução
#### O recurso CloudFormation dentro da AWS permite que os usuários criem infraestrutura na nuvem por meio de código. É utilizado arquivo no modelo de escrita JSON ou YAML e são implementados com uma única unidade de chamada "pilha" (stack).
#### Foi criado um recurso de EC2 através do formato JSON. 
#### Para provisionar uma instância EC2, a AWS requer quatro propriedades básicas (além de ter um Security Group anexado):
   ##### 1. O identificador da Amazon Machine Image (AMI) precisa ser fornecido;
   ##### 2. É necessário definir o poder computacional da máquina e o custo;
   ##### 3. O par de chaves da EC2;
   ##### 4. Utilizar o type `"AWS::EC2::Instance"` para este recurso.

## Insights 
### Atráves da criação de uma EC2 pelo AWS CloudFormations foi possível adquirir os seguintes insights:

#### Documentação automatica: o templete em JSON ou YAML é uma documentação da sua infraestrutura, onde descreve seus recursos e configurações.
#### Rastreabilidade: Ao fazer o armazenagem do código para controle de versão, é mais fácil rastrear as alterações realizadas na infraestrutura ao longo do tempo.
#### Automação e velocidade: é possivel criar vários recursos de forma mais rápido e através de um único template. 
#### Controle e segurança: pode ser definido templates organizados e padronizados, garantindo que os recusos criados sigam as melhores práticas. 
#### Exclusão de forma simplificada: com um único comando pode ser excluido os recursos que foram criados, o que torna o processo mais rápido, principalmente em ambiente de teste.
