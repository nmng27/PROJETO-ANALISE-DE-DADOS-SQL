# Projeto de Análise de Dados Usando SQL

## Descrição do Projeto

Este projeto foi desenvolvido com o objetivo de aprimorar e relembrar conceitos fundamentais no processo de análise de dados, utilizando uma base de dados PostgreSQL. O foco é identificar fatores importantes para o tratamento e visualização de dados, que podem servir como base para um projeto de Business Intelligence (BI).

### Etapas do Projeto

1. **Criação das Tabelas**  
   A análise foi inspirada em uma rotina comum do meu dia a dia como recrutador de talentos. Desenvolvi uma modelagem simples, mas que representa bem as operações realizadas.

   - A primeira tabela criada foi a de **clientes (customers)**, contendo dados básicos como nome, e-mail, endereço e setor de atuação.
   - Em seguida, criei a tabela de **pedidos (requests)**, que simula o registro de solicitações para novas posições. Esses pedidos só podem ser aceitos caso exista um contrato previamente estabelecido.
   - Cada contrato, por sua vez, requer uma equipe específica para atender ao cliente, o que levou à criação da tabela de **colaboradores (employees)**.

   Essa estrutura foi desenhada para representar cenários reais do dia a dia e facilitar a análise.

---

## Comandos Utilizados

1. **`CREATE TABLE`**: Criar tabelas no banco de dados.
2. **`INSERT INTO`**: Inserir dados nas tabelas.
3. **`SELECT`** com filtros simples: Buscar dados específicos utilizando condições (e.g., `WHERE`).
4. **`COUNT(*)`**: Contar registros em tabelas. Também utilizei `COUNT` para realizar cálculos aritméticos e descobrir proporções.
5. **`GROUP BY` e `ORDER BY`**: Agrupar e ordenar os dados.
6. **`LIMIT`**: Selecionar apenas o primeiro ou os primeiros registros de um conjunto.
7. **`JOINS`**: Cruzar informações de diferentes tabelas para análises mais completas.

---

## Perguntas a Serem Respondidas Neste Projeto

1. Quantos clientes já utilizaram um serviço desta empresa hipotética?
2. Quantos clientes estão ativos?
3. Quantos clientes estão inativos?
4. Qual é a proporção de permanência na organização (not turnover)?
5. Quais são os tipos de contratos possíveis? Quais são os tipos de pedidos possíveis?
6. Qual é o setor principal que utiliza nossos serviços?
7. Quais são os contratos de cada cliente?
8. Quais são as regiões de cada cliente?
9. Outras perguntas exploratórias baseadas nos dados disponíveis.

---
