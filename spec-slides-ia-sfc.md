# Especificação de conteúdo - Apresentação "IA no dia a dia da Fiscalização"
### Deck adaptado do material apresentado à SAF em 05/08/2026
**16/09/2026 | GPF/SFC | Pedro Henrique Soares**

---

## PARTE I - CONTEXTO

### O que é este documento
Especificação de **conteúdo e intenção**, slide a slide, do deck da SFC. O sistema visual
está inteiro no [`KIT.md`](KIT.md) e **prevalece sobre esta especificação** em qualquer
divergência estética. Este arquivo registra o que cada slide afirma, de onde vem a
afirmação e por que ela mudou em relação ao deck da SAF.

### Contexto da apresentação
- **Evento**: encontro interno da Superintendência de Fiscalização e Coordenação das Unidades Regionais (SFC).
- **Plateia**: toda a SFC - gerências da sede (GAT, GCOR, GPF) e as Gerências e Unidades Regionais. Parte da sala participa a distância. Letramento em IA heterogêneo, majoritariamente baixo a médio; não são pessoas de tecnologia.
- **Apresentador**: Gerente de Planejamento e Inteligência da Fiscalização (GPF/SFC). A GPF é gerência **desta mesma Superintendência** e constrói os sistemas que a plateia usa (SFIS, SisPAT, SAI e os conectores). O apresentador não é visita.
- **Data e hora**: 21 de setembro de 2026, às 16h20.
- **Duração**: 90 minutos. Os chips de tempo das divisórias somam **72 minutos** de exposição; a folga vai para demonstração ao vivo e perguntas, **não para slides novos**.
- **Restrições de fato**: a Agência **não tem política de uso de IA** e **não tem assinatura corporativa** de nenhuma ferramenta. O que existe é orientação federal publicada, e o slide 11 a nomeia.

### Objetivo, em ordem de prioridade
1. Que a plateia saia sabendo **o que nunca pode ser colado** numa ferramenta de IA, com as vedações escritas para o trabalho de fiscalização, e **como configurar privacidade**.
2. Que a plateia saia sabendo montar **um projeto com instruções**, que é a técnica de maior retorno imediato.
3. Que a plateia entenda que **a ausência de política da Agência não é ausência de regra**: há orientação federal em vigor, e ela já responde a maior parte das dúvidas.
4. Que ninguém saia achando que a IA lavra auto, tipifica conduta ou gradua sanção.

### Tese central, reforçada três vezes
> **A IA é revisora, pesquisadora e tradutora de dados. O autor e o responsável continuam sendo o servidor.**

Frase-âncora, idêntica nos slides **7, 30 e 37**:
> **"A IA não assina. Quem assina é você - e quem assina responde."**

### Regras de escrita (obrigatórias em todo texto do deck)
- Português formal da administração pública.
- **Sem travessão longo.** Use hífen simples ou parênteses.
- **Sem estrangeirismos**: "instrução" e não "prompt", "conector" e não "plugin", "conta" e não "account", "programa" e não "software". Exceções aceitas: *prompt* ao citar o guia da SGD/MGI e *MCP*, que é nome próprio de protocolo.
- Frases curtas. Slide não é documento.
- **Máximo de 6 linhas de texto por slide.**
- **Todo número projetado tem linha de fonte no rodapé.**
- Fonte mínima de 17px em qualquer elemento visível.

### Regras de conteúdo (obrigatórias)
- **Não invente nada.** Todo número, data, valor e norma deste deck foi conferido na fonte antes de entrar.
- **Neutralidade de fornecedor**: o deck não recomenda produto.
- Nenhuma demonstração usa processo em tramitação, dado pessoal ou base credenciada. Só dado que a própria Agência publica. Isso é argumento, não acaso: dizer isso em voz alta faz parte do roteiro do slide 37.
- Rodapé padrão em todos os slides de conteúdo: identificação da unidade, fonte e numeração `NN / 41`.

### Vocabulário de leiaute
| Código | Leiaute |
|---|---|
| **L1** | Capa |
| **L2** | Frase de impacto em tela cheia, sem apoio |
| **L3** | Título e lista |
| **L4** | Duas colunas comparativas |
| **L5** | Tabela |
| **L6** | Bloco de texto monoespaçado |
| **L8** | Destaque numérico grande |
| **L10** | Divisória de bloco |
| **L11** | Encerramento e contato |

O leiaute **L7** (captura de tela) não é usado. O deck foi entregue sem nenhuma captura, por
decisão tomada ainda no deck da SAF; o conteúdo ocupa a largura cheia, com corpo maior.

### Divisórias
Uma divisória **L10** antes de cada bloco, com número, título e tempo: slides **4, 10, 20, 28 e 38**.
A abertura (slides 1 a 3) não tem divisória.

---

## PARTE II - CONTEÚDO SLIDE A SLIDE

