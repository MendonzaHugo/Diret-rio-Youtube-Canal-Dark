# Caso 2026 — Rede de canais de histórias: diagnóstico

> Data: 28/10/2026 · Base: capturas da aba **Ganhos** do YouTube Studio e da lista de contas · Diretrizes: `diretrizes/03`, `diretrizes/08` · Análises: `analises/01` (R1, R2, R7, R14), `analises/02` (histórias narradas)
>
> As contas de e-mail foram substituídas por **Conta A/B/C**.

## 1. A rede

| Conta | Canal | Idioma (provável) | Inscritos | Status no YPP |
|---|---|---|---|---|
| A | **Ispovijesti Srca** ("Confissões do coração") | croata/bósnio | 2.210 | Suspenso: **genérico ou repetitivo**. Contestação **negada**. |
| A | **Гласовете на времето** ("Vozes do tempo") | búlgaro | 2.010 | Termos aceitos; AdSense não conectado; análise não iniciada |
| A | **Naša Sjećanja** ("Nossas memórias") | croata/bósnio | 1.480 | Suspenso: **canal relacionado**. Prazo de contestação: 29/04/2026 (perdido) |
| B | Vrouwenverhalen ("Histórias de mulheres") | holandês | 946 | Não monetizado |
| B | Нашият път ("Nosso caminho") | búlgaro | 690 | Não monetizado |
| B | Historie Joanny ("Histórias da Joanna") | polonês | 105 | Não monetizado |
| B | (canal pessoal) | — | 30 | Fora do escopo |
| C | **Odwaga Kobiet** ("Coragem das mulheres") | polonês | 1.500 | Suspenso: **insatisfatório ou desagradável**. Prazo de contestação: 08/05/2026 (perdido) |
| C | Vergeten Levens ("Vidas esquecidas") | holandês | 127 | Não monetizado |

**Resumo:** 8 canais do mesmo formato, em 4 idiomas e 3 contas. Três deles foram monetizados e depois suspensos.

## 2. Linha do tempo reconstruída

O prazo de contestação é de 21 dias, então a data da suspensão é a data-limite menos 21 dias.

| Data aprox. | Evento |
|---|---|
| antes de 08/04/2026 | **Ispovijesti Srca** é suspenso por conteúdo genérico ou repetitivo. Depois, a contestação é negada. |
| ~08/04/2026 | **Naša Sjećanja** é suspenso como **canal relacionado** |
| ~17/04/2026 | **Odwaga Kobiet** (outra conta) é suspenso por conteúdo insatisfatório ou desagradável |

**Conclusão:** a suspensão "relacionada" do Naša Sjećanja é **anterior** à do Odwaga Kobiet. A origem mais provável é o **Ispovijesti Srca**, que está na mesma conta e tem suspensão própria. 🟡 (inferência por datas; o Studio não diz qual é o canal de origem)

O Odwaga Kobiet, numa **conta de e-mail diferente**, foi suspenso dias depois. Isso é consistente com uma revisão do operador inteiro, e não de canais isolados.

## 3. Diagnóstico

### 3.1 O problema é o modelo de produção, não vídeos específicos

Os sinais visíveis (nomes, avatares, idiomas) indicam **um único modelo replicado**:

- histórias emocionais em primeira pessoa voltadas ao público feminino;
- avatares de retrato feminino gerado por IA com moldura floral, no mesmo estilo em todos os canais;
- o mesmo conceito traduzido para croata, búlgaro, polonês e holandês;
- canais abertos em paralelo, vários parados perto do mínimo do YPP.

Os dois motivos de suspensão descrevem esse modelo:

- **Genérico ou repetitivo:** "pode parecer repetitivo para os espectadores depois de assistir vários vídeos seguidos". O formato de confissões tende a ter estrutura, tom e visual iguais de um vídeo para outro.
- **Insatisfatório ou desagradável:** "emocionalmente manipulador… sem oferecer um valor significativo". Histórias de sofrimento feitas para prender pela emoção se encaixam diretamente nessa definição.

### 3.2 A rede é, ela mesma, um sinal de conteúdo inautêntico

O mesmo conteúdo em vários idiomas e contas é o padrão de **fazenda de conteúdo**. Isso pesa mesmo que cada canal, isolado, parecesse aceitável.

### 3.3 Usar contas separadas não separou nada

Canais das contas A e C foram tratados como do mesmo operador. Para o YouTube, todos os canais da tabela são **um só operador**.

## 4. Riscos

| Risco | Probabilidade | Impacto |
|---|---|---|
| Qualquer novo pedido de YPP na rede cair em "canal relacionado" | Muito alta | Sem receita |
| Nova reinscrição do Ispovijesti Srca ser negada se o modelo continuar o mesmo | Muito alta | Mais 90 dias de espera |
| Rede tratada como spam pelas Diretrizes da Comunidade | Média | **Encerramento de canais**, possivelmente todos os ligados |
| Ganhos não pagos retidos | Já sinalizado pelo YouTube | Perda financeira |

## 5. Recomendação por canal

| Canal | Ação | Motivo |
|---|---|---|
| **Ispovijesti Srca** | **Reconstruir** (ver `plano-reconstrucao.md`) | Provável canal de origem. Se voltar ao YPP, libera os canais relacionados. Tem o maior número de inscritos. |
| Odwaga Kobiet | Congelar e consultar o suporte. Provavelmente precisará ser reconstruído **junto** com o Ispovijesti Srca. | Segunda suspensão própria ativa. Pode gerar suspensão por canal relacionado nos outros canais do operador, inclusive num Ispovijesti Srca já aprovado (ver `plano-reconstrucao.md`) |
| Naša Sjećanja | Congelar | Depende do canal de origem |
| Гласовете на времето | **Não conectar o AdSense.** Congelar. | Conectar agora quase certamente resulta em "canal relacionado" |
| Vrouwenverhalen, Нашият път, Historie Joanny, Vergeten Levens | Parar de publicar no modelo atual. Não pedir o YPP. | Reforçam o sinal de rede e aumentam o risco de spam |

"Congelar" significa não publicar no modelo atual, não pedir o YPP e não excluir o canal. Excluir não desfaz a ligação com o operador e não pode ser revertido.

## 6. Dados que faltam para fechar o diagnóstico

- [ ] Horas de exibição públicas dos últimos 12 meses do Ispovijesti Srca (Analytics).
- [ ] Data exata da suspensão de cada canal (e-mails do YouTube).
- [ ] Como os vídeos são produzidos hoje: origem das histórias, roteiro, voz, imagens.
- [ ] Se o mesmo roteiro é traduzido entre os canais.
- [ ] Status da conta do AdSense (deve estar ativa).
