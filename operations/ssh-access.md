# Acesso via SSH

## Comando
```bash
chmod 400 ec2-lab-key.pem
ssh -i "ec2-lab-key.pem" ec2-user@<IP-da-instancia>
