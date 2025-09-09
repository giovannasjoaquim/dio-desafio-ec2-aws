# dio-desafio-ec2-aws
Documentação prática sobre gerenciamento de instâncias EC2 na AWS, como parte do desafio da DIO.

# 🚀 Desafio DIO - Instância EC2 na AWS
Este repositório documenta minha experiência prática no uso de instâncias EC2 na AWS como parte do desafio proposto pela DIO.

## ✅ Etapas Realizadas
- Criação de instância EC2
- Acesso via SSH
- Instalação de pacotes
- Encerramento da instância

## 🧠 Aprendizados
- Como configurar e acessar uma instância
- Importância dos grupos de segurança
- Gerenciamento de volumes EBS

## 📊 Diagramas da Arquitetura AWS

Abaixo estão os fluxos representando o uso de serviços AWS, incluindo EC2, S3, Lambda, EBS e RDS, utilizados no desafio.

---

### 🖼️ Fluxo 1 - Upload para S3 e Processamento com Lambda

![Diagrama S3-Lambda](./images/Desafio.drawio.png)

Neste fluxo, o usuário envia um arquivo de um sistema de arquivos local para o Amazon S3. A chegada desse arquivo aciona automaticamente uma função Lambda, que pode ser usada para processar, validar ou mover o arquivo para outro serviço.

---

### 🖼️ Fluxo 2 - EC2 com Volumes EBS e Integração com RDS

![Diagrama EC2-EBS-RDS](./images/Desafio2.drawio.png)

Neste cenário, o ator interage com uma aplicação hospedada em uma instância EC2. A EC2 está conectada a dois volumes EBS (D e E), responsáveis pelo armazenamento de dados. Além disso, há integração com um banco de dados RDS para persistência e consulta de dados.

---




📚 [Documentação oficial da EC2](https://docs.aws.amazon.com/pt_br/ec2/)
