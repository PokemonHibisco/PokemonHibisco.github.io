---
title: Guía de Showdown
layout: default
permalink: /guias/showdown/
---
# Guía de Showdown

## Creación de cuenta

Bla bla ya hago esto luego

## Creación de equipo

En la pantalla de home selecciona la opción Teambuilder para abrir el menú de creación y edición de equipos.

<p class="center">
    <img src="/assets/img/showdown/1.png">
</p>

Selecciona la opción de New Team.

<p class="center">
    <img src="/assets/img/showdown/2.png">
</p>

Nombra tu equipo si quieres y en formato, escoge `[Gen 9] National Dex AG`. A continuación selecciona Add Pokémon.

<p class="center">
    <img src="/assets/img/showdown/3.png">
</p>

Ve rellenando la información de tu pokémon. **¡RECUERDA CAMBIAR EL NIVEL!** Para saber qué movimientos puede aprender tu pokémon a su nivel, puedes verlos en [Serebii](https://www.serebii.net/pokedex-sv/bulbasaur/#attacks) (por ejemplo, un Bulbasaur nivel 5 sabrá Tackle, Growl, y Vine Whip sin necesidad de TMs o tutores de movimientos). Deja el Tera Type por defecto.

<p class="center">
    <img src="/assets/img/showdown/4.png">
</p>

Para pelear no vamos a usar EVs, pero Showdown no deja verificar pokémons que tengan 0 EVs. Para solucionar esto, pon exactamente 1 EV en cualquier estadística. Esto es solamente para que Showdown sepa que no estás usando EVs a propósito y **no afectará las estadísticas del pokémon**. Para los IVs, déjalos en 31.

<p class="center">
    <img src="/assets/img/showdown/5.png">
</p>

Vuelve a la vista del equipo entero y selecciona Validate. Si todo está correcto saldrá este popup diciendo que tu equipo es válido.

<p class="center">
    <img src="/assets/img/showdown/6.png">
</p>

***

## Retar a un usuario en combate

En la pestaña de home selecciona Find a user.

<p class="center">
    <img src="/assets/img/showdown/7.png">
</p>

Escribe el nombre del usuario al que quieras retar. Saldrá una ventana con opciones. Selecciona Chat. Es importante que selecciones Chat y no Challenge.

<p class="center">
    <img src="/assets/img/showdown/8.png">
</p>

Una vez en el chat, escribe el siguiente comando:

<div class="copy language-plaintext highlighter-rouge"><div class="highlight"><pre class="highlight"><code>/challenge gen9nationaldexag@@@Dynamax Clause,Terastal Clause,!! EV Limit = 0
</code></pre></div></div>

<p class="center">
    <img src="/assets/img/showdown/9.png">
</p>

Esto creará una propuesta de combate al usuario con nuestras reglas personalizadas. Selecciona tu equipo y dale a Challenge una vez estés listo.

<p class="center">
    <img src="/assets/img/showdown/10.png">
</p>

Aparecerá una solicitud de combate en la pestaña Home del otro usuario. Una vez acepte la propuesta, comenzará el combate.

<p class="center">
    <img src="/assets/img/showdown/11.png">
</p>

Una vez termine el combate **NO CIERRES LA PESTAÑA**. Envía el siguiente comando en el chat:

<div class="copy language-plaintext highlighter-rouge"><div class="highlight"><pre class="highlight"><code>!showteam
</code></pre></div></div>

Y selecciona Download replay y Upload and share replay. Esto generará un archivo html y un enlace a la repetición del combate, debes mandar ambos al canal <a class="discord" href="/">#inserte-canal</a>. Una vez hecho esto, ya puedes cerrar la pestaña del combate si quieres.

<p class="center">
    <img src="/assets/img/showdown/12.png">
</p>

Una vez que un moderador verifique el combate, podrás añadir tu recompensa de (insertar recompensa).

- Si en un combate hay al menos un usuario que no realiza el comando `!showteam`, se considerará inválido automáticamente y no se podrá cobrar la recompensa.
- Si hay discrepancias en los datos de los pokémon (nivel incorrecto, movimientos incorrectos, etc) el combate se considerará inválido y no se podrá cobrar la recompensa. 
- Realizar combates inválidos continuamente puede resultar en sanción y el ser vetado completamente de realizar combates de Showdown en el grupo.
