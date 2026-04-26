<div align="center">

<img src="https://capsule-render.vercel.app/api?type=cylinder&color=0:020c1b,40:0a3d62,100:020c1b&height=220&section=header&text=Jhonatam%20Kauã&fontSize=55&fontColor=00ffe0&desc=✦%20Analista%20de%20Dados%20✦&descSize=22&descFontColor=7fdbca&animation=blinking&fontAlignY=45&descAlignY=68" />

</div>

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=20&duration=2800&pause=800&color=00FFE0&center=true&vCenter=true&width=700&height=55&lines=%F0%9F%93%8A+Dados+brutos+entram.+Decis%C3%B5es+estrat%C3%A9gicas+saem.;%F0%9F%90%8D+Python+%7C+%F0%9F%97%84%EF%B8%8F+SQL+%7C+%F0%9F%93%97+Excel+%7C+%E2%98%81%EF%B8%8F+AWS;%F0%9F%94%8D+Explorando+padr%C3%B5es+que+o+olho+humano+n%C3%A3o+v%C3%AA;%F0%9F%9A%80+Portf%C3%B3lio+em+constru%C3%A7%C3%A3o+%E2%80%94+open+to+work" />

</div>

---

<div align="center">

```
╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║   SELECT name, role, status FROM analysts                    ║
║   WHERE passion = 'dados' AND location = 'Brasil'            ║
║   AND open_to_work = TRUE;                                   ║
║                                                              ║
║   ──────────────────────────────────────────────────         ║
║   name    │ Jhonatam Kauã Silva Alves                        ║
║   role    │ Analista de Dados                                ║
║   focus   │ ETL · Análise · Visualização · Cloud            ║
║   stack   │ Python · MySQL · Excel · AWS                     ║
║   status  │ ✅ Open to Work                                  ║
╚══════════════════════════════════════════════════════════════╝
```

</div>

---

## 〔 01 〕 Quem sou eu

<img align="right" width="340" src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" />

```python
class JhonatamKaua:

    def __init__(self):
        self.role     = "Analista de Dados"
        self.location = "Brasil 🇧🇷"
        self.stack    = ["Python", "MySQL", "Excel", "AWS"]
        self.foco     = [
            "Análise Exploratória (EDA)",
            "Pipelines ETL",
            "Visualização de Dados",
            "Cloud com AWS"
        ]
        self.objetivo = "Transformar dados em decisões"
        self.status   = "🚀 Open to Work"

    def trabalho(self):
        while True:
            dado = coletar()
            insight = analisar(dado)
            decisao = visualizar(insight)
            entregar(decisao)  # sempre
```

<br clear="right"/>

---

## 〔 02 〕 Arsenal Técnico

<div align="center">

| 🐍 Análise & Python | 🗄️ Banco de Dados | ☁️ Cloud AWS | 📊 Visualização | 🔧 DevOps & Tools |
|:---:|:---:|:---:|:---:|:---:|
| Python | MySQL | S3 | Excel Avançado | Git & GitHub |
| Pandas | PostgreSQL | Glue | Power BI | Docker |
| NumPy | SQL Avançado | Athena | Matplotlib | Linux |
| Jupyter | Modelagem | EC2 | Seaborn | VS Code |

</div>

<div align="center">

<img src="https://skillicons.dev/icons?i=python,mysql,aws,docker,git,linux,github,vscode&theme=dark&perline=8" />

</div>

---

## 〔 03 〕 Projetos em Destaque

<div align="center">

| Projeto | Descrição | Stack |
|---|---|---|
| 🔷 **[Gitlytic](https://github.com/jktremdev)** | Analisa perfis do GitHub em tempo real — linguagens mais usadas, repos populares, estrelas e ranking global | `Python` `API REST` `Data Viz` |
| 📊 **Em breve...** | Pipeline ETL com Python + MySQL + AWS | `Python` `MySQL` `AWS Glue` |
| 📈 **Em breve...** | Dashboard interativo de análise de dados | `Python` `Excel` `Power BI` |

</div>

---

## 〔 04 〕 GitHub em Números

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=jktremdev&show_icons=true&hide_border=true&bg_color=020c1b&title_color=00ffe0&icon_color=00ffe0&text_color=7fdbca&ring_color=00ffe0" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jktremdev&layout=compact&hide_border=true&bg_color=020c1b&title_color=00ffe0&text_color=7fdbca&langs_count=6" />

</div>

<div align="center">

<img width="70%" src="https://github-readme-streak-stats.herokuapp.com/?user=jktremdev&hide_border=true&background=020c1b&ring=00ffe0&fire=00d4aa&currStreakLabel=00ffe0&sideLabels=7fdbca&dates=7fdbca&stroke=0a3d62" />

</div>

---

## 〔 05 〕 Atividade — Jogo da Cobrinha 🐍

> _Cada quadradinho verde é uma contribuição devorada pela cobra._

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/jktremdev/jktremdev/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/jktremdev/jktremdev/output/github-contribution-grid-snake.svg" />
  <img alt="snake eating contributions" src="https://raw.githubusercontent.com/jktremdev/jktremdev/output/github-contribution-grid-snake-dark.svg" />
</picture>

</div>

<details>
<summary>⚙️ <b>Como ativar a cobra no seu perfil — clique aqui</b></summary>

<br/>

Crie o arquivo `.github/workflows/snake.yml` no repositório `jktremdev/jktremdev`:

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest
    timeout-minutes: 10

    steps:
      - name: Generate snake
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: Push to output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

Depois vá em **Settings → Actions → General → Workflow permissions** e marque **Read and write permissions**. Rode o workflow manualmente na primeira vez e a cobra aparecerá! 🐍

</details>

---

## 〔 06 〕 Objetivo

<div align="center">

```
┌─────────────────────────────────────────────────────────────┐
│                                                             │
│   Atuar como Analista de Dados, construindo pipelines,      │
│   extraindo insights e apoiando decisões estratégicas       │
│   com Python, SQL, Excel e AWS.                             │
│                                                             │
│   Cada dataset é um problema esperando uma solução.         │
│   Eu sou quem encontra ela.                                 │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

</div>

---

## 〔 07 〕 Me encontre aqui

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-020c1b?style=for-the-badge&logo=linkedin&logoColor=00ffe0&labelColor=020c1b)](https://www.linkedin.com/in/jhonatam-kau%C3%A3-a7aa55259/)
[![GitHub](https://img.shields.io/badge/GitHub-020c1b?style=for-the-badge&logo=github&logoColor=00ffe0&labelColor=020c1b)](https://github.com/jktremdev)

</div>

---

<div align="center">

<img src="https://komarev.com/ghpvc/?username=jktremdev&style=for-the-badge&color=020c1b&label=VISITAS+AO+PERFIL&labelColor=0a3d62" />

</div>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=cylinder&color=0:020c1b,40:0a3d62,100:020c1b&height=140&section=footer&text=Data%20is%20the%20new%20oil%20%E2%80%94%20let%27s%20refine%20it.&fontSize=18&fontColor=00ffe0&animation=blinking" />

</div>
