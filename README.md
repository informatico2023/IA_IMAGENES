# 🤖 IA Imágenes

Repositorio para recoger herramientas de generación de imágenes a través de IA

## 1. Qué es el promt?
El prompt es la instrucción en lenguaje natural que interpretará la IA como el conjunto de instrucciones para generar a partir de ella la imagen, este tiene que ser en inglés. Dependiendo de esas palabras el resultado será diferente y un pequeño cambio hará que pueda variar bastante.

Aunque un prompt puede ser muy básico:
```
cat
```
![Imágen creada con DreamStudio](https://github.com/Poloigithub/iaimages/blob/main/images/gato.jpeg "Imágen creada con DreamStudio")

Lo mejor es crear uno dónde demos mayor información, lo mejor es que cumpla la siguiente estructura.

**Tipo de obra | Contenido | Estilo | Modificadores**

Esto sería una ejemplo para obetener una fotografía de un gato siamés en un sofá:
```
photography of a siamese cat, on a sofa, HD photo, trending on artstation
```
![Imágen creada con DreamStudio](https://github.com/Poloigithub/iaimages/blob/main/images/gato2.jpeg "Imágen creada con DreamStudio")

Al principio es complicado encontrar un prompt que haga lo que realmente teníamos en la cabeza, es cosa de ir probando combinaciones y sobre todo, buscar los de otros usuarios para aprender como construyen los suyos. Puedes buscar promts en la plataforma [lexica.art](https://lexica.art/)

## 2. Generación de imágenes Lv1

Recopilación de aquellas herramientas que de forma muy rápida nos permiten generar imágenes a través de IA.

### 2.1. Starryai

![Starryai](https://github.com/Poloigithub/iaimages/blob/main/images/starryai.png)

Herramienta muy simple de utilizar, ofrece 5 créditos diarios de forma gratuita, además tiene aplicación para iOS y Android. Lamentablemente los resultados no llegan a ser muy buenos en muchas ocasiones. [https://starryai.com/](https://starryai.com/)

### 2.2. Stable Diffusion 2.1. Huggingface

![stabble diffusion huggingface](https://github.com/Poloigithub/iaimages/blob/main/images/sdhugg.png)

Espacio en Huggingface dónde poder utilizar una versión simplificada de Stable Diffusión, aunque la velocidad no es la mejor, si que nos permite utilizarlo las veces que queramos con tan sólo introducir las intrucciones. https://huggingface.co/spaces/stabilityai/stable-diffusion


## 3. Generación de imágenes Lv2

Aquí voy a recopilar aquellas herramientas que nos permiten generar imágenes que son un poco más avanzadas, estas ya nos permitirán retocar algunos parámetros y configuraciones de forma simple.

### 3.1. DreamStudio

![DreamStudio](https://github.com/Poloigithub/iaimages/blob/main/images/dreamstudio.png)

Versión web de **Stable Diffusión**, nos permite generar imágenes de forma gratuita con los 200 créditos que nos proporcionan en un principio, una vez acabados estos se tienen que pasar por caja.

Para utilizarla es muy sencillo, hay que crear un usuario en [https://beta.dreamstudio.ai/](https://beta.dreamstudio.ai/), modificar el prompt que nos viene por defecto y darle al botón de **Dream**.

### 3.2. Midjourney

![Midjourney](https://github.com/Poloigithub/iaimages/blob/main/images/midjourney.png)

Personalmente es una de las que creo que mejores resultados da, aunque es necesario tener una invitación y funciona a través de un bot de Discord, cosa que puede hacer que algunas usuarias tengan una barrera de inicio importante.

Puedes pedir una invitación desde [https://www.midjourney.com/](https://www.midjourney.com/) , es necesario para ello tener una cuenta en Discord.

Una vez que tú invitación sea aceptada tendrás que entrar al canal de Discord de Midjourney y unirte a una de los canales de creación de imágenes, desde allí teclear el comando **/imagine** del prompt que quieras utilizar y el bot después de unos segundos te contestará con cuatro imágenes generadas.

Una vez generadas puedes elegir que rescale alguna de ellas desde el menú:

U1 | U2 | U3 | U4

O que genere versiones de a partir de algunas desde el menú:

V1 | V2 | V3 | V4

De nuevo el bot nos contestará con lo que le hayamos indicado.

### 3.3. Dall·E

![DallE](https://github.com/Poloigithub/iaimages/blob/main/images/dalle.png)

IA para generación de imágenes de OpenAI, es muy simple de utilizar y ya no requiere invitación. Dispones de 15 créditos gratuitos mensualmente para la generación de imágenes y de una API de pago para poder conectarla con aplicaciones de producción propia. [https://labs.openai.com/](https://labs.openai.com/)


## 4. Generación de imágenes Lv3

## 5. Creación de vídeo

### 5.1. Genmo

![Genmo](https://github.com/Poloigithub/iaimages/blob/main/images/genmo.png)

Esta IA permite primero generar una imagen a través de un prompt y después animarla, por ahora lo consideraría sólo una curiosidad, no le veo mucho sentido. https://alpha.genmo.ai/

## 6. Edición de imágenes

### 6.1. InstructPix2Pix

![InstructPix2Pix](https://github.com/Poloigithub/iaimages/blob/main/images/intruc2pix.png)

Podemos a través del promtp modificar las imágenes que le añadamos, es una especie de editor de imágenes por IA. https://huggingface.co/spaces/timbrooks/instruct-pix2pix

