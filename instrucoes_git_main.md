# Instruções para usar o Git (branch main)

Este arquivo serve como exemplo de instruções básicas para começar a usar o Git em seu projeto.

## Passos iniciais
1. Instale o Git em sua máquina.
2. Configure seu nome de usuário e e-mail:
   ```bash
   git config --global user.name "Seu Nome"
   git config --global user.email "seuemail@exemplo.com"
   ```
3. Crie uma pasta para seu projeto e inicialize o repositório:
   ```bash
   mkdir meu-projeto
   cd meu-projeto
   git init
   ```
4. Adicione arquivos e faça o primeiro commit:
   ```bash
   git add .
   git commit -m "Commit inicial"
   ```
5. Crie um repositório no GitHub e conecte:
   ```bash
   git remote add origin URL_DO_REPOSITORIO.git
   git push -u origin main
   ```

## Comandos úteis
- `git status` — Verifica o estado dos arquivos
- `git log` — Mostra o histórico de commits
- `git pull` — Atualiza o projeto local com o remoto
- `git push` — Envia alterações para o GitHub
