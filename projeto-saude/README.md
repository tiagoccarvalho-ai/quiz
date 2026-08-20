# Projeto Saúde

Agentes (em `.claude/agents/`):
- `coach-saude` — coordena, faz check-in, revisa tendência de peso, decide ajustes
- `nutricionista` — dieta, macros, registro de refeições, recálculo do dia
- `treinador` — musculação, progressão de carga, mobilidade/alongamento

Uso: peça ao Claude "usa o nutricionista: comi 2 ovos e 100g de arroz" ou "usa o treinador: monta meu treino".

Arquivos:
- `perfil.md` — dados atuais (fonte de verdade)
- `dieta-base.md` — plano e macros alvo (gerado pelo nutricionista)
- `treino.md` — plano de treino (gerado pelo treinador)
- `decisoes.md` — histórico de ajustes
- `diario/AAAA-MM-DD.md` — registro diário
- `exames/` — exames convertidos em markdown
