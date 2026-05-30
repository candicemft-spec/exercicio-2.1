# Mapa de Atores — Pensão por Morte RGPS (Espécie 21)
**Jornada:** Requerimento e concessão via Meu INSS, Central 135 e atendimento presencial
**Produzido em:** 2026-05-30 | **Versão:** final | **Base:** relatório assistente v3 + decisões da sessão grill-me

---

## Decisões estruturais do mapa

| Dimensão | Decisão |
|---|---|
| Propósito | Facilitação de workshop |
| Público | Misto — técnicos e gestores, multiorganizacional |
| Granularidade | Separa atores quando o papel na jornada é diferente; mesmo papel = bloco único com nota |
| Formato | Matriz: 7 momentos (eixo horizontal) × 9 categorias de atores (eixo vertical) |
| Gargalos | Apenas veto alto entram na matriz como ⚑; demais ficam em anexo |

---

## Legenda

| Símbolo | Significado |
|---|---|
| ◉ | Entrada — ator começa a atuar neste momento |
| ● | Ativo — ator em plena atuação |
| ○ | Saída — ator encerra atuação neste momento |
| ◉○ | Entra e sai no mesmo momento |
| ⚑ | Flag — gargalo de veto alto neste cruzamento |
| * | Saída condicional — veja nota |
| — | Ausente neste momento |

**Momentos da jornada:**
`Pré` = Pré-requerimento · `Req` = Requerimento · `Instr` = Instrução · `Dec` = Decisão · `Pag` = Pagamento/Manutenção · `Rec` = Recurso Administrativo · `Ctrl` = Controle e Responsabilização

---

## Matriz de Atores × Momentos

| Categoria | Ator | Pré | Req | Instr | Dec | Pag | Rec | Ctrl |
|---|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **Demandantes** | Dependente requerente | — | ◉ | ● | ● | ○* | (*●) | — |
| | Cônjuge / companheiro(a) | — | ◉ | ● | ● | ○* | (*●) | — |
| | Filhos / equiparados | — | ◉ | ● | ● | ○ | — | — |
| | Pais e irmãos elegíveis | — | ◉ | ● | ● | ○ | — | — |
| | Co-dependentes | — | — | ◉ | ● | ● | ○ | — |
| | Representante legal / tutor / curador | — | — | ◉ | ● | ○ | — | — |
| **Canais de acesso** | Meu INSS | — | ◉ | ● | ● | ○ | — | — |
| | Central 135 | — | ◉ | ○ | — | — | — | — |
| | APS (atendimento presencial) | — | ◉ | ○ | — | — | — | — |
| **Autenticação e identidade** | Gov.br Bronze ⚑ | — | ◉○⚑ | — | — | — | — | — |
| | Gov.br Prata | — | ◉○ | — | — | — | — | — |
| | Gov.br Ouro | — | ◉○ | — | — | — | — | — |
| | RFB / CPF ⚑ | ◉⚑ | ● | ○ | — | — | — | — |
| **Decisão previdenciária** | INSS | — | — | ◉ | ● | ○ | — | — |
| **Sistemas e dados** | Cartório / SIRC ⚑ | ◉⚑ | ● | ○ | — | — | — | — |
| | CNIS ⚑ | — | — | ◉⚑ | ○ | — | — | — |
| | Dataprev ⚑ | — | ◉⚑ | ● | ● | ○ | — | — |
| **Pagamento e manutenção** | Banco pagador | — | — | — | — | ◉○ | — | — |
| **Instância recursal** | CRPS — Juntas / Câmaras | — | — | — | — | — | ◉○ | — |
| | CRPS — Conselho Pleno | — | — | — | — | — | ◉○ | — |
| **Judicial** | Justiça Federal / JEF | — | — | — | ◉ | ● | ● | ○ |
| **Controle e responsabilização** | AGU / PFE-INSS | — | — | — | ◉ | ● | ● | ○ |
| | TCU / CGU / MPF / PF | — | — | — | — | — | — | ◉○ |
| | STF / CPMI ⚑ | — | — | — | — | — | — | ◉○⚑ |

**Total: 24 atores/blocos · 9 categorias · 7 momentos**

---

## Flags e notas das células

### ⚑ Gov.br Bronze — Requerimento
**Divergência probatória em aberto:** o audit\_v2 indicou que atendimento presencial em Agências do INSS / Balcão gov.br eleva para nível prata; a página oficial consultada lista essa rota no bloco **bronze**. O mapa não afirma "presencial = prata" sem fonte normativa adicional.
**Debate para o workshop:** a orientação ao cidadão está alinhada à página oficial atual ou a norma interna diferente?

### ⚑ RFB/CPF — Pré-requerimento
CPF do segurado falecido e do dependente é chave de interoperabilidade entre cartório, SIRC, CNIS e Meu INSS. CPF ausente ou inconsistente pode contaminar toda a cadeia de análise.
**Debate para o workshop:** quem é responsável por garantir o CPF válido no registro de óbito?

### ⚑ Cartório/SIRC — Pré-requerimento
Obrigação de remessa ao INSS em até 1 dia útil (Lei 8.212/91, art. 68). Erro de CPF ou data de óbito pode gerar indeferimento indevido ou pagamento indevido.
**Debate para o workshop:** quem é dono da correção ponta a ponta do dado de óbito?