### Abertura

| # | Leiaute | Conteúdo | Fonte |
|---|---|---|---|
| 1 | L1 | Capa. "IA no dia a dia da **Fiscalização**". Rótulo "Encontro interno · SFC". Data: 21 de setembro de 2026, 16h20. | — |
| 2 | L3 | Duas declarações. (1) A GPF é a gerência que constrói e mantém os sistemas que vocês usam todo dia. (2) A Agência não tem política de uso de IA; o que existe é orientação federal, e ela já diz bastante coisa. | — |
| 3 | L3 | Três perguntas de mão levantada. A segunda cita relatório, auto de infração e defesa. A terceira (quem sabe dizer se a conta usada treina modelo com o conteúdo) fica sem mãos, e esse silêncio é o gancho do bloco 2. | — |

### Bloco 1 · Como funciona e onde quebra (10 min)

| # | Leiaute | Conteúdo | Fonte |
|---|---|---|---|
| 4 | L10 | Divisória. Chips: completação de texto, contexto, alucinação, conferência na fonte. | — |
| 5 | L2 | A tese central, primeira das três aparições. | — |
| 6 | L4 | O que a ferramenta é: completação de texto, não consulta a banco de dados. | — |
| 7 | L4 | Contexto é tudo: sem e com o relatório de fiscalização anexado. **Faixa-âncora #1.** | — |
| 8 | L3 | Alucinação não é acidente, é característica. O modelo é melhor exatamente naquilo que é padronizado: norma, artigo, inciso, número de processo e valor. Erro de redação você percebe; erro de enquadramento, não - até a defesa apontar. | Guia de IA Generativa no Serviço Público (SGD/MGI com SERPRO) |
| 9 | L2 | A regra sem exceção: norma, artigo, inciso, processo, valor. Sempre. | — |

### Bloco 2 · O que já está escrito, e o que nunca entra (14 min)

Bloco reescrito em relação ao deck da SAF, que tinha 6 slides e tratava só de privacidade e
configuração. Aqui são 10 slides, e o eixo é a orientação federal já publicada.

| # | Leiaute | Conteúdo | Fonte |
|---|---|---|---|
| 10 | L10 | Divisória. Chips: guias federais em vigor, o que nunca entra, treinamento de modelo, dado fictício e transparência. | — |
| 11 | L5 | **A Agência não tem política. A União já publicou orientação.** Cinco documentos, com o órgão emissor de cada um: Guia de IA Generativa no Serviço Público (SGD/MGI com SERPRO); Guia de Uso Responsável de Ferramentas de IA Generativa (CGU); Guia Prático de Prompt e Pesquisa com IA (SGD/MGI); Radar Tecnológico de IA Generativa (ANPD); Guia de uso de IA generativa no TCU. Faixa: nenhum é norma da ANTAQ, todos são boa prática publicada, e nenhum depende de contratar ferramenta. | Páginas oficiais dos órgãos, consultadas em 16/09/2026. O guia da CGU foi aprovado pela Portaria Normativa CGU nº 193, de 6 de janeiro de 2025 |
| 12 | L3 | **Cinco princípios, e nenhum deles é novo**: legalidade, imparcialidade (ferramenta não gradua sanção), ética, publicidade (o que você não consegue explicar não vai para os autos) e eficiência. Faixa: a responsabilidade do servidor sobre o documento produzido permanece inalterada, com ou sem IA. | Guias federais citados no slide 11 |
| 13 | L3 | **O que nunca entra**, seis vedações escritas para a fiscalização: dado pessoal ou sensível, inclusive de tripulante e passageiro; retorno do Sinesp Infoseg ou de base credenciada; processo em sigilo ou denúncia identificável; planejamento de ação fiscal não deflagrada (ordem de serviço, alvo, data, roteiro); informação econômico-financeira de regulado; credencial e correio eletrônico institucional para abrir conta não aprovada. | Regimento Interno da ANTAQ, art. 86; guias federais |
| 14 | L2 | "90% público" não protege ninguém. O incidente acontece nos 10%, e a fiscalização trabalha dentro deles todo dia. | — |
| 15 | L5 | **Os 10% ficam aqui**: mapa de risco por unidade. GREs e UREs (planejamento de ação não deflagrada, denúncia); GAT (minuta de decisão recursal); GPF (critérios de seleção de alvo); GCOR (escala e deslocamento de equipes); transversal (art. 86 e retorno do Sinesp Infoseg). | Regimento Interno da ANTAQ; Ofício Circular nº 3/2023/SFC/ANTAQ |
| 16 | L4 | Treinamento de modelo é escolha sua, e o botão fica na configuração. Cartão adicional: o guia federal manda priorizar a solução aprovada pela instituição; enquanto a Agência não aprovar nenhuma, aquele botão é a única proteção que existe. | Documentação pública de privacidade da ferramenta demonstrada; guias federais |
| 17 | L5 | Conta pessoal x conta institucional. A diferença não é o preço, é o contrato. | Documentação pública de privacidade da ferramenta demonstrada |
| 18 | L4 | **Para testar, use dado que não existe.** Coluna vermelha (como quase todo mundo testa) contra coluna azul (como o guia manda testar), mais quatro técnicas: mascaramento, tokenização, generalização e dado sintético. Faixa dourada sobre credencial genérica desvinculada da instituição. | Guias federais citados no slide 11 |
| 19 | L3 | **Dizer que usou não enfraquece o documento.** Fecha com o carimbo de transparência: "Parte do conteúdo foi gerado com o auxílio de IA." | Guias federais citados no slide 11 |

