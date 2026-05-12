🏗️ Implementando minha Primeira Stack com AWS CloudFormation

Este repositório contém a documentação da minha primeira experiência prática com Infraestrutura como Código (IaC) utilizando o AWS CloudFormation, como parte da trilha de Cloud da Digital Innovation One (DIO).

🎯 Objetivo
O objetivo deste desafio foi automatizar o provisionamento de recursos na AWS. Em vez de criar serviços manualmente, utilizei um template em YAML para definir e lançar uma infraestrutura completa e segura.

🛠️ O que foi construído?
Através da Stack criada, provisionei um Amazon S3 Bucket com as seguintes configurações:
- Versionamento Habilitado: Para garantir a segurança e recuperação de versões anteriores de arquivos.
- Segurança Nativa: Bloqueio de acesso público configurado diretamente no código.
- Nomenclatura Dinâmica: Uso de funções intrínsecas da AWS para garantir nomes exclusivos.

📸 Evidência de Sucesso
O processo de criação foi monitorado via console, atingindo o status final de sucesso:

> Status: `CREATE_COMPLETE`

💡 Insights
- Reprodutibilidade: O CloudFormation garante que o ambiente possa ser recriado exatamente da mesma forma em segundos.
- Gestão de Mudanças: Entendi o ciclo de vida de uma Stack (criação, atualização e exclusão).
- Prática Profissional: Este conhecimento é a base para o uso de ferramentas como Terraform e Ansible em ambientes de produção.

Desenvolvido por Eduardo | Focado em AWS Cloud e Automação de TI.
