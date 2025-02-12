---
title: Son
publishDate: 2019-12-01 00:00:00
img: /assets/stock-2.jpg
img_alt: ''
description: |
  Dans ce projet, je créée un outil permettant de transformer le son brut d'une guitare en source de synthétiseur.
tags:
  - Traitement du signal
  - Musique
  - Programmation
---



# INTERPRÉTATION DU SON

Il faut être capable de récupérer du son (via une carte son par exemple), le modifier en temps réel, puis le renvoyer dans la carte son pour le retranscrire en signal analogique. 

Il faudra faire en C/C++, c’est bien plus rapide que le Python (même si je maîtrise mieux le Python que le C, et je ne connais pas du tout le C++).

La librairie PortAudio en C permet de faire du traitement du son en temps réel.

https://www.portaudio.com/

https://www.portaudio.com/docs/v19-doxydocs/tutorial_start.html

*Avec une arduino ou une raspberry ?*

Avantages arduino : plus petit et plus “simple” pour l’implémentation

Avantages Raspberry : beaucoup plus simple a manipuler vu que c’est un ordi. Mais ça rajoute des couches de complexité. Beaucoup plus puissant.

Je vais utiliser une raspberry, c’est bien plus adéquat. Genre une raspberry Pi 4

https://www.raspberrypi.com/products/raspberry-pi-3-model-b/

https://yadom.fr/raspberry-pi-4-model-b-2gb.html

https://www.thomann.de/fr/behringer_ucontrol_uca_222.htm?gad_source=1&gbraid=0AAAAADuDMCV-tQsNWB7pDnBc8Jj6FzGSu&gclid=CjwKCAiA3Na5BhAZEiwAzrfagFzh6JA-dyCXAcYuwwVUpqjehHZCmneGUKU87HxYIQ3WCEQNIpCZdBoC2HEQAvD_BwE

En gros environs 50€.

---

Vidéo qui explique en détails comment configurer PortAudio sur Raspberry :

[https://www.youtube.com/watch?v=JUYDcAIWQ7w](https://www.youtube.com/watch?v=JUYDcAIWQ7w)

Blog pour apprendre à se servir du Raspberry en 30j :

[Maîtrisez Raspberry Pi en 30 jours](https://raspberrytips.fr/maitrisez-raspberry-pi-en-30-jours/?coupon=IP21MP)

---

Une autre piste à explorer : 

Elk OS, une distributon de Linux faite exprès pour le traitement du son en temps réel. 

https://elk-audio.github.io/elk-docs/html/intro/run_elk_on_boards.html