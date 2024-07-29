---
layout: ../layouts/BlogPost.astro
title: Polyfill.io
slug: polyfill-io
description: 'Au secours, mon site web est contaminé !'
cover: /assets/PUBLI6.jpg
altCover: 'Texte "Polyfill.io victime d''une attaque : + de 100 000 sites impactés"'
tags:
  - serveur
  - actualite
  - cloud
added: 2024-07-03T22:00:00.000Z
---

Au secours, mon site web est contaminé ! 😱

Enfin, c’est ce qui aurait pu m’arriver sans un bon suivi des dépendances logicielles.

Polyfill.io, un outil couramment utilisé par les sites internet pour être compatible avec d’anciens navigateurs, a été victime d’une “supply-chain attack” la semaine dernière. En effet, son nom de domaine a été récupéré par un acteur malveillant, et au lieu d’exécuter le code nécessaire au bon fonctionnement du site, un code malveillant peut être utilisé.

Si vos sites utilisent cette dépendance, il est conseillé de l’enlever de toute urgence, ou de la remplacer par une version non impactée (voir lien ci-dessous).

Si vous utilisez Cloudflare, il est même possible que votre problème ai été temporairement réglé : leurs services redirigent désormais automatiquement vers une version sécurisée.

Vous pensez être concernés, ou vous voulez être protégés contre ces attaques ? Contactez-moi !

Informations supplémentaires : [https://polykill.io/](https://polykill.io/) ; [https://sansec.io/research/polyfill-supply-chain-attack](https://sansec.io/research/polyfill-supply-chain-attack)
Versions sécurisées : [https://polyfill-fastly.io/](https://polyfill-fastly.io/) 
Article Cloudflare : [https://blog.cloudflare.com/automatically-replacing-polyfill-io-links-with-cloudflares-mirror-for-a-safer-internet](https://blog.cloudflare.com/automatically-replacing-polyfill-io-links-with-cloudflares-mirror-for-a-safer-internet)
