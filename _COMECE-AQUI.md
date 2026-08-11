# KIT — Portfólio / página de vendas (white-label)

Esta é a sua **página de vendas pronta** pra fechar clientes de site de pedidos. Ela já vem com os **17 exemplos funcionando embutidos** (pasta `exemplos/`) — o visitante clica em "Ver funcionando" e abre um demo de verdade, tudo local, **sem nenhum link pra site de terceiros**.

Use esta página pra:
- Mandar pro dono de comércio ver seu trabalho antes de fechar.
- Ter um link fixo de portfólio no seu Instagram / bio.
- Provar o que você entrega (a "parede de exemplos" convence sozinha).

## O que trocar pra deixar com a sua cara

Tudo está marcado com **placeholder** pra achar fácil (abra o `index.html`):

- **`{{SUA_MARCA}}`** → o nome da sua marca/agência. Aparece no topo, no título e no rodapé.
- **`SEU_WHATSAPP`** → o seu número, formato `55` + DDD + número, só dígitos (ex: `5551999998888`). É pra onde vão os pedidos de orçamento.
- **`SEU-DOMINIO.com.br`** → seu domínio (no `canonical` e nas tags `og:`), se tiver. Se não tiver, pode deixar.
- **Cores** (opcional) → o vermelho/dourado está no bloco `:root` do CSS; troque se quiser a sua identidade.
- **`og.jpg`** (imagem de preview do link) → **não vem incluso** de propósito (era da marca original). Gere a sua com o seu nome pra o link ficar bonito no WhatsApp. O Claude faz isso — veja o `PROMPT-PARA-O-CLAUDE.md`.

## Os exemplos embutidos

- Ficam em `exemplos/<nicho>/` e já estão **neutralizados** (número trocado por `SEU_WHATSAPP`).
- Servem só de **demonstração** — o visitante testa o fluxo. Você não precisa mexer neles aqui.
- Quando fechar um cliente, use o **outro kit** ("Sites Prontos") pra montar e entregar o site dele de verdade.

## Como publicar

Arraste a pasta inteira pro [vercel.com](https://vercel.com) ou [netlify.com/drop](https://app.netlify.com/drop). Fica no ar de graça. Aí é só divulgar o link.

## Importante

A copy desta página segue o Método Aliados (problema → causa → solução → prova → oferta). **Não precisa reescrever** — só troque marca, número e cor. O texto já foi pensado pra converter.
