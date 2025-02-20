# Olá, eu sou Yuri Vasconcellos 👋

<p align="center">
  <img src="https://i.ibb.co/ZRtdjnh6/technology-banner.png" alt="technology-banner" style="max-width:100%; max-height:50%; border-radius:10px;" />
</p>

---

## Sobre Mim

Sou um desenvolvedor apaixonado por tecnologia e inovação, especializado em **engenharia de prompts**, **desenvolvimento full stack**, **automatização de processos** e **integração de IA**. Busco transformar desafios complexos em soluções escaláveis e eficientes, combinando conhecimento técnico e criatividade para criar produtos de alto impacto.

---

## Tecnologias & Habilidades

<div align="center">
  <img src="https://img.shields.io/badge/Python-%233776AB?style=for-the-badge&logo=python&logoColor=yellow" alt="Python" />
  <img src="https://img.shields.io/badge/Dart-%230175C2?style=for-the-badge&logo=dart&logoColor=white" alt="Dart" />
  <img src="https://img.shields.io/badge/Flutter-%2302569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter" />
  <img src="https://img.shields.io/badge/C%23-%23239120?style=for-the-badge&logo=c-sharp&logoColor=white" alt="C#" />
  <img src="https://img.shields.io/badge/React-%2361DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/Node.js-%23339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Docker-%232496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/PostgreSQL-%23336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/-Javascript-blue?style=for-the-badge&logo=javascript&logoColor=f5f5f5" alt="Javascript" />
</div>

---

## Projetos Destacados

<table align="center">
  <tr>
    <td align="center" valign="top">
      <a href="https://github.com/DevYuriTiago/LandingPagePromptEbook" target="_blank">
        <img src="https://via.placeholder.com/250?text=Projeto+1" alt="Projeto 1" style="border-radius:10px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);" />
      </a>
      <br>
      <b>Landing Page AI</b>
      <p>Plataforma interativa com IA para automação de processos.</p>
    </td>
    <td align="center" valign="top">
      <a href="https://github.com/seu_usuario/projeto2" target="_blank">
        <img src="https://via.placeholder.com/250?text=Projeto+2" alt="Projeto 2" style="border-radius:10px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);" />
      </a>
      <br>
      <b>Financial AI</b>
      <p>IA preditiva para análise de mercado financeiro.</p>
    </td>
  </tr>
</table>

---

## Estatísticas do GitHub

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=DevYuriTiago&show_icons=true&theme=tokyonight&count_private=true" alt="GitHub Stats" />
  <br>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=DevYuriTiago&layout=compact&theme=tokyonight" alt="Top Languages" />
</div>

---

## Automação & Integração

Utilizo **GitHub Actions** para manter este perfil atualizado automaticamente com dados em tempo real.

<details>
  <summary style="cursor: pointer; font-weight: bold;">Ver Workflow de Automação</summary>

```yaml
name: Atualizar README

on:
  schedule:
    - cron: '0 * * * *'  # Atualiza a cada hora
  workflow_dispatch:

jobs:
  update-readme:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout do Repositório
        uses: actions/checkout@v3
      - name: Atualizar Estatísticas
        run: |
          python update_readme.py
      - name: Commit e Push
        run: |
          git config --local user.name "github-actions[bot]"
          git config --local user.email "github-actions[bot]@users.noreply.github.com"
          git add README.md
          git commit -m "Atualização automática das estatísticas"
          git push
```
</details>

---

## Conecte-se Comigo

<div align="center" style="margin-top: 1rem;">
  <a href="mailto:seu.email@exemplo.com" target="_blank">
    <img src="https://img.icons8.com/color/48/000000/new-post.png" alt="Email" style="border-radius:50%;" />
  </a>
  <a href="https://linkedin.com/in/seu_perfil" target="_blank">
    <img src="https://img.icons8.com/color/48/000000/linkedin.png" alt="LinkedIn" style="border-radius:50%;" />
  </a>
  <a href="https://github.com/DevYuriTiago" target="_blank">
    <img src="https://img.icons8.com/color/48/000000/github.png" alt="GitHub" style="border-radius:50%;" />
  </a>
</div>

<p align="center">
  "Unindo tecnologia, paixão e inovação para construir o futuro." – *Yuri Vasconcellos*
</p>
