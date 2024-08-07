---
layout: ../layouts/BlogPost.astro
title: 'HTTPS : Êtes vous protégés ?'
slug: https-etes-vous-proteges
description: 'Ouf ! Ce site a bien un cadenas, je suis protégé... N’est-ce pas ?'
cover: /assets/PUBLI4.png
altCover: Image reprenant le titre et une image de navigateur web
tags:
  - actualite
  - crypto
  - serveur
added: 2024-06-19T22:00:00.000Z
---

Ouf ! Ce site a bien un cadenas, je suis protégé... N’est-ce pas ? 😨

Et bien… C’est plus compliqué que ça ! 🧐

Ce cadenas prouve uniquement que les échanges entre votre navigateur et le site internet sont chiffrés, et donc que personne ne peut les lire. Cependant, soyez sûrs d’être sur le bon site et pas victime d’une tentative de phishing !

🤔 Mais au fait, comment fonctionne cette protection ?

➡️ Le serveur qui fournit le site internet possède un certificat pour ce site, et votre navigateur vérifie que ce certificat est valide. Ensemble, ils s’en servent pour chiffrer leurs échanges.

➡️ Pour valider un certificat, votre navigateur vérifie entre autres ses dates de début et de fin de validité et le fait qu’il corresponde bien au site sur lequel vous vous trouvez.

➡️ Votre navigateur vérifie également l’autorité qui a émis ce certificat. Il ne connaît pas tous les certificats du monde, mais il en connaît quelques dizaines, utilisés pour générer les certificats des sites via une chaîne de certification. Par exemple, pour LinkedIn, le certificat de “www\.linkedin.com” est émis par “DigiCert SHA2 Secure Server CA” lui même émis par “DigiCert Global Root CA”. C’est ce dernier que votre navigateur connaît déjà !

Enfin, il est important de savoir que le certificat ne fait pas tout. Il permet d'utiliser le protocole HTTPS, mais ce dernier doit être configuré de manière sécurisée. De plus, vous n'êtes pas à l'abri de tentatives de phishing.

Vous voulez être sûrs de ne pas vous faire avoir par du phishing ou de sécuriser suffisamment l’accès à vos sites internet ? Contactez-moi directement !
