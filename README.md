# Atividade com a Classe ContaBancaria

Este repositório contém dois exercícios em Java baseados em orientação a objetos, utilizando a classe `ContaBancaria`. O estilo é semelhante ao dos exercícios anteriores com a classe `Livro`.

---

## 💡 Exercício 1: CadConta

Crie um programa que implemente a classe `ContaBancaria`. Esta classe deve conter os seguintes atributos:

- Nome do titular
- Número da conta
- Agência
- Saldo

Adicione um método chamado `depositar`, que recebe um valor como parâmetro e incrementa o saldo da conta com esse valor.

Após isso, crie uma segunda classe chamada `Main` (classe principal), que conterá o método `main`. Nesta classe:

1. Crie um objeto da classe `ContaBancaria`.
2. Solicite ao usuário os valores para preencher os atributos da conta.
3. Leia também um valor a ser depositado.
4. Chame o método `depositar`.
5. Apresente em tela o estado atual do objeto, exibindo todas as informações da conta.

---

## 🗂️ Exercício 2: ListaContas

Usando a classe `ContaBancaria`, criada no exercício anterior, crie uma lista para armazenar diferentes contas bancárias. Esta lista deve ser implementada utilizando a coleção `ArrayList`.

Na classe principal:

1. Solicite ao usuário os dados de várias contas (nome do titular, número da conta, agência e saldo inicial).
2. Crie um conjunto de objetos `ContaBancaria` e armazene-os na lista.
3. Após o cadastro de todas as contas, apresente para cada uma:
   - O nome do titular
   - O saldo atual da conta

### Requisitos:

- A lista de contas deve ser global.
- Devem ser criados métodos separados para:
  - Cadastrar contas
  - Apresentar os dados das contas

---
