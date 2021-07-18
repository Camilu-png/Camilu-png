# Hola 🤓
Soy Camilú y actualmente estoy trabajando en [Ulimac](https://camilu-png.github.io/portafolio.html), aunque igualmente sientete cómodo de ver mis repositorios. 
Quién sabe, tal vez encuentres algo bueno por ahí.

## Estudios
Estoy aprendiendo desarrollo web por lo que podrás encontrar GitHub Pages por aquí 👀<br>
Aunque también estoy estudiando Ingeniería Informática, por lo que encontrarte un repositorio de mis tareas no es tan descabellado
## Encuéntrame

Puedes encontrarme en mis redes sociales, como [Instagram](https://www.instagram.com/camilu_png/), [Twitter](https://twitter.com/camilu_png) y [Facebook](https://www.facebook.com/camila.arancibia.98096/)

![Twitter Follow](https://img.shields.io/twitter/follow/camilu_png?label=Camil%C3%BA%20%E2%9D%A4&style=social)
<!--
**Camilu-png/Camilu-png** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

<!--START_SECTION:waka-->
name: Waka Readme

on:
  schedule:
    # Runs at 12am IST
    - cron: '30 18 * * *'
  workflow_dispatch:
jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: anmol098/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
          GH_TOKEN: ${{ secrets.GH_TOKEN }}

<!--END_SECTION:waka-->
