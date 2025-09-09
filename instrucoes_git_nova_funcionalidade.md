# Instruções para usar o Git (branch nova-funcionalidade)

Este arquivo serve como exemplo de instruções para trabalhar em uma nova funcionalidade usando branches no Git.

## Passos para criar e trabalhar em uma branch
1. Crie uma nova branch para sua funcionalidade:
   ```bash
   git checkout -b nova-funcionalidade
   ```
2. Faça alterações nos arquivos do projeto.
3. Adicione e faça commit das alterações:
   ```bash
   git add .
   git commit -m "Adiciona nova funcionalidade"
   ```
4. Envie a branch para o GitHub:
   ```bash
   git push origin nova-funcionalidade
   ```
5. Crie um Pull Request no GitHub para revisar e mesclar as mudanças na branch main.

## Comandos úteis
- `git branch` — Lista as branches disponíveis
- `git checkout nome-da-branch` — Troca de branch
- `git merge nome-da-branch` — Mescla uma branch na atual
- `git pull` — Atualiza o projeto local
- `git push` — Envia alterações para o GitHub
