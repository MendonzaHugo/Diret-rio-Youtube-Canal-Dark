# Análise 01 — Riscos de monetização para canais dark

> Baseada em: `diretrizes/01`, `02`, `03`, `04`, `06` · Atualizada em 28/10/2026

## Conclusão principal

O YouTube **não pune canais dark nem o uso de IA**. Ele pune canais **intercambiáveis**: aqueles em que os vídeos poderiam ser gerados em série, trocando só o tema, sem que ninguém percebesse diferença. Desde julho/2026, essa avaliação é feita **olhando o canal inteiro**, e uma categoria nova e subjetiva ("insatisfatório ou desagradável") amplia o que o revisor pode reprovar.

Para um canal dark, o risco de monetização está menos em **o que** se usa (voz de IA, stock footage) e mais em **quanto do vídeo é seu**: roteiro, ponto de vista, pesquisa, estrutura.

## Matriz de risco

Probabilidade × impacto para os padrões mais comuns em canais dark.

| # | Padrão | Política atingida | Probabilidade | Impacto | Nível |
|---|---|---|---|---|---|
| R1 | Mesmo template visual + mesma estrutura de roteiro + mesma voz em todos os vídeos, mudando só o tema | Inautêntico (cat. 1) | Alta | Canal inteiro reprovado/removido do YPP | 🔴 Crítico |
| R2 | Narração de IA lendo texto de artigo, Wikipedia ou Reddit sem análise própria | Inautêntico + Reutilizado | Alta | Canal inteiro | 🔴 Crítico |
| R3 | Slideshow de imagens ou texto rolando com pouca narração | Inautêntico | Alta | Canal inteiro | 🔴 Crítico |
| R4 | Compilação de clipes (filmes, TikTok, esportes) com narração mínima | Reutilizado + Direitos autorais | Alta | Canal inteiro + strikes | 🔴 Crítico |
| R5 | Avatar/persona de IA dando conselhos de finanças, saúde ou jurídicos | Inautêntico (cat. 3) | Alta | Canal inteiro | 🔴 Crítico |
| R6 | Volume muito alto de uploads (vários por dia) com qualidade baixa | Inautêntico + Spam | Média-alta | Canal inteiro, possível encerramento | 🟠 Alto |
| R7 | Vídeos "chocantes" feitos para engajamento (desastres gerados por IA, sofrimento, sustos) | Inautêntico (cat. 2) + Anunciantes | Média | Canal ou vídeos | 🟠 Alto |
| R8 | Imagens realistas geradas por IA sem rótulo de conteúdo sintético | Sintético/IA | Média | Rótulo forçado, possível suspensão do YPP | 🟠 Alto |
| R9 | Miniaturas/títulos com sangue, armas, corpos, palavrões | Anunciantes | Alta | Vídeos com ícone amarelo | 🟡 Médio |
| R10 | Música comercial ou trilhas de filmes no fundo | Direitos autorais (Content ID) | Alta | Receita do vídeo vai para o titular | 🟡 Médio |
| R11 | Clipes curtos de filmes/séries para ilustrar narração original | Direitos autorais | Média | Reivindicação ou strike | 🟡 Médio |
| R12 | Canal com vídeos antigos fracos misturados com vídeos novos bons | Revisão do YPP é por canal | Média | Reprovação no pedido | 🟡 Médio |
| R13 | Voz de IA em roteiro próprio com visuais variados e editados | — | Baixa | — | 🟢 Baixo |
| R14 | Mesmo formato replicado em vários canais/idiomas/contas pelo mesmo operador | Inautêntico + canal relacionado + Spam | Alta | **Todos os canais do operador** perdem a monetização; risco de encerramento | 🔴 Crítico |

> R14 foi documentado em um caso real: `casos/2026-rede-historias/`. Contas de e-mail diferentes **não** separam canais do mesmo operador.

## Sinais que um revisor provavelmente usa

O YouTube não publica um checklist, mas o conjunto das diretrizes aponta para estes sinais (inferência 🟡):

- **Variação entre vídeos:** estrutura, duração, abertura e visual mudam conforme o tema?
- **Densidade de informação própria:** o roteiro traz pesquisa, argumento, opinião ou só reformula fontes?
- **Relação imagem–narração:** as imagens foram escolhidas para aquele trecho ou são genéricas/aleatórias?
- **Ritmo de publicação vs. qualidade:** 3 vídeos/dia com 10 min cada sugere automação.
- **Presença editorial:** existe uma "voz" do canal (opinião, humor, estilo) reconhecível?
- **Metadados honestos:** título e miniatura correspondem ao que o vídeo entrega?

## Teste rápido: "o vídeo é intercambiável?"

Responda para os 10 vídeos mais vistos e os 10 mais recentes:

1. Se eu trocar o tema, a estrutura e o visual continuam idênticos? → se **sim**, risco R1.
2. Alguém poderia gerar este roteiro com um único prompt? → se **sim**, risco R2.
3. Há mais de 30 s seguidos sem narração ou comentário sobre o que está na tela? → risco R3/R4.
4. O vídeo tem uma opinião, conclusão ou descoberta que não está nas fontes? → se **não**, risco R2.
5. Eu assistiria até o fim se não fosse o dono do canal? → se **não**, risco R7 (insatisfatório).

**Regra prática:** 2 ou mais "sim/não" de risco em mais de um terço dos vídeos → não peça o YPP ainda; corrija ou oculte (privado) os vídeos problemáticos primeiro.

## Recomendações

1. **Antes do YPP:** auditar o canal inteiro com `templates/analise-de-canal.md`. Vídeos que não passam devem ir para **privado** antes do pedido — a revisão olha o que está público.
2. **Variar o formato:** ter 2–3 formatos (ex.: documentário longo, top-lista com análise, episódio de série) evita a cara de template.
3. **Volume sustentável:** priorizar 2–4 vídeos/semana bem feitos a vários por dia.
4. **Nada de persona de IA em nicho sensível:** em finanças/saúde, a narração deve ser apresentada como narração, não como um "especialista" fictício.
5. **Rotular IA realista** sempre que houver dúvida — o custo de rotular é quase zero; o de não rotular pode ser o YPP.
6. **Monitorar a linha do tempo:** a categoria "insatisfatório ou desagradável" (jul/2026) ainda não tem limites claros — tende a ser refinada.
