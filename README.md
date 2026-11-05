# Manual de Operação — Sorteio de Brindes · Grupo Muralha

Página **temporária** com o manual de operação do sorteio (HTML, PDF, imagens e 2 vídeos).

- Manual: https://yeshsharedev.github.io/muralha-sorteio-manual/
- PDF: https://yeshsharedev.github.io/muralha-sorteio-manual/Manual-Operacao-Sorteio-Muralha.pdf

> **Remover em 30/11/2026** (último dia do mês). O código do sistema fica no repositório privado `muralha-sorteio-evento`.

## Como tirar do ar

1. Só desligar o site (o repositório continua visível): Settings → Pages → *Unpublish site*, ou
   `gh api -X DELETE repos/YeshShareDEV/muralha-sorteio-manual/pages`
2. Tirar tudo (recomendado): Settings → General → *Danger Zone* → **Delete this repository**, ou
   `gh repo delete YeshShareDEV/muralha-sorteio-manual --yes` (precisa do escopo `delete_repo`: `gh auth refresh -s delete_repo`).
