# Configuração da Instância EC2

## Escolha da AMI
- Amazon Linux 2023 (Free Tier elegível)

## Tipo de Instância
- t2.micro (1 vCPU, 1 GB RAM)

## Armazenamento
- 8 GB padrão SSD (gp2)

## Rede
- VPC padrão
- Sub-rede pública

## Chave SSH
- Nome da chave: `ec2-lab-key`
- Permissões ajustadas com `chmod 400 ec2-lab-key.pem`
