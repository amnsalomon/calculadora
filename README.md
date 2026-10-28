# IA & Valor — calculadora de capacidade × custo

Aplicação **mobile-first**, sem frameworks, cadastro, cookies ou backend, destinada à publicação no GitHub Pages.

## Recursos
- Comparação interativa de 24 modelos de IA, com índice de inteligência e dois modos de custo.
- Simulador de gastos mensais com API (chamadas × tokens de entrada/saída × preços por milhão).
- Filtro por capacidade mínima, pesquisa, ordenação e fronteira de eficiência.
- Comparação de até três modelos e compartilhamento do cenário por URL.
- Interface acessível por toque, teclado e leitores de tela, sem dependências externas.

## Publicar no GitHub Pages
1. No repositório, abra **Settings → Pages**.
2. Em **Build and deployment**, escolha **Deploy from a branch**.
3. Selecione **main**, pasta **/(root)**, e clique em **Save**.
4. Quando o GitHub concluir a publicação, a URL prevista é https://amnsalomon.github.io/calculadora/.

> O arquivo `index.html` já está na raiz da branch main. A existência do commit não significa que Pages esteja habilitado.

## Base de dados e limites
Comparação histórica baseada em informações atribuídas ao **Artificial Analysis Intelligence Index v4.3.2**, instantâneo de **15/10/2026**, e tarifas de API da mesma referência. O índice v5 foi divulgado em **27/10/2026**, mas métricas entre versões não devem ser diretamente comparadas.

Fonte de referência: https://artificialanalysis.ai/models

A simulação de API é uma aproximação: o volume real de tokens (incluindo raciocínio), cache, contexto longo, ferramentas e regras específicas de tarifação podem mudar o total. O custo por tarefa do benchmark não corresponde ao preço real de uma tarefa comercial. **Verifique preços e desempenho nas fontes originais antes de decisões financeiras.**

## Uso local
Abra `index.html` em um navegador moderno. Todo o processamento ocorre localmente; não é preciso instalação nem build.
