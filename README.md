Sistema de Gestão de Funcionários
Este projeto é um sistema de gestão de funcionários que permite gerenciar informações sobre departamentos, funcionários e salários. O sistema é implementado usando MySQL e inclui operações para criar, atualizar, consultar e excluir dados.

Estrutura do Banco de Dados
O banco de dados GestaoFuncionarios contém três tabelas principais:

Departamentos

id_departamento: Identificador único do departamento (chave primária)
nome: Nome do departamento
Funcionarios

id_funcionario: Identificador único do funcionário (chave primária)
nome: Nome do funcionário
cargo: Cargo do funcionário
salario: Salário do funcionário
id_departamento: Identificador do departamento ao qual o funcionário pertence (chave estrangeira)
Salarios

id_salario: Identificador único do salário (chave primária)
id_funcionario: Identificador do funcionário (chave estrangeira)
data: Data do registro de salário
valor: Valor do salário
Operações
Criação das Tabelas: Comandos SQL para criar as tabelas Departamentos, Funcionarios e Salarios.
Inserção de Dados: Exemplos de dados inseridos nas tabelas para teste.
Consultas: Exemplos de consultas para listar funcionários com seus departamentos, calcular o salário total por departamento e verificar o histórico salarial de um funcionário.
Atualizações e Exclusões: Comandos SQL para atualizar salários, renomear departamentos e excluir registros com controle de integridade referencial.
Comandos SQL Importantes
Criar Banco de Dados e Tabelas
Inserir Dados
Consultas SQL para Relatórios
Atualizar e Excluir Registros
Como Usar
Configuração Inicial: Execute os comandos SQL fornecidos para criar o banco de dados e tabelas.
Inserir Dados: Insira dados de teste usando os comandos fornecidos.
Executar Consultas: Utilize as consultas SQL para gerar relatórios e verificar dados.
Atualizar e Excluir: Execute os comandos de atualização e exclusão conforme necessário.
Requisitos
MySQL Server
Cliente MySQL para execução dos comandos
