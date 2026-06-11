# 🛒 ShopEasy

## Observação

O **ShopEasy** é uma plataforma de e-commerce projetada para centralizar a experiência de compra online, oferecendo gerenciamento de produtos, carrinho de compras, pagamentos seguros, rastreamento de pedidos e controle administrativo em um único sistema.

O projeto foi desenvolvido na disciplina de **Projeto de Software da PUC Minas**, tendo como foco a análise, modelagem, arquitetura e documentação completa do sistema, sem implementação prática do software.

A documentação contempla requisitos, casos de uso, diagramas UML, arquitetura, banco de dados e especificações técnicas para uma futura implementação.

---

# 🚧 Status do Projeto

![Status](https://img.shields.io/badge/status-Concluído-success)
![Disciplina](https://img.shields.io/badge/PUC%20Minas-Projeto%20de%20Software-blue)
![Documentação](https://img.shields.io/badge/UML-Completa-orange)
![PlantUML](https://img.shields.io/badge/PlantUML-Modelagem-green)

---

# 📚 Índice

- 📝 Sobre o Projeto
- 🎯 Objetivos
- 👥 Atores do Sistema
- ✨ Funcionalidades Principais
- 🏗 Arquitetura
- 📊 Diagramas Desenvolvidos
- 🗄 Banco de Dados
- 📂 Estrutura da Documentação
- 👨‍💻 Autor
- 📚 Disciplina

---

# 📝 Sobre o Projeto

O ShopEasy surgiu da necessidade de modelar uma solução completa para comércio eletrônico capaz de atender clientes, administradores e fornecedores dentro de uma única plataforma.

A proposta contempla:

- Cadastro e autenticação de usuários
- Pesquisa de produtos
- Carrinho de compras
- Processamento de pagamentos
- Controle de estoque
- Rastreamento de pedidos
- Relatórios administrativos
- Avaliações de produtos

O projeto foi construído seguindo conceitos de Engenharia de Software, Arquitetura de Software e Modelagem UML.

---

# 🎯 Objetivos

O sistema busca:

- Facilitar compras online
- Automatizar processos de venda
- Melhorar o controle de estoque
- Integrar pagamentos e logística
- Fornecer informações gerenciais
- Garantir escalabilidade para crescimento futuro

---

# 👥 Atores do Sistema

## Cliente

- Realizar cadastro
- Fazer login
- Pesquisar produtos
- Comprar produtos
- Rastrear pedidos
- Avaliar produtos

## Administrador

- Gerenciar produtos
- Gerenciar pedidos
- Gerar relatórios

## Fornecedor

- Cadastrar produtos
- Atualizar estoque

## Sistemas Externos

- Stripe (Pagamentos)
- SendGrid (E-mails)
- Correios API (Frete e Rastreamento)

---

# ✨ Funcionalidades Principais

✅ Cadastro de Usuários

✅ Login com JWT

✅ Catálogo de Produtos

✅ Carrinho de Compras

✅ Finalização de Pedidos

✅ Integração com Gateway de Pagamento

✅ Rastreamento de Entregas

✅ Avaliação de Produtos

✅ Gestão de Estoque

✅ Relatórios Administrativos

---

# 🏗 Arquitetura

O ShopEasy utiliza:

## Frontend

- React
- TypeScript
- Redux Toolkit

## Backend

- Java 17
- Spring Boot 3
- Spring Security
- JWT

## Banco de Dados

- PostgreSQL

## Cache

- Redis

## Mensageria

- RabbitMQ

## Armazenamento

- MinIO / AWS S3

## Infraestrutura

- AWS ECS
- AWS RDS
- AWS ElastiCache
- CloudFront

A arquitetura segue o modelo de **Arquitetura em Camadas (Layered Architecture)** combinada com o padrão **MVC**.

---

# 📊 Diagramas Desenvolvidos

O projeto contempla:

## UML

- Diagrama de Casos de Uso
- Diagrama de Classes
- Diagramas de Sequência
- Diagramas de Comunicação
- Diagramas de Estados
- Diagrama de Componentes
- Diagrama de Implantação

## Arquitetura

- Modelo C4
- Arquitetura em Camadas

## Banco de Dados

- DER (Entidade-Relacionamento)
- Scripts DDL PostgreSQL

Todos os diagramas foram desenvolvidos utilizando **PlantUML**.

---

# 🗄 Banco de Dados

Principais entidades modeladas:

- Usuário
- Produto
- Categoria
- Carrinho
- Pedido
- ItemPedido
- Pagamento
- Avaliação

O projeto inclui:

- DER completo
- Estratégia de Mapeamento ORM
- Scripts SQL DDL

---

# 📂 Estrutura da Documentação

```text
docs/
│
├── Casos de Uso
├── Histórias de Usuário
├── Contratos de Operação
├── Diagramas UML
├── Diagramas C4
├── DER
├── Scripts SQL
└── Documento Final
```

---

# 👨‍💻 Autor

**Pedro Arthur Oliveira Silva**

🎓 Engenharia de Software – PUC Minas

📧 E-mail: pedroarthursilva05@gmail.com

💼 LinkedIn:  
https://www.linkedin.com/in/pedro-arthur-oliveira-silva-6888aa293

🐙 GitHub:  
https://github.com/PeterSilva05

---

# 📚 Disciplina

Projeto desenvolvido para a disciplina:

**Projeto de Software**  
Pontifícia Universidade Católica de Minas Gerais – PUC Minas

Professor: **João Paulo Aramuni**

---

# 📄 Licença

Projeto acadêmico desenvolvido exclusivamente para fins educacionais.

---

⭐ Desenvolvido por **Pedro Arthur Oliveira Silva** durante a disciplina de Projeto de Software da PUC Minas.