### Bloco 3 · Projeto, instruções e memória (20 min)

| # | Leiaute | Conteúdo | Fonte |
|---|---|---|---|
| 20 | L10 | Divisória. | — |
| 21 | L4 | O que o projeto resolve: sem projeto, você reexplica o que é uma NOCI, qual resolução tipifica o quê e o que a sua unidade fiscaliza, e recola os mesmos manuais. | — |
| 22 | L3 | Criando o projeto **"SFC - Instrução de processo sancionador"**, em quatro passos. | Resolução ANTAQ nº 3.259/2014 |
| 23 | L6 | **As instruções do projeto**, escritas uma vez e válidas para sempre. É o slide central do deck. Contexto (regime legal, produtos, SFIS e SEI), como trabalhar (nunca inventar norma; citar norma, artigo, inciso e alínea com aviso de conferir vigência; confrontar conduta com dispositivo e evidência; devolver achados como CRÍTICO / RELEVANTE / FORMAL) e um bloco dourado de vedações (não decidir nem graduar sanção; dado aberto é indício, não prova; nada de dado pessoal, sigilo ou base credenciada). | Lei 10.233/2001, Lei 12.815/2013, Resolução ANTAQ nº 3.259/2014 |
| 24 | L4 | O que subir: manuais de fiscalização da SFC, resoluções que tipificam infração, ordens de serviço da SFC, Regimento Interno, modelos e listas de verificação da casa. O que não subir: qualquer coisa do slide 13. | — |
| 25 | L5 | As quatro camadas que todo mundo confunde: instruções, conhecimento, contexto e memória. | — |
| 26 | L4 | Memória: saber desligar vale mais do que saber ligar. O isolamento impede que a conversa de um processo sancionador vaze para o projeto de outro. | — |
| 27 | L2 | Como começar: "Vou criar um projeto para a minha Unidade Regional, que fiscaliza navegação interior." | — |

### Bloco 4 · Conector e dados abertos (18 min)

Bloco inteiramente refeito. O deck da SAF demonstrava um conector de Compras Públicas sobre
o PNCP; aqui as quatro demonstrações usam o **conector MCP de Dados Abertos da ANTAQ**,
construído na GPF sobre os painéis e o acervo normativo que a Agência já publica.

