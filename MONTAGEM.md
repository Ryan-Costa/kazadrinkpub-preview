# KAZA drink&pub · setup inicial no Waveform

Este site (`index.html`) foi feito só com o que o Waveform já tem: os blocos do editor, o tema da tela **Aparência** e o CSS dos sites (`waveform/site.css`, cópia de `src/components/site/site.css`). Montando como abaixo, o resultado no Waveform é o mesmo da prévia.

Fontes das informações: o site atual (kazadrinkpub.com: home, happy hour, drinks, petiscos, cervejas, bebidas) e o Instagram @kazadrinkpub. O que não foi encontrado está marcado **(confirmar)**.

## 1. Cliente

No admin, **Novo cliente**:

- Nome: `KAZA drink&pub`
- Endereço: `kazadrinkpub`
- Responsável: quem cuida do KAZA (e-mail do contato: kazapubfortaleza@gmail.com), com convite por e-mail
- Domínio próprio depois: `kazadrinkpub.com` já é deles

## 2. Aparência

**Cores** (azul do logo "K" e amarelo dos destaques do Instagram)

| Campo | Cor | Uso |
| --- | --- | --- |
| Fundo | `#0e1424` | azul-noite |
| Superfície | `#17213b` | cartões |
| Texto | `#fff8ec` | |
| Texto secundário | `#bac3d8` | |
| Principal | `#3b8bff` | azul do logo (palavras em destaque) |
| Destaque | `#ffc21a` | amarelo (botões e sobretítulos) |
| Texto dos botões | automático | |

As cores exatas do site atual não puderam ser lidas **(confirmar com o cliente)**.

**Tipografia**

| Local | Fonte | Tamanho |
| --- | --- | --- |
| Título principal | Unbounded | 130% |
| Títulos das seções | Unbounded | 90% |
| Sobretítulos | Space Grotesk | 110% |
| Menu | Space Grotesk | 110% |
| Texto | DM Sans | 105% |
| Botões | Space Grotesk | 105% |

**Arredondamento:** 14 px.

**Identidade:** enviar o logo (círculo azul com o "K" branco; o site atual tem as versões `logo-branca` e `logo-kaza-amarelada`) como logo e favicon.

## 3. Mídia

Todas as fotos da prévia são de referência (créditos no rodapé) e **nenhuma é do KAZA**. Pedir ao cliente:

| Uso | Na prévia | O ideal |
| --- | --- | --- |
| Fundo da abertura | balcão de bar com neon | a pista ou o balcão do KAZA à noite |
| Foto do "Sobre" | um casarão histórico de Fortaleza | a fachada do casarão do KAZA |
| Vitrine do happy hour (2 fotos) | caipirinha, brinde | drinks do happy hour |
| Galeria (5 fotos) | brinde, pista, mural, caipirinha, balcão | fotos das noites (o Instagram tem muitas: murais coloridos, aniversários, noites temáticas) |

## 4. Eventos

O site atual tem o título "Programação da Semana" sem eventos, e a agenda fica nos destaques do Instagram. A seção **Agenda** foi montada sem eventos: mostra o texto de "nada por enquanto" até o KAZA cadastrar as noites em **Eventos**.

## 5. Página inicial: seções, nesta ordem

WhatsApp: `+55 85 92004-9048`. Mapa: `https://www.google.com/maps/search/?api=1&query=KAZA%20drink%26pub%2C%20Rua%20Monsenhor%20Salazar%2C%201306%2C%20S%C3%A3o%20Jo%C3%A3o%20do%20Tauape%2C%20Fortaleza%20-%20CE`

1. **Abertura** (hero)
   - Fundo: foto, foco no centro. Alinhamento: esquerda. Sombra: forte. Dica de rolagem: ligada.
   - Sobretítulo `Drinks • música • encontro`; título em duas linhas: `A KAZA` e `é *nossa!*`
   - Subtítulo: `Uma casa de encontros, bons drinks e música boa, num casarão histórico no São João do Tauape, em Fortaleza.`
   - Botões: `Reserve pelo WhatsApp` → `https://wa.me/5585920049048?text=Oi! Quero fazer uma reserva no KAZA.` (principal); `Ver o cardápio` → `#cardapio` (contorno)
