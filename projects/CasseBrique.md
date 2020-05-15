---
layout: project
type: project
link: /CasseBrique
image: ../images/casse-brique/jeu.png
images:
- ../images/casse-brique/jeu.png
title: "Casse Brique"
date: 2020-05-15
labels:
- JavaScript
summary: Projet réalisé pour le expérimenter le JavaScript.
---

# Résumé

Ce jeu a été réalisé dans le cadre personnel afin d'apprendre à utiliser le langage JavaScript.  
Il a été réalisé grâce au tutoriel disponible [ici](https://developer.mozilla.org/en-US/docs/Games/Tutorials/2D_Breakout_game_pure_JavaScript)

<canvas id="myCanvas" width="480" height="320"></canvas>

<div class="ui grid">
  <div style="margin: 0 auto; margin-top: 1em; margin-bottom: 1em">
    <div class="ui button" onclick="draw()" style="margin-top: 1em">Jouer</div>
  </div>
</div>

<script type="text/javascript" src="{{ site.url }}/js/casse-brique.js"></script>
