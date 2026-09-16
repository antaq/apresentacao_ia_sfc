# Pendências da apresentação "IA no dia a dia da Fiscalização"

Situação em: **16/09/2026** · Apresentação marcada para **21/09/2026, às 16h20**

> Não há marcador `[CONFIRMAR]`, `[DATA]` ou `[CAPTURA]` em aberto no deck. Os 41 slides
> passaram pela verificação automática de leiaute em 16/09/2026 (ver seção 4). O que
> continua pendente é **fora do HTML**: a publicação da página e duas falas que não estão
> projetadas em tela nenhuma.

---

## 1. Bloqueia a publicação

| Item | Situação |
|---|---|
| **Repositório `antaq/apresentacao_ia_sfc`** | ✅ Criado e publicado na `main` em 16/09/2026. |
| **GitHub Pages** | ⏳ **Falta ligar.** Em *Settings → Pages*, *Source* = **Deploy from a branch** → `main` → `/ (root)`. Não foi possível ligar pela linha de comando: a credencial local não tem o escopo `pages`. **Enquanto o Pages não estiver ligado, o código de leitura óptica do slide 41 abre uma página que não existe.** Confira depois em `https://antaq.github.io/apresentacao_ia_sfc/`. |
| **Código de leitura óptica** | ✅ Regerado em 16/09/2026 e conferido por decodificação: aponta para `https://antaq.github.io/apresentacao_ia_sfc/`. Os arquivos `Imagens/qr-material-apoio.svg` e `.png` já foram substituídos. |

---

## 2. Depende do apresentador, e não está em tela nenhuma

| Slide | O que precisa ser dito em voz alta |
|---|---|
| **40** | A GPF se oferece para montar a **primeira habilidade** junto com a equipe da unidade que pedir. O slide de convite foi suprimido ainda no deck da SAF. |
| **41** | A GPF abre o **conector de Dados Abertos** para quem quiser experimentar. Sem essa frase, a apresentação termina sem próximo passo. |

---

## 3. A conferir antes de projetar

| Onde | O quê |
|---|---|
| **Slide 11** | O guia da CGU é atribuído à **Portaria Normativa CGU nº 193, de 6 de janeiro de 2025**, confirmada por busca. O PDF do repositório da CGU **não abriu** na consulta de 16/09/2026 (redirecionamento seguido de erro). Nenhum outro número de deliberação foi citado no slide, justamente por isso. Conferir a referência antes de projetar. |
| **Slide 15** | Cita o **Ofício Circular nº 3/2023/SFC/ANTAQ** na linha de fonte. Conferir se continua sendo a referência vigente sobre uso de base credenciada. |
| **Slide 32** | O cartão de alerta é atribuído ao **curso de introdução à fiscalização da SFC**. Conferir a atribuição antes de dizer em voz alta de onde vem. |
| **Bloco 4 inteiro** | Todos os números foram lidos do conector de Dados Abertos em **16/09/2026**, sobre uma captura do painel de **18/08/2026**. Se a apresentação escorregar de data, reconferir: a base é atualizada. |
| **Demonstração ao vivo** | O conector `dados-antaq` precisa estar acessível na máquina da apresentação. Se a rede cair, o procedimento é narrar o que está projetado; os quatro slides de demonstração se sustentam sozinhos. |

---

## 4. Verificação de leiaute (16/09/2026)

Os 41 slides foram medidos dentro do navegador, um `<iframe>` por slide em 1920×1080:

- **Estouro de área**: nenhum. Todos os documentos medem exatamente 1920×1080.
- **Ícone inexistente**: nenhum. Todo elemento `<i class="fa-...">` resolve para um glifo do
  Font Awesome 6.4 gratuito.
- **Fonte mínima**: nenhum texto visível abaixo de 17px.
- Os elementos que ultrapassam a moldura são só os decorativos de sangria (`bg-marca`,
  `shape-circle`, `bg-pattern`), recortados por `overflow:hidden` como manda o KIT.

---

## 5. Divergências registradas

1. **Deck de 37 para 41 slides.** A especificação da SAF mandava gastar a folga dos 90
   minutos em demonstração estendida, **não em slides novos**. Aqui a folga foi gasta em
   quatro slides novos de governança (11, 12, 18 e 19), e o bloco 2 passou de 10 para 14
   minutos. A exposição soma 72 minutos, contra os 60 do deck da SAF. Foi decisão
   deliberada, para incorporar as orientações federais publicadas.
2. **Tag `PRIVACIDADE` virou `GOVERNANÇA`.** O bloco 2 deixou de tratar só de privacidade e
   configuração.
3. **Slide 41 não tem tag de bloco.** O KIT da SAF previa `ENCERRAMENTO` com
   `fa-flag-checkered`, mas o slide L11 nunca a teve. O `KIT.md` foi corrigido para
   descrever o que o deck faz, não o que se pretendia.
4. **Travessão longo.** As regras proíbem travessão longo em todo texto do deck. Ele
   sobrevive em um lugar só: a dica de ferramenta dos pontinhos de progresso do
   `index.html`, que é interface de navegação e não texto projetado.
5. **Leiaute L7 (captura de tela) continua sem uso.** Nenhum slide traz captura; o conteúdo
   ocupa a largura cheia, com corpo maior. Decisão herdada do deck da SAF.
6. **Proposta formal.** Continua fora do deck. O slide 11 mostra que a orientação federal
   existe e que a Agência não tem política própria, mas o deck **não pede decisão por
   escrito em tela nenhuma**. Se essa mensagem importar nesta plateia, ela depende
   inteiramente da fala.
