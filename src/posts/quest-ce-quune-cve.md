---
layout: ../layouts/BlogPost.astro
title: Qu’est ce qu’une CVE ?
slug: quest-ce-quune-cve
description: Définition
cover: /assets/public/assets/PUBLI13.png
altCover: Texte reprenant la définition de l'article
tags:
  - windows
  - linux
added: 2024-08-28T22:00:00.000Z
---

Qu’est ce qu’une CVE ? 🤔

Vous avez déjà peut-être lu cet acronyme utilisé pour parler d’une faille de sécurité. Il signifie “Common Vulnerabilities and Exposures”, soit littéralement Vulnérabilités et expositions communes.

💡Il s’agit d’une liste globale de vulnérabilités de cybersécurité connues : être accompagné pour associer ces vulnérabilités à l’état de votre système d’informations permet de renforcer votre cybersécurité.

Cette liste est composée d’entrées identifiées par un numéro unique au format CVE-Année-Nombre, comme par exemple la récente CVE-2024-38063 qui impacte Windows.

La liste est maintenue par l’organisme @MITRE aux États-Unis, et les entrées peuvent être ajoutées par différents organismes partenaires, appelés CNA (CVE Numbering Authorities, ou Autorités de Numérotation de CVE). C’est par exemple le cas de @Thalès en France.


Une CVE va comporter plusieurs éléments outre son identifiant. Je vous donne ici l’exemple de la CVE-2024-38063.

➡ Un titre descriptif, comme “Windows TCP/IP Remote Code Execution Vulnerability”

➡Un score basé sur le Common Vulnerability Scoring System (CVSS) qui prend en compte notamment sa criticité et sa complexité de mise en oeuvre. Le maximum est de 10.0. Dans notre exemple, le score est de 9.8, mettez à jour !

➡Des informations sur le produit et ses versions impactées. Plusieurs dans notre cas, y compris Microsoft Windows 11 Version 23H2 de la version 10.0.0 à la version 10.0.22631.4037 non inclue, qui contient le correctif.

➡Une CVE va souvent contenir un lien vers une source plus détaillée, qui permettra de mieux comprendre l’impact ou de mettre en place un correctif.


🔴 Pas le temps ou les compétences en interne ? Laisse-moi vous aider à assure le suivi des vulnérabilités de votre système d’informations !
