# 🧠 Projeto de Lógica de Programação

Projeto colaborativo criado por 6 alunos de Sistemas de Informação para praticar **lógica de programação, Java, Git e GitHub**.

A ideia é começar com códigos muito simples e, conforme o grupo evoluir, adicionar novos desafios e funcionalidades.

> **Não é necessário ter experiência com Git ou programação para participar. A ideia é aprender juntos.**

---

## 🎯 Objetivo

- Praticar lógica de programação.
- Aprender Java.
- Aprender Git e GitHub.
- Aprender a trabalhar em equipe.
- Compartilhar conhecimento.
- Evoluir gradualmente para exercícios mais complexos.

---

## 👥 Participantes

Inicialmente, cada participante ficará responsável por uma funcionalidade simples.

| Membro | Responsabilidade |
|---|---|
| Membro 1 | Soma |
| Membro 2 | Subtração |
| Membro 3 | Multiplicação |
| Membro 4 | Divisão |
| Membro 5 | Par ou ímpar |
| Membro 6 | Média |

> Os nomes dos participantes serão adicionados posteriormente.

---

## 🧩 Primeiras tarefas

### 👤 Membro 1 — Soma

Receber dois números e retornar a soma.

**Exemplo:**

```text
Entrada:
10
5

Saída:
15
```

---

### 👤 Membro 2 — Subtração

Receber dois números e retornar a subtração.

**Exemplo:**

```text
Entrada:
10
5

Saída:
5
```

---

### 👤 Membro 3 — Multiplicação

Receber dois números e retornar a multiplicação.

**Exemplo:**

```text
Entrada:
10
5

Saída:
50
```

---

### 👤 Membro 4 — Divisão

Receber dois números e retornar a divisão.

**Exemplo:**

```text
Entrada:
10
5

Saída:
2
```

O código também deve considerar a possibilidade de divisão por zero.

---

### 👤 Membro 5 — Par ou ímpar

Receber um número e informar se ele é par ou ímpar.

**Exemplo:**

```text
Entrada:
10

Saída:
Par
```

---

### 👤 Membro 6 — Média

Receber dois números e calcular a média.

**Exemplo:**

```text
Entrada:
10
6

Saída:
8
```

---

# 🌎 Git e GitHub

## O que é Git?

**Git** é uma ferramenta utilizada para controlar as alterações feitas em um projeto.

Ele permite:

- acompanhar alterações no código;
- saber quem fez cada alteração;
- voltar para versões anteriores;
- trabalhar em diferentes funcionalidades;
- trabalhar em equipe.

## O que é GitHub?

**GitHub** é uma plataforma onde podemos armazenar nossos projetos Git na internet e trabalhar colaborativamente.

---

# 🌿 O que é uma Branch?

Uma **branch** é uma cópia de trabalho do projeto onde podemos desenvolver uma funcionalidade sem alterar diretamente a `main`.

Exemplo:

```text
main
 ├── soma
 ├── subtracao
 ├── multiplicacao
 ├── divisao
 ├── par-impar
 └── media
```

Cada participante trabalha na sua própria branch.

---

# 📌 O que é Commit?

Um **commit** é um registro das alterações feitas no projeto.

Exemplo:

```bash
git commit -m "feat: adiciona soma de dois numeros"
```

A mensagem deve explicar o que foi alterado.

---

# 📤 O que é Push?

O `push` envia os commits da sua máquina para o GitHub.

```bash
git push origin soma
```

---

# 📥 O que é Pull?

O `pull` baixa as alterações mais recentes do GitHub para o seu computador.

```bash
git pull origin main
```

---

# 🔀 O que é Pull Request?

Um **Pull Request (PR)** é um pedido para adicionar as alterações da sua branch à `main`.

Exemplo:

```text
soma
  ↓
Pull Request
  ↓
main
```

Antes do código entrar na `main`, outro participante deverá revisar o código.

Durante a revisão podemos:

- encontrar erros;
- fazer perguntas;
- sugerir melhorias;
- aprender com o código do colega.

---

# 🔗 O que é Merge?

**Merge** significa juntar as alterações de uma branch com outra.

Exemplo:

```text
soma
  ↓
Merge
  ↓
main
```

Depois do Merge, a funcionalidade passa a fazer parte da `main`.

---

# 🔄 Fluxo do projeto

Todos deverão seguir este fluxo:

```text
1. Atualizar a main
        ↓
2. Criar uma branch
        ↓
3. Desenvolver
        ↓
4. Fazer commit
        ↓
5. Fazer push
        ↓
6. Abrir Pull Request
        ↓
7. Revisão
        ↓
8. Merge
        ↓
9. Atualizar a main
```

