
# Engenharia de Software – Rede de Cinemas

## 1. Regras de Negócio

RN01 — Toda sessão precisa obrigatoriamente estar vinculada a um filme já cadastrado no sistema.

RN02 — O sistema não pode permitir o registro de público com valores negativos.

RN03 — Os filmes precisam possuir informações básicas obrigatórias, como título, gênero e duração.

RN04 — O sistema deve registrar a quantidade de pessoas presentes em cada sessão individualmente.

RN05 — O sistema deve permitir a consulta das sessões cadastradas juntamente com o filme correspondente.

RN06 — O horário da sessão deve ser informado no momento do cadastro.

RN07 — O sistema deve armazenar os dados de filmes e sessões no banco SQLite.

---

## 2. Requisitos Funcionais

RF01 — O sistema deve permitir o cadastro de filmes contendo título, gênero e duração.

RF02 — O sistema deve permitir o cadastro de sessões de cinema.

RF03 — O sistema deve permitir registrar o público presente em cada sessão.

RF04 — O sistema deve listar todas as sessões cadastradas.

RF05 — O sistema deve permitir consultar os filmes disponíveis no sistema.

RF06 — O sistema deve armazenar os dados de filmes e sessões utilizando SQLite.

RF07 — O sistema deve utilizar arquitetura MVC com as camadas Controller, Service e Repository.

---

## 3. Caso de Uso Implementado

O caso de uso implementado foi o registro de público em uma sessão de cinema.

---

## 4. Arquitetura Utilizada

- MVC
- Service
- Repository
- SQLite

---

## 5. Diagramas UML

Os diagramas UML separados estão na pasta:

casos_de_uso/

Cada arquivo possui um diagrama individual em PlantUML.
