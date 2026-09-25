# Congrega OS - skills adaptadas

Skills da Congrega Auditores e Consultores inspiradas na arquitetura dos agentes
deste repositório (escopo de acionamento, entrevista mínima, entregável
obrigatório, anti-padrões, escalonamento e autoverificação), reescritas para a
legislação e as normas brasileiras. Nenhum texto dos agentes originais foi
reaproveitado; apenas a estrutura.

| Skill | Pasta | Uso |
|---|---|---|
| Fluxo de caixa 13 semanas | `skills/fluxo-caixa-13-semanas/` | Projeção pelo método direto, cenários, semana de perigo, capital de giro e plano de ação |

## Instalação

- **Claude.ai (skills da organização):** compacte a pasta da skill (por exemplo
  `fluxo-caixa-13-semanas/`, com o `SKILL.md` na raiz do zip) e envie em
  Configurações > Capacidades > Skills.
- **Claude Code:** copie a pasta para `.claude/skills/` do projeto ou para
  `~/.claude/skills/`.

## Teste rápido

```bash
cd congrega-os/skills/fluxo-caixa-13-semanas
pip install openpyxl   # opcional, para gerar o .xlsx
python3 scripts/projecao_13_semanas.py modelos/premissas_exemplo.json --saida /tmp
```
