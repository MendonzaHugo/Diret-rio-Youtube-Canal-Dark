# Análise 03 — Boas práticas de produção

> Baseada em: `diretrizes/02`, `03`, `04`, `05`, `06` · Atualizada em 28/10/2026

Objetivo: um fluxo de produção de canal dark que **escale** sem cair em conteúdo inautêntico. A regra geral: **IA pode acelerar etapas, mas a decisão editorial precisa ser humana e visível no resultado.**

## 1. Pauta e pesquisa

| Faça | Evite |
|---|---|
| Escolher um ângulo ou pergunta por vídeo ("por que…", "como…") | Pautas genéricas iguais às de centenas de canais |
| Pesquisar em mais de uma fonte e registrar as fontes | Basear o vídeo em uma única fonte (artigo, Wikipedia, post) |
| Checar fatos, especialmente números, datas e temas de saúde/finanças | Repetir "curiosidades" sem verificar |

## 2. Roteiro

- **IA pode ajudar** a gerar ideias, estruturar tópicos e revisar texto — isso não exige rótulo. 🟢
- **O roteiro final deve conter algo que não está nas fontes:** conclusão, comparação, opinião, conexão entre fatos, humor, pergunta para o público.
- **Varie a estrutura** conforme o tema. Ganchos, transições e encerramentos idênticos em todos os vídeos são sinal de template.
- **Teste do prompt único:** se um único prompt conseguiria gerar o roteiro, ele ainda não é seu.

## 3. Narração

| Opção | Risco | Observação |
|---|---|---|
| Voz própria (sem aparecer) | 🟢 Mínimo | Melhor sinal de autenticidade |
| Locutor contratado | 🟢 Mínimo | Ter contrato/licença de uso comercial |
| Voz de IA genérica, roteiro próprio | 🟢–🟡 Baixo | Permitida; usar ferramenta com licença comercial |
| Voz de IA clonando pessoa real | 🔴 Alto | Exige rótulo; risco de remoção por privacidade e de imitação |
| Persona/avatar de IA "especialista" em saúde, finanças, jurídico | 🔴 Crítico | Inautêntico (jul/2026) |

- Ajuste ritmo, pausas e ênfase da voz de IA — narração monótona aumenta a chance de cair em "insatisfatório".
- Não use a mesma voz exatamente igual em vários canais seus: reforça a cara de fazenda de conteúdo.

## 4. Visual e edição

- As imagens devem **ilustrar o que está sendo dito naquele momento**, não ser B-roll aleatório.
- Misture tipos de visual: stock footage, mapas, gráficos, textos animados, gravações de tela, ilustrações próprias.
- Crie elementos **seus**: identidade visual, gráficos, mapas, linha do tempo animada.
- Evite: slideshow estático com zoom lento por minutos; texto rolando; mesmo layout em todos os vídeos.
- **Imagens realistas geradas por IA** de pessoas, eventos ou lugares reais → **ativar o rótulo** "conteúdo alterado ou sintético" no Studio.

## 5. Título, miniatura e descrição

- Prometa o que o vídeo entrega (metadados enganosos = spam).
- Miniatura sem sangue, armas apontadas, corpos, nudez ou palavrões — é avaliada pelas diretrizes de anunciantes.
- Descrição com **fontes** e créditos de licenças (créditos não substituem licença, mas mostram cuidado).
- Declarar uso de IA na descrição é opcional, mas ajuda na transparência.

## 6. Publicação e cadência

- Prefira consistência a volume: 2–4 vídeos bons por semana > vários por dia.
- Use as **verificações** do Studio antes de publicar para pegar Content ID.
- Configure corretamente "feito para crianças".
- Use `templates/checklist-pre-publicacao.md` em cada vídeo.

## 7. Uso de IA — resumo

| Etapa | Uso de IA | Precisa rotular? | Risco de inautêntico |
|---|---|---|---|
| Ideias, pauta, pesquisa auxiliar | ✅ Livre | Não | Baixo |
| Rascunho de roteiro | ✅ Com revisão e autoria humana | Não | Médio se sem edição |
| Narração (voz genérica) | ✅ | Não | Baixo com roteiro próprio |
| Legendas, tradução | ✅ | Não | Baixo |
| Imagens claramente artísticas/irreais | ✅ | Não | Baixo |
| Imagens/vídeos realistas | ⚠️ | **Sim** | Médio |
| Voz/rosto de pessoa real | ⚠️ | **Sim** | Alto |
| Vídeo inteiro gerado de ponta a ponta em série | ❌ | — | Crítico |
| Persona de IA em tema sensível | ❌ | — | Crítico |

## 8. Escalar sem virar fazenda de conteúdo

- Escale **pesquisa e edição**, não "copiar e colar com outro tema".
- Mantenha um **guia editorial** do canal (tom, opinião, tipos de fonte, formatos) — ele é o que torna os vídeos reconhecíveis.
- Revise amostras do canal a cada mês com o teste de `analises/01-riscos-monetizacao.md`.
