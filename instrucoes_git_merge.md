# Instruções para fazer o merge de uma branch no Git

Este arquivo mostra como unir uma branch de funcionalidade à branch principal (`main`).

## Passos para realizar o merge
1. Certifique-se de estar na branch `main`:
   ```bash
   git checkout main
   ```
2. Atualize a branch `main` com as últimas alterações do repositório remoto:
   ```bash
   git pull origin main
   ```
3. Faça o merge da branch de funcionalidade (exemplo: `nova-funcionalidade`):
   ```bash
   git merge nova-funcionalidade
   ```
4. Resolva possíveis conflitos, se houver.
5. Envie as alterações mescladas para o GitHub:
   ```bash
   git push origin main
   ```

## Dica
- Para mesclar usando Pull Request, faça o processo pelo GitHub, onde outros colaboradores podem revisar antes de unir as mudanças.
