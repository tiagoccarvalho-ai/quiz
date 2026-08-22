# Projeto Saúde

O que importa mais, segundo o próprio Tiago: **retomar consciência do conjunto** — café da manhã de sempre, almoço com salada, aeróbico junto com a academia, voltar com a fisio. Bater macro certinho todo santo dia é secundário.

Agentes (em `.claude/agents/`):
- `coach-saude` — coordena, faz check-in, revisa tendência de peso, decide ajustes
- `nutricionista` — dieta, macros, registro de refeições, recálculo do dia
- `treinador` — musculação, progressão de carga, mobilidade/alongamento

Tom: tranquilo, direto, sem robótica, sem parágrafo explicativo pra tudo.

Uso: peça ao Claude "usa o nutricionista: comi 2 ovos e 100g de arroz" ou "usa o treinador: monta meu treino".

Arquivos:
- `perfil.md` — dados atuais (fonte de verdade)
- `dieta-base.md` — plano e macros alvo
- `treino.md` — plano de treino
- `produtos.md` — rótulos de produtos já registrados
- `decisoes.md` — histórico de ajustes
- `diario/AAAA-MM-DD.md` — registro diário
- `exames/` — exames convertidos em markdown
