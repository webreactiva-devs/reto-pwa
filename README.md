# Reto PWA

> Crea por fin una Progressive Web Application para acercar la experiencia móvil a la web

Bienvenid@ a un nuevo reto de programación de la comunidad malandriner de [webreactiva.com](https://webreactiva.com)

## 1. Motivación

Seguro que llevas tiempo pensando en crear una PWA, probar las funcionalidades que trae, deslumbrar al mundo con tu invento.

Lo que pasa es que nunca hay tiempo para dedicárselo a la creación de cosas nuevas. 

El tiempo te lo voy a “regalar” aquí con una motivación extra:

**Las nuevas siglas de la PWA**

Crea tu propia PWA para deslumbrar a la familia y los colegas: 

`Petándolo Wapamente Abuela`

![image](https://github.com/webreactiva-devs/reto-pwa/assets/1122071/80e7a0e6-601a-46a3-b0a6-372a13de8cef)

·

## 2. Propuesta

1. Cada participante resuelve el reto con las herramientas que prefiera siempre que no sea una herramienta final (Ej: un plugin de WordPress que te lo haga)  
	_Hay que picar algo de código, malandriners_
2. Cada semana se propondrá una nueva funcionalidad para la PWA.
3. El reto finaliza con un directo donde podremos ver las soluciones de los participantes el 15 de Junio (Jueves) a las 19:00 CEST.


### 🤔 Pero, entonces, ¿esto no es curso?

No.

Puedes seguir cualquier curso de Udemy y de YouTube para hacerlo.

Esta propuesta es diferente. Se trata de poner las **manos sobre el teclado** y seguir los pasos de la formación. 

O, mejor aún, adaptarlo a unos requisitos concretos.


### 🏆 Recompensa

Repartiremos puntos entre los participantes que darán acceso a más oportunidades para ganar una recompensa.

**¿Qué recompensa?**

Pronto lo sabrás ;) 


·


## 3. Objetivo final

1. Crear una PWA con características relacionadas con la reproducción de audio.
2. Las características completas no se desvelarán hasta el final del reto.
3. La idea es que sea una webapp con desarrollo incremental: cada semana incorporamos una nueva funcionalidad
4. El reto finaliza con un directo donde podremos ver las soluciones de los participantes el 15 de Junio (Jueves) a las 19:00 CEST


·


## 4. Cómo se participa

- Tu código tiene que estar subido en un repositorio de Github o Gitlab de forma pública
- [Envía tus soluciones con las issues de este proyecto](https://github.com/webreactiva-devs/reto-pwa/issues) indicando cuál es tu solución, contando tus dificultades y enlazando la solución final


·

# Contiendas


## ⚔️ Primera contienda: Manifiesto!

Quieres crear una PWA para escuchar audio y que tu abuela, que está enganchadísima a redes, tenga en el móvil algo parecido a una radio.

Este es el mockup de la webapp:

![image](https://github.com/webreactiva-devs/reto-pwa/assets/1122071/be303bed-12ef-496b-8864-6788065d5692)



1. Un botón para reproducir audio (y detenerlo)
2. Un selector del audio que puede escuchar.

El planteamiento de requisitos mínimos para la primera semana es:


### Requisitos funcionales
1. La web tiene que reproducir un fichero de audio. Por ejemplo [este](https://api.spreaker.com/v2/episodes/48338128/download.mp3)
2. Basta con que reproduzca el audio con la etiqueta estándar de HTML
3. No es necesario que tenga estilos ni que sea bonita en este punto

### Requisitos PWA
1. Tienes que dar un nombre a tu PWA
2. Debes permitir que la webapp sea instalable en un dispositivo móvil 
3. El requisito anterior hará que tengas que cumplir otros (manifest.json, miniaturas…)
4. Se valorará positivamente tener un manifest.json lo más completo posible y una “splash screen”



### 🥶 Recomendaciones de Supercoco

¡NO TE LÍES!

No hace falta (de momento) que haya caché offline, ni notificaciones, ni reproducción en segundo plano, ni selector de audios…

Ya ampliaremos las funcionalidades de la webapp en las siguientes semanas.

👉 Usa la tecnología que ya sepas manejar o la que quieras aprender.

Te dejo unos recursos para que puedas empezar  a investigar:

- [Cómo construir una PWA desde cero con HTML, CSS y JavaScript](https://www.freecodecamp.org/espanol/news/como-construir-una-pwa-desde-cero-con-html-css-y-javascript/)
- [Learn PWA](https://web.dev/learn/pwa/)
- [Get started with Progressive Web Apps](https://learn.microsoft.com/en-us/microsoft-edge/progressive-web-apps-chromium/how-to/)
- [Cómo agregar un manifiesto en la aplicación web](https://web.dev/i18n/es/add-manifest)
- [Vite PWA](https://vite-pwa-org.netlify.app/)
- [WR 27: Convierte tu web en una PWA](https://www.webreactiva.com/podcast/web-en-pwa)


### Puntos

Los participantes que entreguen la solución antes del 1 de Junio a las 19:00 CEST ganan 20 puntos.

Si entregas más tarde, antes del final, 10 puntos.



## Segunda contienda: Service Worker!

Tampoco es que tu abuela viva en una cueva o en mitad de la nada, pero no es el lugar con mejor cobertura del mundo.

Te dice que muchas veces estaba escuchando algo y luego “como que se va la conexión”.

Tu PWA necesita una mejora cuanto antes: ¡qué funcione en modo offline!

### Requisitos

1. Debes incorporar un Service Worker en tu PWA
2. El Service Worker debe registrarse correctamente
3. Hay que incluir un sistema de caché que sea capaz de almacenar los ficheros estáticos de la web: HTML, CSS, JS y, por supuesto, los audios
4. La web debe poder cargarse en modo offline una vez haya sido cargada previamente.

**Extra**

- ¿Podría tu PWA guardar el estado de reproducción del audio? Por ejemplo, el audio seleccionado o el segundo en el que se estaba reproduciendo.

### 🥶 Recomendaciones de Supercoco

Algunos recursos que pueden serte de ayuda:

- [WRP 247. Cómo empezar y deslumbrar con las PWA](https://www.webreactiva.com/audios/como-empezar-deslumbrar-pwa)
- Learn PWA: [Service Workers](https://web.dev/learn/pwa/service-workers/), [Caching](https://web.dev/learn/pwa/caching/)
- [Hacer que las PWAs trabajen desconectadas con servicio workers](https://developer.mozilla.org/es/docs/Web/Progressive_web_apps/Tutorials/js13kGames/Offline_Service_workers) {[EN](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps/Tutorials/js13kGames/Offline_Service_workers)}
- [Make Progressive Web Apps Work Offline](https://dev.to/azure/05-make-progressive-web-apps-work-offline-fil)



### Puntos

Los participantes que entreguen la solución antes del 8 de Junio a las 23:59  ganan 20 puntos.

Si entregas más tarde, antes del final, 10 puntos.



## Tercera contienda: Pantalla Bloqueada!

Si algo hay que tu abuela no soporte de YouTube es que no se pueda escuchar en pantalla bloqueda (salvo que pases por caja).

¡Es tu gran momento!

### Requisitos

- El audio tiene que ser resproducible con la pantalla bloqueada del movil
- Tiene que verse, en pantalla bloqueada, la información de lo que está escuchándose: nombre, carátula
- Tu abuela tiene cosas que hacer: Añade (en pantalla normal, no es necesario que esté bloqueada) la opción de escuchar el audio a 2x (doble velocidad)

**Extra**

- ¿Podría tu PWA guardar el estado de reproducción del audio? Por ejemplo, el audio seleccionado o el segundo en el que se estaba reproduciendo.

Ya, ya, es el mismo del reto anterior, pero que sepas que tienes 10 puntos más ;)

### Puntos

Los participantes que entreguen la solución antes del 15 de Junio a las 19:00  ganan 10 puntos.

Si presentas tu solución en la final del 15 de Junio ganarás 20 puntazos más.

¡A por ello!
