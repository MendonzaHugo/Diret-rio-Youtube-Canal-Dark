# Diretório YouTube — Canal Dark

Base de conhecimento e análises sobre as **diretrizes do YouTube** aplicadas a **canais dark** (canais sem rosto: narração, roteiro e edição sem o criador aparecer em vídeo).

O projeto tem duas camadas:

1. **`diretrizes/`** — o *diretório*: resumo organizado das políticas do YouTube relevantes para canais dark, com fontes e nível de confiança de cada afirmação.
2. **`analises/`** — as *análises* geradas em cima do diretório: riscos de monetização, checklist por nicho, boas práticas de produção e direitos autorais.

Mais **`templates/`** para aplicar as análises a um canal ou vídeo específico.

> Última verificação geral: **28/10/2026**. As políticas do YouTube mudam com frequência. Antes de tomar uma decisão importante (ex.: pedir entrada no YPP, contestar uma reivindicação), confira a página oficial indicada em cada arquivo.

## Estrutura

```
diretrizes/
  01-ypp-requisitos.md               Requisitos e revisão do Programa de Parcerias (YPP)
  02-conteudo-reutilizado.md         Política de conteúdo reutilizado
  03-conteudo-inautentico.md         Conteúdo inautêntico / repetitivo / produzido em massa (inclui update de jul/2026)
  04-conteudo-sintetico-ia.md        Divulgação de conteúdo alterado ou sintético (IA)
  05-direitos-autorais.md            Content ID, strikes de direitos autorais, uso justo
  06-diretrizes-anunciantes.md       Diretrizes de conteúdo adequado para anunciantes (ícone amarelo)
  07-diretrizes-comunidade.md        Diretrizes da comunidade e sistema de avisos/strikes
  08-desmonetizacao-e-recuperacao.md Suspensão do YPP, contestação, canal relacionado, AdSense desativado
  linha-do-tempo.md                  Histórico datado das mudanças de política
  fontes.md                          Todas as fontes, com classificação de confiabilidade

analises/
  01-riscos-monetizacao.md           Matriz de risco: o que derruba a monetização de um canal dark
  02-checklist-por-nicho.md          Nichos comuns de canais dark avaliados contra as diretrizes
  03-boas-praticas-producao.md       Roteiro, narração, edição e uso de IA em conformidade
  04-direitos-autorais-canal-dark.md Clipes, música, imagens, fair use aplicados ao formato dark

templates/
  checklist-pre-publicacao.md        Checklist rápido antes de subir cada vídeo
  analise-de-canal.md                Roteiro para auditar um canal inteiro antes do pedido de YPP

casos/
  2026-rede-historias/               Caso real: rede de canais de histórias suspensa do YPP
    diagnostico.md                   Mapa da rede, linha do tempo, causas e recomendação por canal
    plano-reconstrucao.md            Plano em fases para recuperar o canal de origem
```

## Legenda de confiança

Cada afirmação nos arquivos de `diretrizes/` traz uma marca:

| Marca | Significado |
|---|---|
| ✅ **Oficial** | Texto ou resumo direto de página oficial do YouTube/Google |
| ✅ **Studio** | Texto copiado de telas reais do YouTube Studio |
| 🟢 **Consolidado** | Regra conhecida há anos e confirmada por várias fontes independentes |
| 🟡 **Secundário** | Reportado por imprensa/blogs de forma consistente, sem acesso ao texto oficial |
| ⚠️ **Não verificado** | Fonte única, contraditória ou de blog de marketing — usar com cautela |

> **Nota sobre a coleta:** nesta primeira versão, as páginas oficiais (`support.google.com`, `blog.youtube`) não estavam acessíveis diretamente do ambiente de pesquisa. O conteúdo foi montado a partir de resultados de busca que citam essas páginas e de cobertura da imprensa. Por isso há bastante 🟡: o próximo passo recomendado é confrontar cada item com o texto oficial e promover a marca para ✅.

## Como usar

- **Vai começar um canal?** Leia `analises/02-checklist-por-nicho.md` para escolher o nicho e `analises/03-boas-praticas-producao.md` para montar o fluxo de produção.
- **Vai pedir o YPP?** Rode `templates/analise-de-canal.md` no canal inteiro.
- **Vai publicar um vídeo?** Use `templates/checklist-pre-publicacao.md`.
- **Canal suspenso do YPP?** Veja `diretrizes/08-desmonetizacao-e-recuperacao.md` e o caso em `casos/2026-rede-historias/`.
- **Recebeu reivindicação ou ícone amarelo?** Veja `diretrizes/05-direitos-autorais.md` e `diretrizes/06-diretrizes-anunciantes.md`.

## Como atualizar

1. Ao detectar mudança de política, registre em `diretrizes/linha-do-tempo.md` com data e fonte.
2. Atualize o arquivo de diretriz correspondente e a data de "Última verificação" no topo dele.
3. Revise as análises em `analises/` que citam aquela diretriz (cada análise lista suas dependências no topo).
4. Adicione a fonte em `diretrizes/fontes.md`.

## Aviso

Este material é uma interpretação organizada das políticas públicas do YouTube, não aconselhamento jurídico. Em casos de direitos autorais com valor financeiro relevante, consulte um advogado.
