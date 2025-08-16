---
layout: post
title: Así estoy usando Claude Code
subtitle: Mi flujo de trabajo para usar Claude Code
share-img: /assets/img/avatar.jpeg
tags: [desarrollo, simple]
---

La IA nos está cambiando la forma de trabajar como devs todo el tiempo. Al principio solo la usábamos para hacerle preguntas, después empezó a asistirnos en el IDE con autocompletado y hoy puede llegar a escribir la implementación de features completas. En un futuro quizás nos reemplace, pero todavía estamos lejos de eso :).

Todavía no estamos en el punto de delegar todo nuestro trabajo en una IA, pero sí se volvió una ayuda enorme. Es casi como tener a otro dev al lado, acompañándonos en el proceso, en una especie de pair programming.

En estos meses probé distintas herramientas y desde hace un tiempo encontré en Claude Code un gran aliado. Tenerlo en la terminal me parece un golazo y la forma de interactuar me resulta muy natural. Con el tiempo fui cambiando cómo lo uso, y hoy te quiero contar mi proceso actual.

### Mi flujo de trabajo con IA
1. Armo un documento en markdown con requerimientos y detalles técnicos.
2. Paso ese documento por la IA para pulirlo.
3. Le pido a Claude Code un plan de trabajo.
4. Avanzo con aceptación manual de los cambios.

### Cómo llegué a este método
Al principio chateaba directamente con Claude Code desde la consola. Eso funcionaba, pero no era muy eficiente: daba muchas vueltas y sentía que no estaba exprimiendo la herramienta.

Hoy hago algo distinto. Primero escribo un documento en markdown con todo el contexto, lo que quiero lograr, reglas de dominio, cambios en la BD, objetos y abstracciones que quiero armar. Suelo agregar bastante detalle, aunque a veces le dejo libertad a Claude para proponer.

Con ese documento escrito, lo paso por Claude.ai o ChatGPT y les pido que me hagan preguntas técnicas y no técnicas para descubrir huecos. Luego les pido que integren esas respuestas en el documento. Este paso fue un cambio enorme: me obliga a aclarar cosas que antes me olvidaba y me deja un plan mucho más sólido.

Cuando el documento está listo, se lo paso a Claude Code en **modo “plan”**. Itero hasta que la propuesta me convence y recién ahí le pido que ejecute los cambios, siempre con revisión manual. **Nunca uso auto-accept**, prefiero ver cada cambio y decidir si quiero aplicarlo o no.

Algunas veces acepto cambios aunque no me cierren del todo, los **anoto en papel** para ajustarlos después, haciendo un refactoring o acomodando alguna cuestión que no me gusta. Otras veces, al ver la implementación, cambio de idea y pido otro enfoque. Esto no es nada raro ya que también me pasaba cuando programaba sin IA. Indudablemente soy de los que necesita ver la solución para darse cuenta si realmente es lo que quiero.

### Lo que descubrí
El proceso es simple, pero me cambió por completo la forma de trabajar. No solo ayuda a que Claude entienda mejor lo que quiero hacer, también me obliga a mí a pensar más. Escribir el documento me ordena, me hace tomar decisiones y no delegar todo en la IA.

En definitiva, descubrí que escribir primero y usar la IA como copiloto después es la clave.
