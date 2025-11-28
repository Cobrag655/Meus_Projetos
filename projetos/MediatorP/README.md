# 📊 Sistema de Notas 4.0 – Aplicação em Tkinter

Este projeto é uma aplicação gráfica desenvolvida em **Python** utilizando o **Tkinter**, criada com o objetivo de facilitar o gerenciamento de notas dos alunos. A ferramenta permite cadastrar alunos, inserir notas bimestrais, calcular médias automaticamente e visualizar o desempenho geral da turma.

## 🚀 Funcionalidades Principais

* **Cadastro de Alunos** com nome e quatro notas bimestrais.
* **Validação de Entradas** garantindo que apenas valores válidos sejam registrados.
* **Cálculo Automático da Média** e definição da situação final (Aprovado/Reprovado).
* **Tabela Interativa (Treeview)** exibindo todos os alunos adicionados.
* **Identificação Visual**: alunos aprovados aparecem em verde e reprovados em vermelho.
* **Persistência Temporária**: dados ficam disponíveis enquanto a aplicação está aberta.

## 🗂️ Estrutura da Interface

A interface é organizada com campos de entrada para:

* Turma
* Professor
* Nome do aluno
* Quatro notas bimestrais

Além disso, a janela contém botões para:

* **Adicionar aluno**
* **Exibir tabela de resultados**

E por fim, uma tabela dinâmica onde os dados são exibidos.

## 🧠 Lógica de Funcionamento

1. O usuário insere turma, professor e dados do aluno.
2. O sistema valida as notas (0 a 10).
3. A média é calculada automaticamente.
4. O aluno é salvo e exibido na lista.
5. A tabela mostra todos os registros formatados.

## 🛠️ Tecnologias Utilizadas

* **Python 3.x**
* **Tkinter** (Interface gráfica)
* **ttk.Treeview** (Tabela de resultados)

## 📦 Compilação para Executável

Comandos úteis já utilizados durante o desenvolvimento:

### Gerar executável com console:

```
pyinstaller --onefile Mediator4.py
```

### Gerar executável sem console e com ícone:

```
python -m PyInstaller --onefile --noconsole --icon="python_94570.ico" Mediator4.py
```

## 🎯 Objetivo do Projeto

Servir como uma aplicação prática para consolidar meus conhecimentos em Python e Tkinter, além de compor meu portfólio como desenvolvedor back-end e entusiasta de interfaces gráficas.

Mais atualizações e melhorias poderão ser adicionadas futuramente.
