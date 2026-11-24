# Jogos da Semana da Segurança da Informação 2026 — Grupo Delga

Site estático (GitHub Pages) + ranking numa planilha Google (Apps Script).

| Arquivo | Para quê |
| --- | --- |
| `index.html` | Os 4 jogos, ranking e área restrita |
| `config.js` | Endereço da API do ranking (URL `/exec` do Apps Script) |
| `Code.gs` | Código da API — vai no Apps Script da planilha, **não** no GitHub |

Área restrita: Ranking → 🔒 Indicadores → senha. A senha é conferida só no Apps Script.
