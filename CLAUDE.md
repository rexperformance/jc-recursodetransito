# JC Recursos de Multa de Trânsito — MazyOS

Esse workspace gerencia a operação digital da JC Recursos de Multa de Trânsito.
Tudo que o sistema gera — conteúdo, posts, propostas, materiais — parte daqui.

**Estrutura de pastas:**
- `_memoria/` — quem é a empresa, como fala, foco atual
- `identidade/` — marca aplicada em tudo que o sistema gera
- `marketing/` — campanhas, conteúdo, mídia paga
- `saidas/` — documentos e materiais pontuais gerados
- `dados/` — arquivos a analisar
- `scripts/` — automações e scripts de apoio

## Sobre a empresa

JC Recursos de Multa de Trânsito é uma consultoria e assessoria especializada em direito de trânsito.
Atua na defesa de motoristas e proprietários de veículos em casos de multas, suspensão e cassação de CNH, cancelamento de PPD e outros problemas relacionados a infrações de trânsito.
Operada por Joerberth Aguiar — Especialista em Segurança no Trânsito e Direito de Trânsito. Solo.
Localização: Rosário/MA. Tagline: "Sua Solução em Trânsito".

## O que mais fazemos aqui

- Criação e gestão de conteúdo para Instagram
- Otimização do Google Meu Negócio
- Materiais de comunicação (posts, carrosséis, propostas)
- Estruturação da presença digital do zero

## Tom de voz

Profissional, objetivo, direto. Linguagem acessível ao motorista comum — sem juridiquês.
Transmite autoridade e credibilidade sem arrogância.
Evitar: exagero emocional, emojis em excesso, termos jurídicos sem explicação, linguagem de guru.

## Regras do sistema

- Conteúdo de Instagram salvar em `marketing/instagram/`
- Materiais visuais e propostas salvar em `saidas/`
- Sempre consultar `identidade/design-guide.md` antes de criar qualquer visual
- Sempre ler `_memoria/` antes de qualquer tarefa de comunicação

## Ferramentas conectadas

- [ ] Google Meu Negócio
- [ ] Instagram / Meta
- [ ] Site institucional
- [ ] Google Ads
- [ ] Meta Ads

*(Marcar conforme for instalando os MCPs e acessos)*

---

## Contexto do negócio

No início de toda conversa, ler os seguintes arquivos (quando existirem e estiverem preenchidos):

1. `_memoria/empresa.md` — quem é o cliente, o que faz, como funciona o negócio
2. `_memoria/preferencias.md` — tom de voz, estilo de escrita, o que evitar
3. `_memoria/estrategia.md` — foco atual, prioridades, próximos passos

Usar essas informações como base pra qualquer resposta ou decisão. Não é necessário listar o que foi lido. Apenas usar o contexto naturalmente.

Pra qualquer tarefa visual (carrossel, post, landing page), consultar `identidade/design-guide.md` como referência de estilo.

---

## Fluxo de trabalho

Antes de executar qualquer tarefa, verificar se existe skill relevante em `.claude/skills/`. Se encontrar, seguir as instruções da skill. Se não encontrar, executar a tarefa normalmente.

Ao concluir uma tarefa que não tinha skill mas parece repetível, perguntar:
> "Isso pode virar uma skill pra próxima vez. Quer que eu crie?"

---

## Aprender com correções

Quando o usuário corrigir algo ou dar instrução permanente, perguntar:
> "Quer que eu salve isso pra não precisar repetir?"

Se sim, salvar no arquivo correspondente:
- Sobre o negócio → `_memoria/empresa.md`
- Sobre preferências e estilo → `_memoria/preferencias.md`
- Sobre prioridades e foco → `_memoria/estrategia.md`
- Regra de comportamento → `CLAUDE.md`

---

## Criação de skills

Quando o usuário pedir skill nova:
1. Verificar se existe template relevante em `templates/skills/`
2. Perguntar se é específica desse projeto ou útil em qualquer contexto
3. Ler `_memoria/` pra calibrar o conteúdo ao contexto do negócio
4. Seguir o fluxo da skill-creator nativa do Claude Code
