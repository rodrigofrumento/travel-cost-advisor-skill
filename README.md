# Consultor de Viagem Econômica — Skill para Claude

Skill que transforma o Claude num consultor de viagens focado no **custo total real**. Em vez de você preencher um prompt cheio de colchetes, ela **te entrevista**, monta o briefing e só depois faz a análise.

## O que ela faz

1. Datas mais baratas
2. Aeroportos e rotas alternativas
3. Conexões por conta própria / multi-cidades
4. Auditoria de oferta de voo (nota de 1 a 10)
5. Taxas e custos ocultos
6. Escolha de bairro
7. Comparação de hospedagem
8. Redução do custo total
9. Decisão: reservar agora, esperar ou mudar de plano
10. Planejamento do zero (encadeia os modos acima)

## Como funciona

1. Você diz o que precisa (ou escolhe no menu).
2. Ela pergunta o essencial, no máximo 3 perguntas por rodada.
3. Mostra um briefing reutilizável e pede confirmação.
4. Faz a análise com busca na web e cita as fontes.

## Princípios

- Não inventa preço nem histórico de tarifa: busca, cita a fonte ou diz onde conferir.
- Previsão de preço é tratada como probabilidade, não certeza.
- Hidden city ticketing só aparece se você pedir, e sempre com os riscos.
- Sem metas arbitrárias de economia: mostra o que dá para economizar e o que você sacrifica.

## Instalação

**Claude.ai / app:** em Configurações → Capacidades → Skills, baixe este repositório, compacte a pasta `consultor-viagem-economica` em .zip e faça o upload.

**Claude Code:** copie a pasta para `~/.claude/skills/` (uso pessoal) ou `.claude/skills/` dentro do projeto.

## Exemplo de uso

> "Quero ir de São Paulo a Lisboa em março, ainda não sei as datas."

A skill identifica o modo "datas" (ou sugere "planejar do zero") e começa a entrevista.

## Licença

MIT