---

# 💻 Comandos Git

## 1. Clonar o projeto

Baixa o projeto do GitHub para o computador.

```bash
git clone URL_DO_REPOSITORIO
```

Depois entre na pasta:

```bash
cd exercicios-logica-programacao
```

---

## 2. Verificar o estado do projeto

```bash
git status
```

Mostra:

- branch atual;
- arquivos modificados;
- arquivos novos;
- alterações pendentes.

---

## 3. Ver as branches

```bash
git branch
```

A branch atual aparece com `*`.

Exemplo:

```text
  main
* soma
```

---

## 4. Entrar na main

```bash
git checkout main
```

---

## 5. Atualizar a main

Antes de começar uma nova tarefa:

```bash
git pull origin main
```

---

## 6. Criar uma branch

```bash
git checkout -b nome-da-tarefa
```

Exemplo:

```bash
git checkout -b soma
```

---

## 7. Fazer o código

Agora desenvolva a funcionalidade da sua tarefa.

---

## 8. Verificar alterações

```bash
git status
```

---

## 9. Adicionar alterações

```bash
git add .
```

O `git add` prepara as alterações para o próximo commit.

---

## 10. Criar um commit

```bash
git commit -m "feat: adiciona soma de dois numeros"
```

Exemplos:

```bash
git commit -m "feat: adiciona subtracao"
```

```bash
git commit -m "feat: adiciona multiplicacao"
```

```bash
git commit -m "feat: adiciona verificacao par ou impar"
```

---

## 11. Enviar para o GitHub

```bash
git push origin nome-da-branch
```

Exemplo:

```bash
git push origin soma
```

---

# 🔀 Abrindo um Pull Request

Depois do `push`, entre no GitHub.

Crie um Pull Request:

```text
Base: main
Compare: soma
```

Ou seja:

```text
soma → main
```

Explique brevemente o que foi desenvolvido.

Outro participante deverá revisar o código.

Após a aprovação, o Pull Request poderá ser integrado à `main`.

---

# 🔄 Depois do Merge

Depois que o Pull Request for integrado à `main`, atualize seu projeto:

```bash
git checkout main
```

Depois:

```bash
git pull origin main
```

Agora você possui a versão mais atualizada do projeto.

---

# 🛠️ Comandos principais

| Comando | Função |
|---|---|
| `git clone` | Baixa o projeto do GitHub |
| `git status` | Mostra o estado do projeto |
| `git branch` | Mostra as branches |
| `git checkout` | Troca de branch |
| `git checkout -b` | Cria uma branch |
| `git pull` | Baixa alterações |
| `git add` | Prepara alterações |
| `git commit` | Registra alterações |
| `git push` | Envia alterações para o GitHub |

---

# ⚠️ Regras do projeto

1. Não alterar diretamente a `main`.
2. Cada tarefa deve possuir sua própria branch.
3. Fazer commits claros.
4. Testar o código antes do Pull Request.
5. Todo Pull Request deve ser revisado por outro participante.
6. Não copiar código sem entender.
7. Pedir ajuda quando tiver dificuldade.
8. Ajudar os outros participantes.
9. Manter o projeto simples no início.

---

# 📚 Primeira atividade

Antes de cada participante começar sua tarefa, todos irão fazer um pequeno exercício juntos.

## Hello World

O grupo irá praticar:

```text
Clone
  ↓
Branch
  ↓
Código
  ↓
Commit
  ↓
Push
  ↓
Pull Request
  ↓
Review
  ↓
Merge
  ↓
Pull
```

Depois que todos entenderem esse fluxo, cada participante poderá começar sua própria tarefa.

---

# 🚀 Evolução do projeto

Começaremos com:

```text
Soma
Subtração
Multiplicação
Divisão
Par ou ímpar
Média
```

Depois adicionaremos novas funcionalidades:

```text
        6 funções iniciais
                ↓
        novos exercícios
                ↓
       novas dificuldades
                ↓
      funções mais complexas
                ↓
        pequenos projetos
```

A dificuldade será aumentada conforme o conhecimento do grupo.

---

# 🤝 Aprender juntos

Este projeto foi criado para alunos que estão aprendendo.

Não importa se você nunca programou.

Não importa se você nunca utilizou Git.

Não importa se você cometer erros.

**Pergunte, teste, pesquise e ajude seus colegas.**

> **Começamos com uma soma e, juntos, vamos evoluir para programas cada vez maiores.**
