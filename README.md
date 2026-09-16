# IA no dia a dia da Fiscalização

Encontro interno da **Superintendência de Fiscalização e Coordenação das Unidades
Regionais (SFC)** da ANTAQ, com as gerências da sede e as Gerências e Unidades Regionais.

Apresentação conjunta de duas gerências da SFC:

- **Pedro Henrique Soares** - Gerência de Planejamento e Inteligência da Fiscalização (GPF)
- **Fábio Queiroz Fonseca** - Gerência de Recursos e de Apoio Técnico (GRAT)

O slide 25 apresenta o **Roteiro para Proteção de Dados Sensíveis no Uso de IA**, da
Gerência de Tecnologia e Gestão da Informação (GTGI), cujo titular é **Alexandre Ferreira de
Alencar**. O roteiro está em minuta, em validação institucional.

🔗 **Página publicada:** https://antaq.github.io/apresentacao_ia_sfc/

📦 **Repositório:** https://github.com/antaq/apresentacao_ia_sfc

> Este deck é uma adaptação do material apresentado à SAF em 5 de agosto de 2026
> (`antaq.github.io/apresentacao_ia_saf`). O bloco 2 foi reescrito a partir das
> orientações federais publicadas sobre IA generativa.
>
> **O bloco de conector e dados abertos saiu daqui.** Ele virou apresentação própria,
> *"Utilização de Dados Abertos da ANTAQ para Análise Técnica"*, no dia seguinte
> (22/09/2026, às 10h20): `antaq.github.io/apresentacao_dados_abertos`. Os dois materiais
> são encadeados, e o deck de dados abertos abre com uma recapitulação deste.

## Sobre

- **Subtítulo:** o que dá para fazer hoje, o que não pode ser feito nunca, e a decisão que está na mesa
- **Duração prevista:** 70 minutos (56 de exposição, conforme os chips de tempo das divisórias, e o restante em demonstração ao vivo e perguntas)
- **Plateia:** toda a SFC - gerências da sede (GCOR, GPF, GRAT) e Gerências e Unidades Regionais
- **Data:** 21 de setembro de 2026, às 16h20
- **Formato:** 32 slides em sequência única, em HTML 1920×1080

## Como usar

Abra o [`index.html`](index.html). Cada slide é um arquivo `slide-NN.html` autossuficiente,
carregado em um `<iframe>` e escalado para a tela.

| Tecla | Ação |
|---|---|
| `→` `espaço` `PageDown` | Próximo slide |
| `←` `PageUp` | Slide anterior |
| `Home` / `End` | Primeiro / último slide |
| `F` | Tela cheia |
| `N` | Abre e fecha as **notas do apresentador** |

As notas do apresentador ficam em bloco oculto dentro de cada slide e **nunca aparecem na
projeção**: só no painel lateral do `index.html`. A barra inferior mostra o progresso por
bloco temático.

Para servir localmente:

```bash
python3 -m http.server 8130
```

## Blocos

| Slides | Bloco | Tempo |
|---|---|---|
| 1 a 3 | Abertura | 3 min |
| 4 a 9 | Bloco 1 · Como funciona e onde falha | 10 min |
| 10 a 19 | Bloco 2 · O que já está escrito, e o que nunca entra | 14 min |
| 20 a 28 | Bloco 3 · Projeto, instruções e memória | 22 min |
| 29 a 31 | Bloco 4 · Habilidades e artefatos | 7 min |
| 32 | Encerramento | — |

## Arquivos

| Arquivo | Conteúdo |
|---|---|
| [`index.html`](index.html) | Navegador dos slides (escala, teclado, notas, progresso) |
| `slide-01.html` … `slide-32.html` | Os 32 slides |
| [`KIT.md`](KIT.md) | Sistema visual (paleta, tipografia, componentes, mapa dos slides) |
| `Imagens/og-capa.jpg` | Cartão 1200x630 que aparece ao compartilhar o endereço |
| `Imagens/og-fonte.html` | Página que gera o cartão. Não faz parte da apresentação |
| [`spec-slides-ia-sfc.md`](spec-slides-ia-sfc.md) | Especificação de conteúdo que originou o deck |
| [`notas-apresentador.md`](notas-apresentador.md) | Roteiro falado por slide, para impressão |
| [`PENDENCIAS.md`](PENDENCIAS.md) | O que foi resolvido, o que sobrou e as divergências registradas |

## Antes de apresentar

Leia o [`PENDENCIAS.md`](PENDENCIAS.md). Há **duas pontes verbais obrigatórias** (slides 31
e 32) que não estão projetadas em tela nenhuma.

## Publicação (GitHub Pages)

A página é servida pela branch `main`, na raiz do repositório, no mesmo padrão das demais
apresentações da Gerência: em **Settings → Pages**, *Source* é **Deploy from a branch** →
`main` → `/ (root)`. O arquivo `.nojekyll` impede que o Jekyll ignore arquivos e pastas
iniciados por `_`.

A partir daí, todo `push` na `main` republica a página automaticamente.

### Cartão de compartilhamento

O `index.html` traz as metaetiquetas Open Graph, e por isso o endereço colado no WhatsApp ou
no Teams abre com o cartão [`Imagens/og-capa.jpg`](https://antaq.github.io/apresentacao_ia_sfc/Imagens/og-capa.jpg) em vez do endereço cru.
Para trocar a arte, use `Imagens/og-fonte.html` e siga a seção 11 do [`KIT.md`](KIT.md).
O arquivo precisa continuar com **1200x630** e **abaixo de 300 KB**, senão a prévia não
aparece. A prévia fica em cache no aplicativo por alguns dias depois de publicada.
