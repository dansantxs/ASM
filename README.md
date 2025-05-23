ERS - Especificação de Requisitos de Software
# **Sistema: ASM Commerce**
# **1. Introdução**
## **1.1 Objetivo do Sistema**
O ASM Commerce é um sistema ERP destinado a automatizar processos comerciais, incluindo vendas, compras, controle de estoque, financeiro e emissão de documentos fiscais. Visa atender empresas do setor de comércio, oferecendo uma base sólida para futuras expansões para outros segmentos.
## **1.2 Escopo**
Esta versão contempla os seguintes módulos: cadastros necessários, vendas, compras, controle de estoque, fluxo de caixa, contas a pagar, contas a receber e emissão de documentos fiscais.
## **1.3 Visão Geral**
Este documento descreve os requisitos funcionais e não funcionais do ASM Commerce, incluindo casos de uso e espaços reservados para modelos e diagramas UML.
# **2. Descrição Geral**
## **2.1 Perspectiva do Produto**
O ASM Commerce é uma evolução do ERP atualmente desenvolvido em VB5 pela Always System Manager, modernizado utilizando ASP.NET Core e PostgreSQL para proporcionar maior escalabilidade e manutenção.
## **2.2 Funções do Produto**
\- Cadastro de Produtos, Clientes, Fornecedores

\- Controle de Estoque

\- Emissão de Documentos Fiscais (NF-e, NFC-e)

\- Controle Financeiro (Contas a Pagar/Receber)

\- Fluxo de Caixa

\- Gestão de Compras e Vendas
## **2.3 Usuários e suas Características**
\- Administrador: Acesso total ao sistema.

\- Operador de Vendas: Realiza vendas e consulta estoque.

\- Financeiro: Gerencia contas a pagar, receber e fluxo de caixa.
## **2.4 Restrições**
\- Sistema baseado na web, utilizando ASP.NET Core MVC.

\- Banco de dados PostgreSQL.

\- Frontend responsivo para acesso via desktop e mobile.
# **3. Requisitos Específicos**
## **3.x Cadastro de Produtos**
\- O sistema deve permitir incluir, editar e excluir produtos.

\- O sistema deve controlar unidades de medida.

\- O sistema deve permitir cadastro de preços diferenciados.
## **3.x Controle de Estoque**
\- Movimentações automáticas via vendas e compras.

\- Relatório de estoque atual e histórico de movimentações.
## **3.x Emissão de Documentos Fiscais**
\- Emissão de NF-e e NFC-e conforme legislação vigente.

\- Validação de dados fiscais antes do envio.
# **4. Requisitos Não Funcionais**
\- Desempenho: O sistema deve processar uma venda em até 2 segundos.

\- Segurança: Autenticação baseada em Identity com políticas de acesso.

\- Tecnologia: ASP.NET Core 8, PostgreSQL, Entity Framework Core.

\- Compatibilidade: Interface responsiva para desktop e dispositivos móveis.
# **5. Casos de Uso**
## **UC001: Cadastrar Produto**
Ator: Administrador

Fluxo Principal:

\- Usuário acessa a tela de produtos.

\- Clica em "Novo".

\- Preenche os dados.

\- Clica em "Salvar".
## **UC002: Realizar Venda**
Ator: Operador de Vendas

Fluxo Principal:

\- Usuário acessa a tela de vendas.

\- Seleciona cliente e produtos.

\- Confirma pagamento.

\- Emite comprovante.
# **6. Modelos ou Protótipos**
Espaço reservado para inclusão de diagramas UML e protótipos de telas.
# **7. Glossário**
\- CFOP: Código Fiscal de Operações e Prestações.

\- NF-e: Nota Fiscal Eletrônica.

\- NFC-e: Nota Fiscal de Consumidor Eletrônica.

\- ERP: Enterprise Resource Planning - Sistema de gestão empresarial.
