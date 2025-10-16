# 🍺 Cervejaria BeboSim – Aplicação de Princípios Ágeis e Gerência de Configuração

> Projeto desenvolvido na disciplina **Engenharia de Software**  
> Professor: **Radamés Pereira**  
> Universidade Comunitária da Região de Chapecó (UNOCHAPECÓ)

---

## 🧭 1. Introdução

### 1.1. Propósito
Este projeto visa documentar a especificação do **Sistema de Controle de Produção e Vendas da Cervejaria BeboSim**, empresa fictícia utilizada como estudo de caso para aplicar **Princípios Ágeis** e **Gerência de Configuração de Software (GCS)**.

O sistema busca integrar todas as operações da cervejaria — desde a **produção**, **estoque**, **vendas** e **campanhas publicitárias** — em uma plataforma web moderna, segura e de fácil manutenção.

---

### 1.2. Escopo do Projeto
O sistema abrangerá o **cadastro e gerenciamento** de:

- 🍻 **Produtos**: cervejas, refrigerantes, águas minerais  
- 🏭 **Unidades de Produção**: fábricas com diferentes produtos e localizações  
- 📦 **Embalagens**: materiais, volumes e custos  
- 👥 **Equipes de Vendas**: vendedores, gerentes e regiões de atuação  
- 🧾 **Clientes**: empresas (pessoas jurídicas)  
- 💰 **Pedidos de Venda**: controle de emissão, produtos e responsáveis  
- 📢 **Campanhas Publicitárias**: acompanhamento de retorno e investimentos  

Essas entidades estarão inter-relacionadas, permitindo controle de histórico, rastreabilidade e relatórios analíticos.

---

### 1.3. Definições, Acrônimos e Abreviações

| Termo | Definição |
|--------|-----------|
| **GCS** | Gerência de Configuração de Software |
| **IEEE** | Institute of Electrical and Electronics Engineers |
| **PO** | Product Owner |
| **SM** | Scrum Master |

---

## 🧩 2. Descrição Geral

### 2.1. Perspectiva do Produto
O sistema será uma **aplicação web responsiva**, acessível via navegadores em desktop e dispositivos móveis.  
Ele substituirá planilhas e controles manuais por uma **plataforma centralizada e automatizada**, integrada aos processos da Cervejaria BeboSim.

---

### 2.2. Funções do Produto

| Categoria | Funções Principais |
|------------|--------------------|
| **Produção** | Cadastro de produtos, fórmulas e unidades produtivas |
| **Vendas** | Cadastro de equipes, vendedores, clientes e emissão de pedidos |
| **Campanhas** | Criação, controle e análise de campanhas publicitárias |
| **Relatórios** | Indicadores de produção, vendas, comissões e desempenho de campanhas |

---

### 2.3. Características dos Usuários

| Tipo de Usuário | Descrição |
|------------------|-----------|
| **Gerente-Geral** | Visualiza todos os módulos e relatórios estratégicos |
| **Gerente de Produção** | Administra produtos, fórmulas e fábricas |
| **Gerente de Vendas** | Gerencia equipes e vendedores |
| **Vendedor** | Registra clientes e pedidos de venda |

---

### 2.4. Restrições

- O sistema deve ser desenvolvido com **tecnologias web modernas e responsivas**  
- O acesso será controlado por **níveis de permissão**  
- Deve garantir **integridade, segurança e consistência dos dados**  
- O código será versionado e auditável via **Git/GitHub**

---

## ⚙️ 3. Requisitos Específicos

Os requisitos serão detalhados em **Épicos**, **Histórias de Usuário** e **Critérios de Aceite**, conforme o framework **Scrum**.  
Essas especificações estarão descritas na **Wiki do repositório**, incluindo requisitos funcionais e não funcionais.

Exemplo de história de usuário:

> **Como** gerente de produção  
> **quero** cadastrar novos produtos e fórmulas  
> **para que** o sistema registre automaticamente os custos e disponibilize-os para vendas.

---

## 🏗️ 4. Arquitetura do Sistema

A arquitetura do sistema será documentada com base no **Modelo C4**, detalhando:

- **Contexto** (nível macro da aplicação)  
- **Contêineres** (módulos e componentes do sistema)  
- **Componentes** (estruturas internas e tecnologias)  
- **Código** (integrações e frameworks)

---

## ⚙️ Princípios Ágeis no Projeto

O projeto BeboSim segue os valores e princípios do **Manifesto Ágil**:

| Valor Ágil | Aplicação no Projeto |
|-------------|----------------------|
| **Indivíduos e interações** mais que processos e ferramentas | Reuniões diárias e comunicação direta entre equipe e stakeholders |
| **Software funcionando** mais que documentação abrangente | Entregas parciais e incrementais de módulos do sistema |
| **Colaboração com o cliente** mais que negociação de contratos | Feedback contínuo do gerente da BeboSim e stakeholders |
| **Responder a mudanças** mais que seguir um plano | Adaptação rápida a novas demandas e requisitos |

### 📅 Práticas Adotadas

- **Sprints curtos** de 2 semanas  
- **Equipe auto-organizada e colaborativa**  
- **Foco na simplicidade e valor entregue**

---

## 🧩 Gerência de Configuração de Software (GCS)

A **GCS** garante controle, integridade e rastreabilidade sobre os artefatos do projeto.

### 🔹 Conceitos-Chave

- **Item de Configuração:** Código-fonte, documentação, requisitos, etc.  
- **Linha de Base:** Versão aprovada que serve de referência.  
- **Controle de Versão:** Utilização do **Git** e **GitHub**.  
- **Controle de Mudanças:** Issues e Pull Requests.  
- **Auditoria de Configuração:** Verificação da conformidade das entregas.

### Autores
- André Leonardo Ugolini []
- Everton Marlon Berlezi [everton65@unochapeco.edu.br]
- Richard Leonardo Otto [richard1@unochapeco.edu.br]
- Vitor Gabriel Cagliari Loli [vlolidev@unochapeco.edu.br]
- Vitor Juan Bueno Chaves [cosmos@unochapeco.edu.br]
