# Desafio CloudFormation - Servidor Web

Este projeto cria uma instância EC2 com Apache usando AWS CloudFormation. Inclui regras de segurança e parâmetros reutilizáveis.

## Recursos criados
- EC2 Amazon Linux 2
- Apache instalado via UserData
- Security Group com portas 22 e 80 abertas

## Como usar
1. Crie uma chave SSH no EC2
2. Edite `parameters.json` com o nome da chave
3. Execute via AWS CLI
