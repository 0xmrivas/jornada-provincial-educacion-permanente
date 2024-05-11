<!-- <h2 class="r-fit-text" style="text-align: center"> IA en el aula: Innovando la Educación del futuro </h2> -->

<img class="r-stretch" style="text-align: center" src="../assets/Cover_IES-las-banderas.png">
 
---

## La Inteligencia Artificial Generativa (IAG)

<img class="r-stretch" style="text-align: center" src="../assets/mod1-cover.png">


Generación y edición

Texto (LLM - Large Language Model) <!-- .element: class="fragment" -->

Audio <!-- .element: class="fragment" -->

Imagen → Vídeo <!-- .element: class="fragment" -->

3D <!-- .element: class="fragment" -->
---
## ¿Qué es un modelo?

<img class="r-stretch" style="text-align: center" src="../assets/modelo.png">


<img class="r-stretch" style="text-align: center" src="../assets/machinelearning.png">
---
## Propietarios o de libre acceso

Propietarios: Solamente pueden usarse a través de las vías que oferta la empresa propietaria (no puedes ejecutarlo en tu equipo) <!-- .element: class="fragment" -->

De libre acceso: Puedes ejecutarlo en tu equipo (si es lo suficientemente potente) o elegir a través de que vía usarlo <!-- .element: class="fragment" -->

¡Cuidado! Aunque un modelo sea de libre acceso, tiene una licencia asociada <!-- .element: class="fragment" -->
---
## Los Grandes Modelos del Lenguaje (LLM)

<img class="r-stretch" style="text-align: center" src="../assets/mod2-cover.png">
---
## Instruct Fine-Tuning

De completar texto a proporcionar respuestas <!-- .element: class="fragment" -->

Chatbot "inteligente" <!-- .element: class="fragment" -->

RLHF es uno de los métodos utilizados <!-- .element: class="fragment" -->


## Tipos de mensajes en un chatbot

User <!-- .element: class="fragment" -->

Assistant <!-- .element: class="fragment" -->

System <!-- .element: class="fragment" -->
---
## ¡Vamos a probarlo!

<img class="r-stretch" style="text-align: center" src="../assets/login-chatgpt/1.png">

<small>chat.openai.com</small>


<img class="r-stretch" style="text-align: center" src="../assets/login-chatgpt/2.png">


<img class="r-stretch" style="text-align: center" src="../assets/login-chatgpt/3.png">


<img class="r-stretch" style="text-align: center" src="../assets/login-chatgpt/4.png">


<img class="r-stretch" style="text-align: center" src="../assets/login-chatgpt/5.png">


<img class="r-stretch" style="text-align: center" src="../assets/login-chatgpt/6.png">


<img class="r-stretch" style="text-align: center" src="../assets/login-chatgpt/7.png">


<img class="r-stretch" style="text-align: center" src="../assets/login-chatgpt/8.png">


<img class="r-stretch" style="text-align: center" src="../assets/login-chatgpt/9.png">


<img class="r-stretch" style="text-align: center" src="../assets/login-chatgpt/10.png">

---
## ¿Cómo funciona realmente un modelo de lenguaje?

### Una aproximación técnica

<img class="r-stretch" style="text-align: center" src="../assets/seaofembeddings.png">

