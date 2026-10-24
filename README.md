# ERP-Tycred-
Projeto de Erp para um trabalho da faculdade
# ERP Tycred - Sistema de Concessão e Recuperação de Crédito

## 📌 Sobre o Projeto
O ERP Tycred é um sistema de gestão financeira desenvolvido como projeto acadêmico para a Universidade Cidade de São Paulo (UNICID). O sistema atua nas duas pontas principais do ciclo de crédito pessoal: a originação e concessãoe a recuperação de crédito.

## ⚙️ Arquitetura e Módulos
O sistema foi estruturado em 4 módulos principais:
* **Módulo 1 (Núcleo Financeiro e Contratos):** Conta com motor de cálculos financeiros utilizando a Tabela Price, realiza o controle de clientes[cite: 2], aplica encargos como multas e juros e é responsável pela geração do contrato de empréstimo.
* **Módulo 2 (Painel Administrativo):** Interface de backoffice para o gerenciamento da esteira de análise de propostas, parametrização de matrizes de risco e deliberação de crédito por analistas.
* **Módulo 3 (CRM do Atendente):** Foco na organização do fluxo de trabalho e atendimento ao cliente, com gestão de chamados operacionais (tickets), controle de filas de inadimplência e formalização de acordos de renegociação.
* **Módulo 4 (Portal do Cliente):** Aplicação construída sob princípios Mobile-First voltada ao autoatendimento, permitindo que o devedor consulte seu cronograma de parcelas e saldo, gere cobranças via PIX ou Boletos e simule opções de renegociação de dívidas.

## 🔒 Segurança e Regras de Negócio
* **Conformidade com a LGPD:** O projeto garante o tratamento seguro de dados pessoais e aplica o mascaramento de dados sensíveis nas telas, como o CPF.
* **Proteção e Autenticação:** O sistema possui mecanismos de bloqueio após tentativas de acesso inválidas consecutivas e proteção de senhas dos usuários.
* **Auditoria Imutável:** Toda operação relevante, como alterações cadastrais e aprovações de crédito, gera um registro de log no banco de dados.
