# 📊 Agregador de Dados para Declaração de Imposto de Renda no Excel

[![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://office.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![DIO](https://img.shields.io/badge/DIO-Challenge-007ACC?style=for-the-badge)](https://dio.me)

## 📌 Sobre o Projeto

O **Agregador de Dados para Imposto de Renda** é uma solução em Microsoft Excel desenvolvida para organizar, consolidar e validar previamente todas as informações necessárias para a Declaração de Ajuste Anual do Imposto de Renda (IRPF).

Muitos contribuintes enfrentam dificuldades na coleta descentralizada de informes de rendimentos, holerites e comprovantes bancários. Esta ferramenta centraliza a qualificação do titular, os saldos mantidos em instituições financeiras e o fluxo de entradas de receitas ao longo do ano, reduzindo erros de preenchimento e acelerando a entrega oficial.

> **Destaque de Portfólio:** Este projeto demonstra habilidades em modelagem de dados no Excel, arquitetura de planilhas intuitivas (UX/UI para usuários não técnicos), governança de dados com validações de entrada e organização de apoio a processos fiscais/financeiros.

---

## 🚀 Funcionalidades Principais

- **Qualificação Cadastral do Titular (`TITULAR`):** Coleta estruturada dos dados pessoais, fiscais (CPF, Título de Eleitor) e flags de controle (mudança de endereço, dependente cônjuge, residência no exterior).
- **Consolidação de Informes Bancários (`INFORMES`):** Mapeamento de saldos por instituição financeira, com rastreabilidade dos arquivos de informes anexados (`.pdf`).
- **Registro Sequencial de Entradas (`NOTAS`):** Controle contínuo de receitas com categorização padronizada de origem do rendimento.
- **Tabela de Domínio Bancário (`TABELAS`):** Relação completa de bancos cadastrados no sistema financeiro nacional para consulta e validação cruzada.
- **Validação e Integridade de Dados:** Aplicação de listas suspensas (*Data Validation*) para padronização de campos de decisão (`SIM/NÃO`) e classificação de receitas (`HOLERITE`, `CNPJ`, `FREELANCE`).

---

## 🛠️ Estrutura do Arquivo

O arquivo `planilha_app_declaracao.xlsx` é dividido nas seguintes abas:

| Aba | Descrição |
| :--- | :--- |
| `TITULAR` | Formulário de dados cadastrais, endereço e status fiscal do contribuinte. |
| `INFORMES` | Agregador de saldos bancários e vínculo de comprovantes anexos. |
| `NOTAS` | Histórico cronológico das entradas de receita e suas categorias. |
| `TABELAS` | Base de conhecimento complementar (códigos e nomes das instituições bancárias). |

---

## 💼 Competências Demonstradas (Skills)

- **Modelagem e Estruturação de Dados no Excel**
- **Validação de Entrada e Controle de Integridade**
- **Desenvolvimento de Soluções No-Code para Negócios/Finanças**
- **UX em Planilhas (Design Limpo e Navegação Intuitiva)**
- **Documentação Técnica e Governança de Projetos (GitHub)**

---

## ✒️ Autor

Desenvolvido por **Jean Claude** como parte do Desafio de Projeto da **Digital Innovation One (DIO)**.

---
*Este repositório faz parte do meu portfólio de tecnologia e análise de dados. Fique à vontade para explorar o arquivo e entrar em contato via LinkedIn para oportunidades profissionais!*