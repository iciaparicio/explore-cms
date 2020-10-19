---
description: >-
  También llamado carrusel horizontal. Usa este módulo, por ejemplo, para
  resaltar contendido relevante para el usuario.
---

# Featured Content

Es un módulo ideal para resaltar contenido de máximo interés para el usuario limitando el número de elementos que puede ver, con un máximo de 6. 

Los distintos contenidos configurados pasan a modo de carrusel horizontal para que el usuario pueda verlos cómodamente.

![](../../.gitbook/assets/featured_content_module.png)

Rellena los campos obligatorios y decide si necesitas rellenar alguno de los campos opcionales:

## Details

![](../../.gitbook/assets/details_module-1-.png)

**Module Type**. Indica de qué tipo es el módulo que estás configurando o editando.  
 ℹ Campo informativo, no editable.

**Name**. Nombre que identifica internamente al elemento. En la app no se muestra en ningún momento pero con ese nombre puedes identificar el módulo en la vista de listado de módulos.  
 🔅No tiene una longitud máxima y es **obligatorio**.

{% hint style="info" %}
Este campo viene informado del paso anterior pero puedes modificarlo si lo consideras necesario.
{% endhint %}

**Layouts.** Campo informativo, no editable, que te indica en qué layouts está incluido el módulo que estás configurando o editando.   
ℹ Campo informativo, no editable.

**For more information check the guidelines**. Consulta las guías de diseño relativas al módulo que estás creando o editando. Revísalas para asegurar que estás subiendo contenido de la mejor calidad posible.

## Module building

![](../../.gitbook/assets/module_building.png)

**Section Title**. Título que se muestra encima del módulo siempre que no esté posicionado en primer lugar. Cuando va en la primera posición, no hay título de sección \(en ese caso el título de sección es siempre _Explore_\). Además, este título sirve para identificar internamente el módulo que estás creando. Con ese título puedes identificar el módulo en la vista de listado de módulos.  
🔅Tiene una longitud máxima de **25 caracteres** y es **obligatorio**.

{% hint style="warning" %}
Dentro de un layout, es obligatorio que un módulo de tipo _Featured Content_ esté en primera posición.
{% endhint %}

### Cards

Desde esta sección puedes crear una card nueva o puedes usar una card que ya esté creada previamente. En ambos casos haz clic en **+ ADD CARD**.

![](../../.gitbook/assets/type_of_card.png)

En la pantalla **Type of card** selecciona una de las opciones:

* **New card**. Selecciona esta opción para crear una nueva card. 
* **Reuse card**. Selecciona una card de las existentes en el desplegable.  Para agilizar tu selección, usa el buscador. Las cards mostradas se van filtrando en función de lo que escribas en el buscador.

Haz clic en **NEXT** para continuar.

Ten en cuenta que los siguientes pasos varían en función de la opción que hayas seleccionado en la ventana Type of card:

#### Si has seleccionado la opción **New card**

Crea una nueva card siguiendo los siguientes pasos 👇 

{% page-ref page="../../card/crear-una-card.md" %}

#### Si has seleccionado la opción Reuse card

Ahora la sección **Module building** contiene la card que has seleccionado en el desplegable **Reuse Card** del paso anterior.

![](../../.gitbook/assets/reuse_card_add.png)



Las _cards_ son las secciones que componen el módulo.Para cada módulo de tipo _Featured Content_ configura un mínimo de 2 _cards_ y un máximo de 6.

![](../../.gitbook/assets/featured_content_cms.png)

Para cada _card_ los campos disponibles varían en función de que selecciones una imagen o un _bumper_:

* **Image**. Muestra una imagen estática.
* **Bumper**. Muestra un vídeo corto o animación.

\*\*\*\*💡 __**¿Sabías que?**

Un _bumper_ es un vídeo corto o animación. Es un formato por lo general estándar con una duración media de 6 segundos aproximadamente y suele usarse con fines comerciales. 

{% tabs %}
{% tab title="Image" %}
![](../../.gitbook/assets/image%20%2812%29.png)

**Image Upload an image** 📤. URL de la imagen de la _card_. Tiene que tener el formato de URL propio del CMS.

Haz clic en el enlace **Upload an image** 📤 ****y selecciona la imagen directamente desde de tu ordenador. Una vez procesada la subida de la imagen, la URL se autocompleta en el campo de texto.

Cuando la imagen se haya subido se previsualiza justo debajo.

