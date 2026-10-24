# Guardião Gamer — alpha 0.1

Controle parental para jogos eletrônicos, no celular e no computador. Protótipo funcional de demonstração do Projeto A3 (UC Exploração Digital e Fundamentos Tecnológicos).

**Abrir e instalar: https://alexandrelott.github.io/guardiao-gamer-alpha/**

## Como instalar

* **Android (Chrome):** abra o link, toque no menu ⋮ e em *Instalar app* (ou *Adicionar à tela inicial*).
* **iPhone e iPad (Safari):** abra o link, toque em *Compartilhar* e em *Adicionar à Tela de Início*.
* **PC (Chrome ou Edge):** abra o link e clique no ícone de instalar no fim da barra de endereço (ou menu ⋮ → *Salvar e compartilhar → Instalar*).
* **Sem internet (PC):** baixe [`downloads/Guardiao-Gamer-alpha-offline.zip`](downloads/Guardiao-Gamer-alpha-offline.zip), extraia a pasta inteira e dê dois cliques em `Abrir-no-PC.bat`.
* **Arquivo único (reserva):** [`downloads/Guardiao-Gamer-alpha.html`](downloads/Guardiao-Gamer-alpha.html) abre direto no navegador.

Depois da primeira abertura com internet, o app funciona também offline. PIN do painel do responsável na demonstração: **1234**.

## O que é real e o que é simulado

O tempo de jogo é simulado pelo botão "Simular 10 min jogando (demo)", o bloqueio acontece dentro do próprio app (ele não bloqueia jogos de verdade no Android ou no Windows) e não há sincronização entre o celular da criança e o painel do responsável. Os dados ficam salvos só no aparelho.

## O que o alpha mostra

Limite de tempo por jogo, tela de bloqueio ao estourar o limite, painel do responsável protegido por PIN, relatório semanal com gráfico e cadastro de novos jogos.

## Arquivos

| Arquivo | Para quê |
| --- | --- |
| `index.html` | O app inteiro (HTML, CSS e JavaScript) |
| `manifest.webmanifest` e `icons/` | Tornam o app instalável |
| `sw.js` | Guarda o app no aparelho para funcionar sem internet |
| `Abrir-no-PC.bat` | Atalho do Windows que abre o app em janela própria |
| `downloads/` | Kit offline e arquivo único |

Documentação completa do projeto: [diário técnico no GitBook](https://bet-blocker.gitbook.io/bet-blocker-docs/).
