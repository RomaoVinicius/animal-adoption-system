<p align="center">
  <img src="/UNICAMP_logo.svg.png" height="80">
  <img src="/af-logo-ft-reduzido-pos.png" height="80">
</p>

<h1 align="center">🐾 Sistema de Adoção de Animais</h1>

<p align="center">
  <strong>Projeto desenvolvido para a disciplina SI200/SI203 – Algoritmos e Programação de Computadores II</strong><br>
  Faculdade de Tecnologia da Universidade Estadual de Campinas  (FT/UNICAMP)
</p>

---

## 📖 Sobre o projeto

O **Sistema de Adoção de Animais** tem como objetivo auxiliar no gerenciamento de cadastros de animais disponíveis para adoção e de possíveis adotantes.  
O sistema foi desenvolvido em **linguagem C** e permite que um administrador realize operações de **cadastro, consulta, atualização, exclusão e associação entre adotantes e animais**.

Este projeto foi desenvolvido como parte da avaliação da disciplina **Algoritmos e Programação de Computadores II**, com foco em modularização, uso de structs, manipulação de arquivos e boas práticas de programação.

---

## ⚙️ Funcionalidades principais

- 🐶 **Cadastro de animais** (nome, raça, faixa etária e disponibilidade para adoção)  
- 👤 **Cadastro de adotantes** (nome, CPF, CEP, telefone, preferência de animal e faixa etária desejada)  
- ✏️ **Atualização de cadastros** (animais e adotantes)  
- ❌ **Exclusão de registros** (por ID ou CPF)  
- 🔍 **Consulta de informações** (geral ou específica)  
- ❤️ **Realização de adoções** (associação entre adotante e animal)  
- 📋 **Listagem das adoções realizadas**

---

## 🧠 Requisitos não funcionais

- **Usabilidade:** interface de linha de comando simples e intuitiva  
- **Desempenho:** resposta rápida mesmo com até 1000 registros  
- **Confiabilidade:** integridade dos dados garantida durante as operações  
- **Portabilidade:** compatível com **Windows** e **Linux**  
- **Validação:** verificação de entradas obrigatórias e mensagens de erro claras  

---

## ⚙️ Fluxo geral do sistema

1. O programa inicia executando `main.c`, que exibe o **menu principal**.  
2. O usuário (administrador) escolhe uma das opções:
   - Cadastrar animal ou adotante  
   - Atualizar ou excluir registros  
   - Realizar adoção  
   - Consultar cadastros existentes  
3. As operações chamam as funções correspondentes em `animal.c`, `adotante.c` ou `utils.c`.  
4. Os dados são **salvos em arquivos `.txt`** dentro da pasta `data/`, garantindo persistência simples e legível.

## 👥 Colaboradores

Todos os integrantes participaram do desenvolvimento do software.
- **Gustavo Domingues Mancio** — RA: 248698  
- **Rafhael Casimiro Martins** — RA: 296058  
- **Samuel Germiniani** — RA: 239416  
- **Vinícius Romão do Nascimento** — RA: 223339

> 💡 *Trabalho desenvolvido em grupo como parte da disciplina SI200/SI203 – Algoritmos e Programação de Computadores II (FT/UNICAMP).*