| # | Leiaute | Conteúdo | Fonte |
|---|---|---|---|
| 28 | L10 | Divisória. Chips: protocolo aberto (MCP), enquadramento, histórico do fiscalizado, qualidade do dado. | — |
| 29 | L4 | A diferença que um conector faz: sem conector a IA fala sobre fiscalização; com conector ela consultou o painel de Fiscalização agora e trouxe o dado. | — |
| 30 | L3 | O conector de Dados Abertos da ANTAQ foi feito aqui: protocolo aberto, desenvolvido na GPF sem custo de contratação, consumindo só o que a Agência publica. Último item: nenhum processo em tramitação sai daqui. **Faixa-âncora #2.** | — |
| 31 | L6+L8 | **Demonstração 1 - o enquadramento que mais soma multa é o genérico.** O tipo residual da Resolução ANTAQ nº 3.274/2014, art. 32, XXXVIII, traz dentro de si a ressalva "exceto quando a conduta infracional se enquadrar em tipo específico contemplado nesta norma". Destaque: R$ 18,7 milhões de R$ 106,4 milhões, em 281 infrações julgadas. | Painel Fiscalização, quadros "Base de Dados" e "Objeto das Normas", via conector MCP (GPF), 16/09/2026; valores nominais |
| 32 | L3 | **Enquadramento genérico não é detalhe de redação**: o tipo residual só cabe sem tipo específico; tipificação frouxa dificulta a defesa; o erro aparece no recurso, anos depois. Cartão de alerta em vermelho. | Curso de introdução à fiscalização da SFC |
| 33 | L6+L8 | **Demonstração 2 - o histórico do fiscalizado, antes de autuar.** 2.824 empresas, 17.505 processos, 19.708 registros. Recortes por empresa, unidade, infração, tipo de decisão e ano. Faixa: não substitui a consulta ao SFIS e só alcança processo já julgado. | Painel Fiscalização via conector MCP (GPF), 16/09/2026 |
| 34 | L6+L8 | **Demonstração 3 - a citação que a base erra, e o conector avisa.** O rótulo de artigo da base de origem aponta o dispositivo errado em **68%** dos casos e o de parágrafo em 98%; e em dois documentos do procedimento sancionador a extração do arquivo comeu letras ("instalaçes", "rgãos", "contraditrio"). Faixa: citação errada é vício de tipificação; a busca localiza, o diário oficial transcreve. | Acervo normativo do setor aquaviário (50 documentos, 2.530 trechos) via conector MCP (GPF), 16/09/2026. Documentos com defeito: Resolução ANTAQ nº 3.259/2014 e Resolução Normativa nº 7/2016 |
| 35 | L5 | **Demonstração 4 - dado aberto não é dado limpo.** Os três estados de "Valor da Multa": 3.319 com número, 11.876 com hífen (arquivado sem irregularidade) e 4.513 com célula vazia (decisão que não foi multa). Mais duas armadilhas: a linha é uma infração julgada e não um processo (19.708 para 17.505, +12,6%), e o detalhe publicado é mais curto que a manchete do painel (710 registros e R$ 3.826.426,96 a menos). | Painel Fiscalização, quadro "Base de Dados", via conector MCP (GPF), 16/09/2026; acervo de 2014 a 2026, valores nominais |
| 36 | L2 | Conclusão do bloco: a IA acelera o acesso, e não substitui quem olha para "11.876 multas de valor zero" e desconfia. Essa desconfiança é a competência da sala. | — |
| 37 | L3 | **O conector acha o dispositivo. Ele não lavra o auto.** O rito continua sendo o da Resolução 3.259/2014. **Faixa-âncora #3.** | Resolução ANTAQ nº 3.259, de 30 de janeiro de 2014 |

### Bloco 5 · Habilidades e artefatos (7 min)

| # | Leiaute | Conteúdo | Fonte |
|---|---|---|---|
| 38 | L10 | Divisória. | — |
| 39 | L3 | Habilidade é o procedimento da casa virando ferramenta reutilizável. Exemplo: uma "Conferência de relatório de fiscalização" que roda sempre igual, em qualquer unidade. | — |
| 40 | L3 | Artefato é a resposta virando arquivo: quadro de acompanhamento do plano de fiscalização, consolidação de resultados das unidades, relatórios periódicos. O arquivo ainda precisa ser conferido. Sempre. | — |

### Encerramento

| # | Leiaute | Conteúdo | Fonte |
|---|---|---|---|
| 41 | L11 | Contato, material de apoio e código de leitura óptica apontando para `antaq.github.io/apresentacao_ia_sfc`. | — |

---

## PARTE III - PROVENIÊNCIA

Este deck deriva do `apresentacao_ia_saf`, apresentado em 5 de agosto de 2026. O que mudou:

1. **Plateia e vocabulário.** Todo exemplo de contratações públicas foi trocado por exemplo
   de fiscalização. "Termo de Referência" virou "relatório de fiscalização"; "acórdão,
   artigo, súmula" virou "norma, artigo, inciso"; GLC, GGP, GOF, GRL e NCR saíram, e GAT,
   GCOR, GPF, GREs e UREs entraram.
2. **Bloco 2 reescrito e ampliado de 6 para 10 slides** (10 para 14 minutos), para
   incorporar as orientações federais publicadas sobre IA generativa: os documentos em vigor
   (11), os princípios (12), o teste com dado que não existe (18) e a transparência sobre o
   uso (19). As vedações do slide 13 passaram de 5 para 6 e foram reescritas para o trabalho
   de fiscalização. A tag do bloco mudou de `PRIVACIDADE` para `GOVERNANÇA`.
3. **Bloco 4 refeito.** As quatro demonstrações passaram do conector de Compras Públicas
   para o conector de Dados Abertos da ANTAQ. A escolha não é só temática: as armadilhas de
   qualidade de dado que o conector mede (rótulo de artigo errado em 68%, três estados do
   valor da multa, linha que não é processo, base mais curta que o painel) são o melhor
   material possível para o argumento do slide 36.
4. **Instruções do projeto (slide 23) reescritas do zero**, com o regime legal do setor
   aquaviário e vedações explícitas sobre decisão, graduação de sanção e uso de dado aberto
   como prova.
5. **Deck de 37 para 41 slides.** A especificação da SAF mandava gastar a folga dos 90
   minutos em demonstração, não em slides novos. Aqui a folga foi gasta em quatro slides
   novos de governança (11, 12, 18 e 19), e a divergência está registrada no
   [`PENDENCIAS.md`](PENDENCIAS.md).