### ⚑ CNIS — Instrução
Base para aferição de qualidade de segurado e histórico contributivo. Lacuna ou inconsistência no CNIS pode bloquear a concessão sem que o dependente saiba a causa real.
**Debate para o workshop:** o dependente é informado quando o bloqueio decorre de lacuna no CNIS, não de ausência de direito?

### ⚑ Dataprev — Requerimento
Dependência tecnológica contratual. Falha sistêmica da Dataprev pode paralisar o processamento de requerimentos em todos os canais simultaneamente.
**Debate para o workshop:** existe plano de continuidade operacional mapeado para falha Dataprev?

### ⚑ STF/CPMI — Controle
**Trilha excepcional.** Atuam em accountability estrutural e sistêmico, não em casos individuais ordinários. Presença no mapa sinaliza a camada máxima de escrutínio externo, não atuação rotineira.

---

## Notas de atores

### * Saída condicional — Dependente requerente e Cônjuge/companheiro
Saída ordinária em **Pagamento/manutenção**. Se houver indeferimento ou contestação de rateio, o ator continua ativo na trilha **Recurso administrativo** e pode chegar até o momento **Judicial** (não representado como coluna de saída para não poluir a leitura da jornada ordinária).

### Nota — Representante legal no pagamento (Banco pagador)
O art. 69, §8º da Lei 8.212/91 prevê que representante legal ou procurador pode intermediar o recebimento do benefício junto à instituição financeira. Aparece como nota na célula Banco pagador / Pagamento, não como ator separado (mesmo ator da categoria Demandantes, papel distinto).

### Nota — Titular do cartório (Cartório/SIRC)
O art. 68, §5º da Lei 8.212/91 responsabiliza o titular do cartório por descumprimento ou informação inexata, com penalidade do art. 92 e ação regressiva proposta pelo INSS. Essa responsabilização é tratada na categoria **Controle e responsabilização** (AGU/PFE), não como ator separado dentro de Sistemas e dados.

### Nota — INSS como suporte operacional do CRPS (Instância recursal)
O INSS fornece sistemas, infraestrutura, recursos humanos e conectividade ao CRPS. Aparece como nota nas células CRPS / Recurso, não como ator duplicado da categoria Decisão previdenciária.

### Nota — Morte presumida (Justiça Federal/JEF)
No caso de morte presumida, a Justiça Federal entra já no **Pré-requerimento** via decisão judicial — a pensão conta da decisão, não do registro cartorial. Essa trilha contorna a lógica Cartório→SIRC→INSS e deve ser tratada como rota paralela, não como variante da jornada ordinária.

### Nota — Estrutura interna do CRPS
O bloco CRPS compreende: Conselho Pleno + 4 Câmaras de Julgamento + 29 Juntas de Recursos, conforme Regimento Interno aprovado pela Portaria MPS nº 125/2026 (revoga a Portaria MTP nº 4.061/2022). Juntas e Câmaras agrupadas por papel idêntico na jornada (julgar recurso em instâncias progressivas); Conselho Pleno separado por papel distinto (uniformização de jurisprudência em tese e no caso concreto).

---

## Gargalos de veto alto — para aprofundamento em subgrupos

Os gargalos abaixo não aparecem na matriz (para não poluir a leitura) mas devem estar disponíveis como material de apoio para os subgrupos do workshop.

| Gargalo | Atores envolvidos | Momento crítico | Pergunta para o subgrupo |
|---|---|---|---|
| Óbito / dados civis inconsistentes | Cartório, SIRC, RFB, INSS | Pré-requerimento | Quem é dono da correção ponta a ponta do dado de óbito? |
| Morte presumida | Judiciário, dependente, INSS, AGU/PFE | Pré-requerimento / Judicial | O blueprint tem trilha separada para morte presumida? |
| Acesso digital | Gov.br, Meu INSS, 135, APS | Requerimento | O problema é autenticação, letramento digital ou regra previdenciária? |
| Divergência nível presencial gov.br | Gov.br, INSS, cidadão | Requerimento | A orientação ao cidadão está alinhada à página oficial ou a norma interna diferente? |
| Prova de união estável / dependência | Dependentes, INSS, CRPS, Justiça | Instrução | A exigência decorre de lacuna documental ou de baixa interoperabilidade? |
| Rateio e co-dependentes | Co-dependentes, INSS, CRPS, Justiça | Instrução / Recurso | Como o serviço comunica retenção/rateio sem gerar percepção de erro? |
| Prova de vida / manutenção | INSS, bancos, representante legal | Pagamento/manutenção | O banco é tratado como etapa do serviço ou como ator externo invisível? |
| Recurso administrativo | INSS, CRPS, Juntas, Câmaras, Conselho Pleno | Recurso | Quem é dono do caso após decisão favorável no CRPS? |
| Responsabilização e ressarcimento | INSS, AGU/PFE, cartório, MPF, PF, CGU | Controle | Qual regime jurídico de ressarcimento se aplica a cada tipo de dano? |

---

## Rastreabilidade

Este mapa foi produzido a partir de:
- **B_relatorio_assistente_v3.md** — pesquisa e auditoria de atores, fontes legais e gargalos
- **Sessão grill-me (2026-05-30)** — 17 perguntas, todas respondidas; estrutura e atores decididos pelo usuário
- Divergência probatória registrada: nível gov.br para atendimento presencial (Bronze vs. Prata) — aguarda confirmação normativa antes de correção