2. **Sobre** (about), âncora `a-kaza`, menu `A KAZA`, foto à direita
   - Sobretítulo `A KAZA`, título `Um pub que vai *além do bar*`, os dois parágrafos da prévia
   - Botão `Como chegar` → mapa
3. **Texto** (rich_text), âncora `horarios`, menu `Horários`, centralizado
   - Sobretítulo `Funcionamento`, título `Quando a KAZA *abre*`
   - Texto: `Quinta: das 19h à 01h` / `Sexta e sábado: das 20h às 03h` / (linha em branco) / `Happy hour: quinta e sexta, das 20h às 23h.`
   - Domingo a quarta não aparecem no site atual **(confirmar se fecha)**
4. **Vitrine** (showcase), âncora `happy-hour`, menu `Happy hour`, fotos à direita, 5 s
   - Sobretítulo `Quinta e sexta · 20h às 23h`, título `Hora Boa do *KAZA*`
   - Texto: o da prévia (preços tirados da página de happy hour)
   - Botão `Ver o happy hour` → `https://kazadrinkpub.com/happyhour/`
5. **Mídias** (media), âncora `cardapio`, menu `Cardápio`, sem vídeo em destaque, cartões lado a lado
   - Sobretítulo `Cardápio`, título `Drinks, petiscos e *cerveja gelada*`
   - Cartões simples (ícone Link): `Drinks *autorais*` → /drinks/; `Caipirinhas *Fratelli*` → /drinks/; `Petiscaria` → /petiscos/ (subtítulos da prévia)
   - Cartão com lista (ícone Link), `Cardápio *completo*` / `Preços e opções de cada categoria`, links: Drinkeria, Petiscaria, Cervejas, Bebidas, Combos, Happy hour → as páginas do site atual
   - Quando o site atual sair do ar, o cardápio pode virar uma página "Cardápio" no Waveform, com uma seção de Texto por categoria
6. **Agenda** (agenda), âncora `agenda`, menu `Agenda`
   - Sobretítulo `Programação da semana`, título `O que rola na *KAZA*`
   - Texto quando não há eventos: `A programação da semana sai no nosso Instagram, nos destaques "Agenda". Em breve, direto aqui.`
7. **Faixa de chamada** (cta_banner), âncora `aniversario`, menu `Aniversário`
   - Título `Seu aniversário merece ser comemorado *no KAZA*`
   - Texto: `Entrada VIP com acompanhante, drink de boas-vindas e lista com 50% na entrada para os convidados até as 21h.`
   - Botão `Reservar aniversário` → `https://wa.me/5585920049048?text=Oi! Quero comemorar meu aniversário no KAZA.`
8. **Galeria** (gallery), âncora `fotos`, layout **destaque**: sobretítulo `Na KAZA`, título `Noites que ficam na *memória*`, 5 fotos com legenda
9. **Divisor** (divider): onda, 104 px
10. **Contato** (contact), âncora `contato`, menu `Contato`
    - Sobretítulo `Reservas e contato`, título `Vem pra *KAZA*`, texto `Reservas, aniversários e ativação de marcas: fale com a gente pelo WhatsApp.`
    - Itens: WhatsApp `5585920049048` (texto exibido `(85) 92004-9048`); Link, rótulo `Endereço`, mapa (texto `Rua Monsenhor Salazar, 1306 · São João do Tauape`); E-mail `kazapubfortaleza@gmail.com`; Instagram `kazadrinkpub`
    - Botão `Reserve pelo WhatsApp` → WhatsApp
11. **Redes sociais** (social_links), centralizado, título `A KAZA é nossa!`: Instagram, Facebook (`https://www.facebook.com/kazadrinkpub`), X (`https://x.com/kazadrinkpub`), WhatsApp
12. **Rodapé** (footer): texto `Rua Monsenhor Salazar, 1306 · São João do Tauape · Fortaleza, CE`, links `Cardápio` (#cardapio), `Happy hour` (#happy-hour), `Reservas` (WhatsApp), voltar ao topo ligado

Depois: **Publicar**.

## Diferenças entre a prévia e o Waveform

- Fontes: na prévia vêm do Google Fonts; no Waveform, do próprio servidor (mesmas famílias).
- A linha "Fotos de referência" no fim da prévia não existe no Waveform: some quando as fotos forem trocadas.
- Os preços na página do site atual aparecem em dois valores (com "$" e com "R$"); a prévia usa o valor em R$ **(confirmar)**.
