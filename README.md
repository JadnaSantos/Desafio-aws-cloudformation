## 🧪 Desafio AWS CloudFormation

Este laboratório tem como objetivo de implementar sua primeira Stack com AWS CloudFormation.
O entregável é um repositório organizado contendo anotações e insights adquiridos durante a prática, servindo como material de
apoio para os seusestudos e futuras implementações.

## 📋 O que é AWS CloudFormation
O AWS CloudFormation é um serviço da AWS que permite provisionar e gerenciar recursos de nuvem (infraestrutura) de forma declarativa, usando arquivos em YAML ou JSON.
Em vez de criar manualmente recursos pelo console (S3, EC2, VPC etc.), você descreve como a infraestrutura deve ser em um template, e o CloudFormation cuida de criar, atualizar ou deletar os recursos na ordem correta.
É a ideia de Infrastructure as Code (IaC) dentro da AWS.

## 🤔 Por que ele é útil?

Automação → elimina a criação manual de recursos (menos erros humanos).
Reprodutibilidade → você pode rodar o mesmo template em diferentes contas/ambientes (ex: dev, staging, prod).
Versionamento → templates ficam no Git, com histórico de mudanças.
Gerenciamento centralizado → CloudFormation controla dependências, ordem de criação e rollback automático se algo falhar.
Consistência → garante que ambientes fiquem iguais, sem “drift” (diferença entre o que foi planejado e o que existe).

## 👣 Desafio

1. Criação de template yaml para automatizar o desenvolvimento do recurso Amazon S3;
2. Desenvolvimento de uma stack para execução do template.
