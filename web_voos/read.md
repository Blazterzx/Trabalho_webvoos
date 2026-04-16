#  Sistema de Reservas de Voos – Relatório

##  Introdução

Este trabalho consiste no desenvolvimento de um sistema de reservas de viagens de avião. O objetivo é permitir que companhias aéreas e passageiros utilizem uma plataforma digital para gerir voos e reservas, sem necessidade de deslocação física.

---

##  Descrição Geral do Sistema

O sistema foi concebido para funcionar de forma autónoma e independente de qualquer companhia aérea. Permite que:

* Companhias aéreas publiquem e gerem voos
* Passageiros consultem voos e efetuem reservas
* Administradores façam a gestão geral do sistema

---

##  Estrutura do Sistema

O sistema encontra-se dividido em várias áreas principais:

### 1. Gestão da Aplicação (Admin)

O administrador é responsável por:

* Inserir e gerir companhias aéreas
* Ativar ou desativar companhias
* Inserir aeroportos
* Consultar dados do sistema

---

### 2. Companhias Aéreas

Cada companhia pode:

* Inserir novos voos
* Alterar ou anular voos
* Consultar reservas associadas aos seus voos

Os voos incluem informações como origem, destino, data, horários e capacidade.

---

### 3. Passageiros

Os passageiros podem:

* Registar-se no sistema
* Consultar voos disponíveis
* Efetuar reservas
* Consultar informações sobre viagens

Cada reserva é individual e associada a um passageiro.

---

##  Base de Dados

A base de dados foi estruturada para armazenar toda a informação necessária ao sistema, incluindo:

* Companhias aéreas
* Aeroportos
* Voos
* Passageiros
* Utilizadores
* Reservas
* Registos de ações (logs)

As relações entre as tabelas permitem garantir a integridade dos dados e suportar todas as operações do sistema.

---

##  Funcionalidades de Consulta

Foram desenvolvidas funcionalidades que permitem:

* Consultar voos por aeroporto e data
* Listar voos entre origem e destino
* Consultar viagens de um passageiro
* Listar passageiros de um voo

Estas consultas ajudam a demonstrar o funcionamento da base de dados.

---

##  Interface Web

Foi também criada uma interface web simples com várias páginas:

* Página inicial
* Página de voos
* Página de passageiros
* Página de reservas
* Página de login

Estas páginas permitem representar visualmente o sistema e facilitar a navegação entre funcionalidades.

---

##  Conclusão

O sistema desenvolvido permite gerir reservas de voos de forma simples e organizada. A solução integra base de dados, lógica de aplicação e interface, garantindo uma estrutura funcional e coerente.

Este trabalho demonstra a aplicação de conceitos de bases de dados, programação e organização de sistemas, podendo ser expandido no futuro para uma solução mais completa.
