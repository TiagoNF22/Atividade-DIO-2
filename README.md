# Atividade-DIO-2# 📊 Agregador de Dados para Declaração de Imposto de Renda

Este repositório contém uma ferramenta desenvolvida no Microsoft Excel para centralizar, organizar e validar todas as informações essenciais necessárias para a elaboração e entrega da declaração de imposto de renda. O projeto foca na criação de uma interface intuitiva, com validação de dados e separação clara por categorias de rendimentos e dados cadastrais.

---

## 🗂️ Estrutura da Ferramenta (`Book1.xlsx`)

A ferramenta foi construída em várias abas integradas para garantir uma navegação fluida e sem erros:

### 1. 👤 Aba TITULAR (`TITULAR`)
* **Objetivo:** Centralizar o registo de todas as informações cadastrais e pessoais do contribuinte.
* **Campos principais:** Nome completo, CPF, data de nascimento, título de eleitor, dados do cônjuge, morada (com rua abreviada e CEP), contactos telefónicos (telefone e telemóvel), correio eletrónico, histórico de alterações e indicação de residência no exterior.

### 2. 💰 Aba INFORMES (`INFORMES`)
* **Objetivo:** Consolidar os saldos e rendimentos bancários de diferentes instituições financeiras.
* **Funcionalidade:** Permite listar múltiplos bancos (utilizando listas de validação baseadas na aba de apoios), inserir o valor atual em cada instituição e anexar comprovativos. Conta com uma fórmula de soma automática (`=SUM(...)`) que calcula o **Total** consolidado nas contas bancárias.

### 3. 📝 Aba NOTAS (`NOTAS`)
* **Objetivo:** Exercer o controlo detalhado das entradas financeiras mês a mês.
* **Campos principais:** Registo cronológico contendo **Data**, **Categoria** e **Valor**, servindo como extrato de holerites ou notas bancárias de receitas ao longo do ano fiscal.

### 4. 📋 Aba TABELAS (`TABELAS`)
* **Objetivo:** Servir de base de dados auxiliar para as validações de dados da aplicação.
* **Destaque:** Contém a tabela oficial com códigos e nomes de instituições financeiras (bancos) utilizadas nos menus pendentes das abas de rendimentos.

---

## ⚙️ Tecnologias e Recursos do Excel Utilizados

* **Validação de Dados:** Aplicação de listas pendentes para seleção uniforme de instituições bancárias e categorias, evitando erros de digitação.
* **Fórmulas e Funções Matemáticas:** Utilização de funções como `=SUM()` para o cálculo automático de totais financeiros.
* **Design focado na Experiência do Utilizador (UX):** Organização visual em blocos limpos, separação clara entre dados estáticos de preenchimento e campos calculados automaticamente.

---

## 🚀 Como Utilizar o Repositório

1. Descarregue o ficheiro `Book1.xlsx` disponível neste repositório.
2. Abra o ficheiro no Microsoft Excel.
3. Preencha os seus dados pessoais na aba **TITULAR**, insira os saldos bancários em **INFORMES** e faça o registo das entradas mensais em **NOTAS**.

---
*Projeto desenvolvido para fins académicos e práticos no âmbito dos desafios de Excel da DIO.*
