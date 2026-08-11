# Prompt pronto — cole no Claude pra deixar o portfólio com a sua cara

> Abra esta pasta no Claude e cole o texto abaixo.

---

Você é um desenvolvedor e designer. Nesta pasta há uma **página de vendas (portfólio) pronta** — um `index.html` com CSS e JS embutidos — que apresenta um serviço de "sites de pedido no WhatsApp" e mostra 17 exemplos funcionando (pasta `exemplos/`).

Sua tarefa é **personalizar a página com a minha marca**, sem quebrar a estrutura nem a copy.

**Antes de mexer, me pergunte:**
1. O nome da minha marca / agência.
2. O meu WhatsApp (com DDD) — é onde chegam os pedidos de orçamento.
3. Se eu tenho domínio próprio (e qual).
4. Se eu quero manter as cores atuais (vermelho/dourado) ou usar outra cor principal.

**Depois, faça:**
- Troque **todos** os `{{SUA_MARCA}}` pelo nome da minha marca.
- Troque **todos** os `SEU_WHATSAPP` pelo meu número (formato `55` + DDD + número, só dígitos).
- Se eu tiver domínio, troque `SEU-DOMINIO.com.br` no `canonical` e nas tags `og:`.
- Se eu pedir outra cor, ajuste as variáveis no bloco `:root` do CSS (mantendo bom contraste e legibilidade).
- **Gere um `og.jpg`** (1200×630) com o nome da minha marca e a frase principal, e salve na raiz da pasta — é a imagem que aparece no preview quando eu mando o link no WhatsApp.

**Regras:**
- **Não reescreva a copy** dos blocos (problema, causa, solução, benefícios, oferta, FAQ) — ela já foi feita pra converter. Mexa só na marca, número, cor e imagem.
- **Não mude** os links dos exemplos (`exemplos/<nicho>/`) — eles apontam pros demos locais que já vêm na pasta.
- Ao final, me diga como publicar de graça (Vercel ou Netlify) arrastando a pasta.