![](https://lh4.googleusercontent.com/dULPpwb-XaQ083yWLTZF1G1l_7MO0cW70lM7eg5-ZpMvWyZAPBHjJJpMVNjiTUDtgMy1ng2b_JaSkVRGDZd84K0oSvZnzSS9wp_ddXuGkWXzR2Loo3Pbeio_0pm5ESpRuO28cUhx)

🔅Este campo es **obligatorio**.

**Image Accesibility Text**. Descripción de la imagen que se usa para la accesibilidad como alternativa si la imagen no se puede mostrar \(por ejemplo, para personas con problemas de visión\).

🔅No tiene una longitud máxima y es **opcional**.
{% endtab %}

{% tab title="Bumper" %}
![](../../.gitbook/assets/image%20%2823%29.png)

**Bumper Upload a bumper** 📤. Se autorrellena con el nombre del _bumper_.

Para subir un bumper tienes dos opciones: 

1. Haz clic en el enlace **Upload a bumper** 📤 y sube un _bumper_ desde tu ordenador.
2. Despliega la lista de los _bumpers_ y selecciona uno de los que ya haya subidos.

Activa la opción **Play in loop** para que el _bumper_ se reproduzca en bucle en Explore. Con la opción desactivada se reproduce cada vez que el _bumper_ entre en pantalla pero se para cuando termina la reproducción.

![Activa o desactiva la opci&#xF3;n para reproducir en bucle](../../.gitbook/assets/image%20%2829%29.png)

Cuando el _bump_e_r_ se haya subido se previsualiza justo debajo:

![](https://lh3.googleusercontent.com/3IXi0mLJsZm9bEzL8Tv-0-lZoNL-TfIve9tuIW_3fQCsNTzYPF7HhKdPi_Vl5RV-TiRr7AF3LgeRpOP-IYXqNsxsMQqz2eZ-_T-zseUG3oWU7N7coCU5szug3M2kTo65W4LYDuT_)

**Bumper Accesibility Text**. Descripción del _bumper_ que se usa para la accesibilidad como alternativa si el _bumper_ no se puede mostrar \(por ejemplo, para personas con problemas de visión\).

🔅No tiene una longitud máxima y es **opcional**.
{% endtab %}
{% endtabs %}

**Card 1 Pre-title**. Título que aparece inmediatamente debajo de la imagen del carrusel. 

🔅Tiene una longitud máxima de **44 caracteres** \(recomendado menos de 24\) y es **obligatorio**.

**Card 1 Title**. Título que aparece debajo del **Pre-title** y que identifica a la _card_ internamente.

🔅Tiene una longitud máxima de **70 caracteres** \(recomendado menos de 35 para no ocupar más de una línea\) y es **obligatorio**.

**Card 1 Tracking Name**. Nombre que no ven los usuarios pero sí se ve en Google Analytics. Sirve para identificar el producto internamente de manera más fácil. 

🔅Es **opcional**.

**Card 1 Description**. Pequeña descripción de la _card_. 

🔅Tiene una longitud máxima de **132 caracteres** \(recomendado menos de 125\) y es **obligatorio**.

**Card 1 Tag**. Texto corto que se sitúa por encima de la imagen de la _card_.

🔅Tiene una longitud máxima de **18 caracteres** \(recomendado menos de 10\) y es **opcional**.

**Card 1 Action Url**. URL de la _card_, es decir, URL a la que se accede al hacer clic sobre la _card_. 

🔅Es **obligatoria** y tiene que ser una URL válida \(ejemplo: [https://www.google.com](https://www.google.com)\)

**Card 1 Starting date and time**. Fecha y hora en la que quieres que la _card_ empiece a mostrarse a los usuarios. 

🔅Es opcional.

**Card 1 Ending date and time**. Fecha y hora en la que quieres que la _card_ termine de mostrarse a los usuarios.

🔅Es opcional.

**Display the ending date on the card**. Activa esta opción para informar al usuario que el contenido va a caducar. 

![](../../.gitbook/assets/image%20%2827%29.png)

**¿Cómo se visualiza la fecha de caducidad?**

Si has habilitado la opción de mostrar la fecha de caducidad, cómo se muestre esa fecha depende del día en que expire la _card_.

`TERMINA HOY hh:mm AM` o `TERMINA HOY hh:mm PM` o `TERMINA HOY hh:mm` \(el formato varía en función del país\) para indicar que la _card_ caduca en el mismo día a la hora indicada, por la mañana o por la tarde, respectivamente. Por ejemplo `TERMINA HOY 9:00AM`.

![](../../.gitbook/assets/image%20%2865%29.png)

`TERMINA MAÑANA` para indicar que la fecha de caducidad es al día siguiente. 

![](../../.gitbook/assets/image%20%286%29.png)

`TERMINA dd mm` para indicar que la diferencia es de más de dos días. Por ejemplo `TERMINA 30 JUN`.

![](../../.gitbook/assets/image%20%2824%29.png)

🎯 La fecha de comienzo y fin son una manera de programar algunas campañas, especialmente aquellas de carácter estacional.

**Card 1 Micro-segments**. Etiquetas que puedes añadir, siempre separadas por comas, para hacer una segmentación de los usuarios que van a ver el contenido que estás creando.

🔅Es **opcional**.

{% hint style="warning" %}
Recuerda que tienes que configurar un mínimo de 2 _cards_ y un máximo de 6.

Los campos para todas las cards son los mismos.
{% endhint %}

**Card 1 categories \(mandatory\)**

Las categorías te permiten filtrar el contendido en Explore. Las categorías se muestran en la parte superior, a modo de carrusel horizontal, de modo que el usuario puede navegar por las categorías y seleccionar la que quiera ver.

Cuando el usuario selecciona una categoría el contenido se muestra ordenado en formato vertical \(en lugar de scroll horizontal\), para que el usuario no se pierda ningún contenido.

![](../../.gitbook/assets/categories_devices-1-.png)

En Explore CMS selecciona la categoría o las categorías que aplican a la card que estás configurando:

![](../../.gitbook/assets/categories.png)

* **Accessories**. Accesorios: auriculares, fundas, relojes.
* **Bundles**. Paquetes: packs, planes, paquetes de productos.
* **Devices**. Dispositivos: smartphones, tablets.
* **Loyalty**. Fidelización: membresía, contenido de programas de loyalty/fidelización \(Valoriza, Priority, Club Movistar…\)
* **Promos**. Promociones: Contenido promocional que pueda encajar y que es posible que incluso pueda convivir con otras categorías.
* **Plans**. Planes: Tarifas, actualizaciones, planes de precios.
* **Services**. Servicios: servicios de valor añadido \(nuevas funcionalidades\), apps, servicios de TEF. 
* **TV**. Televisión: planes de televisión, contenido destacado.

{% hint style="info" %}
La categoría **All**, que es la primera que se visualiza, no es una categoría como tal sino que es la forma que tiene el usuario de ver todo el contenido.

Por defecto, cuando un usuario abre Explore, ve todo el contenido, todas las cards configuradas, y por tanto la categoría seleccionada es siempre **All**. 
{% endhint %}

🎯 **Buenas prácticas**: No es recomendable que un contenido tenga asignada más de una categoría, aunque Explore CMS no limite este comportamiento. A nivel de medición de datos  

#### ¿Qué debo tener en cuenta cuando uso las categorías?

¡Consulta la sección [**Categorías**](https://app.gitbook.com/@tef-novum/s/explore-cms/~/drafts/-LyYX2WN5Qc794RVRWmG/faq#categorias) ****del [FAQ](../../faq.md) para resolver todas tus dudas!

### Cambiar el orden de las _cards_

Dentro del módulo puedes mover las cards para cambiar el orden en el que se muestran. 

![](../../.gitbook/assets/drag-and-drop.png)

Para mover una _card_ arrástrala a la posición en la que quieres que se muestre y suéltala.

![](../../.gitbook/assets/drag-and-drop_demo.gif)

## Link

De forma opcional puedes añadir enlaces que aparecerán en la parte inferior del módulo.

![](../../.gitbook/assets/link_module.png)

Para hacerlo rellena, para cada enlace que quieras añadir \(hasta un máximo de 5 enlaces\), los siguientes campos:

**Name**. Nombre del enlace \(ejemplo `Beneficios`\).

🔅 Tiene una longitud máxima de **38 caracteres** y es **obligatorio**.

**Action URL.** Enlace ****que se abre al hacer clic sobre el **Name**, es decir, sobre el nombre del enlace.

🔅 Es obligatorio y tiene que ser una URL válida \(ejemplo: [`https://www.google.com`](https://www.google.com)\)

![](../../.gitbook/assets/link_featured_content.png)

