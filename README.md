# Sistema de Controle e Gerenciamento de Ordens de Serviço

## Descrição do Desafio
Este projeto tem como objetivo criar um esquema conceitual de um banco de dados para um sistema de controle e gerenciamento de ordens de serviço em uma oficina mecânica. A partir da narrativa fornecida, foi desenvolvida uma solução detalhada contemplando as entidades, atributos e relacionamentos necessários para atender ao contexto descrito.

## Objetivo
Criar o esquema conceitual do banco de dados para uma oficina mecânica, garantindo a organização e o controle eficientes das informações de clientes, veículos, equipes, mecânicos, ordens de serviço, serviços e peças.

## Narrativa
O sistema foi concebido para atender às seguintes necessidades:
- Clientes levam veículos à oficina mecânica para conserto ou revisão.
- Cada veículo é atribuído a uma equipe de mecânicos, que identifica os serviços a serem realizados e preenche uma Ordem de Serviço (OS).
- A OS inclui informações como número, data de emissão, status, data para conclusão, valor total, serviços realizados e peças utilizadas.
- O valor de cada serviço é calculado com base em uma tabela de referência de mão-de-obra.
- As peças também possuem valores que compõem a OS.
- Mecânicos possuem atributos como código, nome, endereço e especialidade.
- Equipes são compostas por diversos mecânicos e são responsáveis por avaliar e executar os serviços.

## Descrição da Solução
A modelagem proposta inclui as seguintes entidades principais:
- **Cliente**
- **Veículo**
- **Equipe**
- **Mecânico**
- **Serviço**
- **Peça**
- **Ordem de Serviço (OS)**

Os relacionamentos foram definidos com base na narrativa e incluem:
- Associação de Clientes a Veículos (1:N)
- Associação de Veículos a Ordens de Serviço (1:N)
- Associação de Equipes a Ordens de Serviço (1:N)
- Associação de Equipes a Mecânicos (1:N)
- Associação de Serviços a Ordens de Serviço (N:N)
- Associação de Peças a Ordens de Serviço (N:N)

### Esquema Conceitual
![Esquema Conceitual](Esquema Conceitual OS Oficina Mecânica.png)

---

Este documento serve como guia para a compreensão do desafio e da solução proposta. Caso surjam dúvidas ou a necessidade de ajustes, entre em contato para melhorias.
