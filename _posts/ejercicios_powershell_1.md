---
layout: 1
title: Ejercicios de Powershell
---
## Sección
Proximámente...

# Antecedentes

Resulta que estaba yo tan tranquilo dispuesto a buscar a **Julio Ureña** en la plataforma de Chatroulette, cuando vi que para empezar a conectar con gente se me solicitaba la siguiente información:

<p align="center">
<img src="/assets/images/chatroulette-bypass/smile.jpg">
</p>

Al parecer debes de sonreir frente a la cámara para ya comenzar a usar el servicio. Esta fase me interesó mucho, ¿de qué forma se hace la validación?... es lo que mi mente inquieta se preguntaba.

Dado que `Burpsuite` siempre responde a estas preguntas, probé a tirar de nuestro querido proxy para ver cómo viajaban las consultas. Desde que presionas `Start`, empiezan a viajar una serie de WebSockets con valores que identifican entre otras cosas nuestro `UserToken`:

<p align="center">
<img src="/assets/images/chatroulette-bypass/burp-first.png">
</p>

COPIADO!!!!


