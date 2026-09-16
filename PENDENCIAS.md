# Pendências da apresentação "IA no dia a dia da Fiscalização"

Situação em: **16/09/2026** · Apresentação marcada para **21/09/2026, às 16h20**

> Não há marcador `[CONFIRMAR]`, `[DATA]` ou `[CAPTURA]` em aberto no deck. Os 31 slides
> passaram pela verificação automática de leiaute em 16/09/2026 (ver seção 4). A página já
> está publicada em **https://antaq.github.io/apresentacao_ia_sfc/**, e o código de leitura
> óptica do slide 31 foi conferido contra ela. O que continua pendente é **fora do HTML**:
> duas falas que não estão projetadas em tela nenhuma e duas atribuições a conferir.
>
> **Mudança de escopo em 16/09/2026:** o antigo bloco 4 (conector e dados abertos, ex-slides
> 28 a 37) saiu deste deck e virou apresentação própria para 22/09/2026, em
> `../Dados-Abertos-Analise-Tecnica/`. O deck passou de 41 para 31 slides e de 72 para 54
> minutos de exposição. **Confirmar com quem reservou a sala se o horário de 21/09 continua
> sendo de 90 minutos**: se continuar, sobra tempo, e o melhor destino dele é demonstração
> ao vivo do bloco 3.

---

## 1. Publicação

| Item | Situação |
|---|---|
| **Repositório `antaq/apresentacao_ia_sfc`** | ✅ Criado e publicado na `main` em 16/09/2026. |
| **GitHub Pages** | ✅ Ligado em *Deploy from a branch* → `main` → `/ (root)`. A primeira compilação não disparou sozinha ao ligar o Pages e precisou ser pedida à mão; se isso se repetir num próximo deck, o caminho é `gh api -X POST repos/<org>/<repo>/pages/builds`. Página no ar e conferida em 16/09/2026. |
| **Código de leitura óptica** | ✅ Regerado em 16/09/2026 e conferido por decodificação: aponta para `https://antaq.github.io/apresentacao_ia_sfc/`. Os arquivos `Imagens/qr-material-apoio.svg` e `.png` já foram substituídos. |

---

## 2. Depende do apresentador, e não está em tela nenhuma

| Slide | O que precisa ser dito em voz alta |
|---|---|
| **30** | A GPF e a GRAT se oferecem para montar a **primeira habilidade** junto com a equipe da unidade que pedir. O slide de convite foi suprimido ainda no deck da SAF. |
| **31** | O convite para a apresentação do dia seguinte, sobre o **conector de Dados Abertos**. Sem essa frase, a apresentação termina sem próximo passo, e o encadeamento entre os dois dias se perde. |

---

## 3. A conferir antes de projetar

| Onde | O quê |
|---|---|
| **Slide 11** | O guia da CGU é atribuído à **Portaria Normativa CGU nº 193, de 6 de janeiro de 2025**, confirmada por busca. O PDF do repositório da CGU **não abriu** na consulta de 16/09/2026 (redirecionamento seguido de erro). Nenhum outro número de deliberação foi citado no slide, justamente por isso. Conferir a referência antes de projetar. |
| **Slide 15** | Cita o **Ofício Circular nº 3/2023/SFC/ANTAQ** na linha de fonte. Conferir se continua sendo a referência vigente sobre uso de base credenciada. |
| **Demonstração ao vivo** | Este deck não tem mais slide de demonstração com número. Se houver demonstração ao vivo, ela é do bloco 3 (criar um projeto), e não depende de rede além do acesso à ferramenta. |

---

## 4. Verificação de leiaute (16/09/2026)

Os 31 slides foram medidos dentro do navegador, um `<iframe>` por slide em 1920×1080:

- **Estouro de área**: nenhum. Todos os documentos medem exatamente 1920×1080.
- **Ícone inexistente**: nenhum. Todo elemento `<i class="fa-...">` resolve para um glifo do
  Font Awesome 6.4 gratuito.
- **Fonte mínima**: nenhum texto visível abaixo de 17px.
- Os elementos que ultrapassam a moldura são só os decorativos de sangria (`bg-marca`,
  `shape-circle`, `bg-pattern`), recortados por `overflow:hidden` como manda o KIT.

---

## 5. Divergências registradas

1. **Deck de 37 para 41 e depois para 31 slides.** A especificação da SAF mandava gastar a
   folga dos 90 minutos em demonstração estendida, **não em slides novos**. Aqui a folga foi
   gasta em quatro slides novos de governança (11, 12, 18 e 19), e o bloco 2 passou de 10
   para 14 minutos, levando o deck a 41 slides e 72 minutos. Com a saída do bloco de dados
   abertos, o deck fechou em 31 slides e 54 minutos de exposição.
2. **A frase-âncora repete duas vezes, não três.** Ela aparecia nos slides 7, 30 e 37; os
   dois últimos foram para o outro deck. Para não perder o fecho, a faixa foi acrescentada
   ao slide 30 (Artefatos), que passou a ser o último slide de conteúdo. As notas dos slides
   5 e 7 foram ajustadas.
3. **Tag `PRIVACIDADE` virou `GOVERNANÇA`.** O bloco 2 deixou de tratar só de privacidade e
   configuração.
4. **Slide 31 não tem tag de bloco.** O KIT da SAF previa `ENCERRAMENTO` com
   `fa-flag-checkered`, mas o slide L11 nunca a teve. O `KIT.md` foi corrigido para
   descrever o que o deck faz, não o que se pretendia.
5. **Travessão longo.** As regras proíbem travessão longo em todo texto do deck. Ele
   sobrevive em um lugar só: a dica de ferramenta dos pontinhos de progresso do
   `index.html`, que é interface de navegação e não texto projetado.
6. **Leiaute L7 (captura de tela) continua sem uso.** Nenhum slide traz captura; o conteúdo
   ocupa a largura cheia, com corpo maior. Decisão herdada do deck da SAF.
7. **Proposta formal.** Continua fora do deck. O slide 11 mostra que a orientação federal
   existe e que a Agência não tem política própria, mas o deck **não pede decisão por
   escrito em tela nenhuma**. Se essa mensagem importar nesta plateia, ela depende
   inteiramente da fala.
