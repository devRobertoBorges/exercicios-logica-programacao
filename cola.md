# 📌 Cola do Projeto — Lógica de Programação

Guia rápido para consultar durante o desenvolvimento. Guarde essa cola por perto!

---

## 🔄 Fluxo do projeto (sempre nessa ordem)

```
1. Atualizar a main   → git checkout main && git pull origin main
2. Criar uma branch   → git checkout -b nome-da-tarefa
3. Desenvolver        → escrever o código
4. Fazer commit       → git add . && git commit -m "feat: mensagem"
5. Fazer push         → git push origin nome-da-branch
6. Abrir Pull Request → no GitHub, base: main / compare: sua-branch
7. Revisão            → outro colega revisa o código
8. Merge              → depois de aprovado, integra à main
9. Atualizar a main   → git checkout main && git pull origin main
```

---

## 💻 Comandos essenciais

| Comando | O que faz |
|---|---|
| `git clone URL` | Baixa o projeto do GitHub |
| `git status` | Mostra o estado atual (arquivos modificados, branch atual) |
| `git branch` | Lista as branches (a atual aparece com `*`) |
| `git checkout main` | Vai para a branch main |
| `git checkout -b nome-da-tarefa` | Cria e entra em uma nova branch |
| `git pull origin main` | Baixa as atualizações mais recentes da main |
| `git add .` | Prepara as alterações para o commit |
| `git commit -m "mensagem"` | Registra as alterações |
| `git push origin nome-da-branch` | Envia sua branch para o GitHub |

---

## ✍️ Como escrever uma mensagem de commit

Formato: `tipo: o que foi feito`

Exemplos:
```
git commit -m "feat: adiciona soma de dois numeros"
git commit -m "feat: adiciona verificacao par ou impar"
git commit -m "fix: corrige divisao por zero"
```

---

## 🔀 Abrindo um Pull Request

1. Depois do `push`, vá até o GitHub.
2. Clique em **Compare & pull request**.
3. Confirme: `base: main` ← `compare: sua-branch`.
4. Escreva uma descrição curta do que foi feito.
5. Aguarde a revisão de outro colega antes do merge.

---

## ⚠️ Regras do projeto

1. Nunca alterar a `main` diretamente.
2. Cada tarefa tem sua própria branch.
3. Commits com mensagens claras.
4. Testar o código antes de abrir o PR.
5. Todo PR precisa ser revisado por outro colega.
6. Não copiar código sem entender.
7. Pedir ajuda quando travar.
8. Ajudar quem estiver travado.

---

## 🆘 Travou? Faça nessa ordem

1. `git status` — para entender onde você está.
2. Releia o fluxo acima — qual passo você pulou?
3. Pergunte no grupo. Ninguém precisa resolver sozinho.