<small>Fuente: [Generative AI exists because of the transformer](https://ig.ft.com/generative-ai/)</small>


## Entrenamiento: Tokenización

<img class="r-stretch" style="text-align: center" src="../assets/technical01.png">

**We:** 7674	**go:** 7653	**to:** 66533	**work:** 8927


## Entrenamiento: Observación

<img class="r-stretch" style="text-align: center" src="../assets/technical02.png">


## Entrenamiento: Conteo de probabilidades

<img class="r-stretch" style="text-align: center" src="../assets/technical03.png">


## Entrenamiento: Embedding

<img class="r-stretch" style="text-align: center" src="../assets/technical04.png">


## Entrenamiento: Creación de embeddings

<img class="r-stretch" style="text-align: center" src="../assets/technical05.png">


## Entrenamiento: Distancia entre embeddings

<img class="r-stretch" style="text-align: center" src="../assets/technical06.png">


## Inferencia: Prompt de entrada

<img class="r-stretch" style="text-align: center" src="../assets/technical07.png">


## Inferencia: Varias posibilidades

<img class="r-stretch" style="text-align: center" src="../assets/technical08.png">


## Inferencia: Elección para completar

<img class="r-stretch" style="text-align: center" src="../assets/technical09.png">
---
## ¿Cómo funciona realmente un modelo de lenguaje?

### Una aproximación intuitiva


## La analogía del estudiante

<img class="r-stretch" style="text-align: center" src="../assets/student.png">


Fase de estudio (entrenamiento)

Una petición es un examen (no recuerda exámenes anteriores) <!-- .element: class="fragment" -->

Puede tratar de responder lo que no sabe (alucinaciones) <!-- .element: class="fragment" -->

Le puedes dar pistas en el enunciado (contexto), pero su longitud es limitada (número de tokens) <!-- .element: class="fragment" -->

Puede volver a la habitación y centrarse en un tema concreto (fine-tuning) <!-- .element: class="fragment" -->


## ¿Qué pasa si se le dan herramientas al estudiante?
---
## Parámetros más comunes de un LLM

<img class="r-stretch" style="text-align: center" src="../assets/config-llm.webp">


Tamaño: Medido en miles de millones de parámetros (B)

Contexto: Memoria a corto plazo (número máximo de tokens) <!-- .element: class="fragment" -->

Temperatura: Medida de la creatividad <!-- .element: class="fragment" -->

Funciones: Herramientas a las que tiene acceso <!-- .element: class="fragment" -->
---
## Diferentes chatbot

https://chat.openai.com

https://huggingface.co/chat

https://gemini.google.com

https://www.perplexity.ai
---
## ¿Cómo obtener las mejores respuestas de un LLM?

<img class="r-stretch" style="text-align: center" src="../assets/teach-robot.webp">


Prompt Engineering

Háblale como si fuera una persona (pero no lo es) <!-- .element: class="fragment" -->

Comprende su funcionamiento para comprender sus respuestas <!-- .element: class="fragment" -->

Sigue unos principios básicos <!-- .element: class="fragment" -->


## 1 - Escribe instrucciones claras y específicas

Proporciona información y usa delimitadores para indicar las distintas partes de tu petición <!-- .element: class="fragment" -->

Solicita respuestas estructuradas en el formato que necesites <!-- .element: class="fragment" -->

Proporciona ejemplos (few-shot) <!-- .element: class="fragment" -->


## 2 - Dale tiempo para "pensar"

Especifica los pasos para realizar la tarea <!-- .element: class="fragment" -->

Solicita que razone sobre los pasos que tendría que dar antes de proporcionar una respuesta <!-- .element: class="fragment" -->

"Respira hondo y resuelve este problema paso por paso" <!-- .element: class="fragment" -->


## 3 - Indica unas pautas de comportamiento

Instrucciones personalizadas: System <!-- .element: class="fragment" -->

¿Qué quieres que sepa sobre ti? <!-- .element: class="fragment" -->

¿Cómo te gustaría que te respondiera? <!-- .element: class="fragment" -->
---
## Algunas conversaciones de aplicación en el ámbito docente

<img class="r-stretch" style="text-align: center" src="../assets/teacher-llm.webp">


[Programaciones didácticas](../chats/programaciondidactica.html)

[Situaciones de aprendizaje](../chats/situacionaprendizaje.html) <!-- .element: class="fragment" -->

[Tareas](../chats/tareas.html) <!-- .element: class="fragment" -->

[Exámenes](../chats/examenes.html) <!-- .element: class="fragment" -->

[Proyectos](../chats/proyectos.html) <!-- .element: class="fragment" -->


[Rúbricas](../chats/rubricas.html)

[Correcciones](../chats/correcciones.html) <!-- .element: class="fragment" -->

[Correos electrónicos](../chats/email.html) <!-- .element: class="fragment" -->

[Publicaciones en redes sociales](../chats/rrss.html) <!-- .element: class="fragment" -->

Note:
https://educagob.educacionyfp.gob.es/en/curriculo/curriculo-lomloe/definiciones.html

https://educagob.educacionyfp.gob.es/en/curriculo/curriculo-lomloe/menu-curriculos-basicos/ed-secundaria-obligatoria.html
---
## ¿Qué tareas puede realizar un LLM?

<img class="r-stretch" style="text-align: center" src="../assets/tareas-llm.webp">


## Las tareas que mejor realiza

Resúmenes <!-- .element: class="fragment" -->

Preguntas y respuestas sobre un texto proporcionado <!-- .element: class="fragment" -->

Traducción <!-- .element: class="fragment" -->

Planificación <!-- .element: class="fragment" -->

Redacción en diferentes estilos de textos genéricos <!-- .element: class="fragment" -->


Escritura de código sencillo y razonamiento sobre el mismo

Explicación de conceptos complejos, dada una descripción previa <!-- .element: class="fragment" -->

Análisis de sentimiento <!-- .element: class="fragment" -->

Invención de historias, poesías... <!-- .element: class="fragment" -->

¿Puedes imaginar más? <!-- .element: class="fragment" -->


## Las tareas que peor realiza

Cálculos matemáticos <!-- .element: class="fragment" -->

Tareas que conlleven conocimiento factual no proporcionado <!-- .element: class="fragment" -->

Humor y sarcasmo <!-- .element: class="fragment" -->

Razonamientos excesivamente complejos <!-- .element: class="fragment" -->

---

## Combinando varios modelos...

Creación de un Avatar Personalizado y Animado con tu Voz

<p align="center">
<video width="480" height="360" controls>
  <source src="../avatar/assets/avatar.mp4" type="video/mp4">
  Tu navegador no soporta el elemento de video.
</video>
</p>

<small>https://0xmrivas.github.io/formacion-profesorado-IA-IES-las-banderas/avatar</small>

---
## Trabajando con LLMs

<img class="r-stretch" style="text-align: center" src="../assets/trabajando-con-llms.png">


## Investigación

<img class="r-stretch" style="text-align: center" src="../assets/perplexity.png">

<small>https://www.perplexity.ai</small>


## Probando ChatGPT Plus

<img class="r-stretch" style="text-align: center" src="../assets/copilot.png">

<small>https://copilot.microsoft.com</small>


## Capacidades de Copilot

Elección de la temperatura <!-- .element: class="fragment" -->

Generación de imágenes <!-- .element: class="fragment" -->

Descripción de imágenes <!-- .element: class="fragment" -->

Bloc de notas para prompts extensos <!-- .element: class="fragment" -->


## Generación de imágenes con texto

<img class="r-stretch" style="text-align: center" src="../assets/ideogram.png">

<small>https://ideogram.ai</small>


## Generación de música

Chirp - Modelo experimental de Suno AI

[Disponible en Discord](https://discord.gg/suno-ai)

También en la web [suno.ai](https://suno.ai)


## Cómo hablar con un PDF

<img class="r-stretch" style="text-align: center" src="../assets/ai-pdf.png">

<small>https://smallpdf.com/ai-pdf</small>


## Cómo hablar con un vídeo de Youtube

<img class="r-stretch" style="text-align: center" src="../assets/whisper.png">

<small>https://huggingface.co/spaces/openai/whisper</small>

---

<!-- .slide: data-background-video="../assets/chatgpt.mp4" data-background-opacity="0.6" data-background-video-loop data-background-video-muted -->

## ¡Gracias por haberme dedicado vuestro tiempo!

---

## ¡ Escanea, y Opina !

<img class="r-stretch" style="text-align: center" src="../assets/qr_feedback.png">

<small>https://app.wooclap.com/MJGERM</small>

---

## Recursos

<img class="r-stretch" style="text-align: center" src="../assets/qr_materiales.png">

<small>https://0xmrivas.github.io/formacion-profesorado-IA-IES-las-banderas</small>

---

## Contacto

 Manuel J. Rivas Sández 
 <small>
- **Email:** [xmrivas@proton.me](mailto:xmrivas@proton.me)
- **Telegram:** [@xmrivas](https://t.me/xmrivas)
- **Twitter:** [@0xmrivas](https://twitter.com/0xmrivas)

- 💼 **PES SAI en el IES Rafael Alerti**

🛡️ Amante del **Hacking Etico** y la **Seguridad Informática**
</small> 