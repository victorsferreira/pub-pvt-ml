- Criar VPC ip/mascara
- Criar Subnet ip/mascara
- Criar Router Table
- Criar Internet Gateway
- Associar Internet Gateway a Subnet
- Associar Router Table a Subnet
- Associar Subnet a VPC
- ACL: firewall da Rede
- Security Group: firewall da instância

eval "$(ssh-agent -s)"
ssh-add ~/.ssh/github