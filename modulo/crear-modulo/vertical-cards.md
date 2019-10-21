---
description: >-
  Muestra elementos en formato vertical. Úsalo, por ejemplo, para presentar
  ofertas de móviles.
---

# Vertical cards

Este tipo de módulo sirve para mostrar varios elementos en formato vertical. Es muy útil para presentar, por ejemplo, ofertas de productos.

Se muestra a modo carrusel ofreciendo enlaces en cada _card_ y elementos opcionales como la etiqueta sobre la imagen o un enlace a toda una lista \(un “Ver todo”\).

![](../../.gitbook/assets/image%20%2830%29.png)

Rellena los campos obligatorios y decide si necesitas rellenar alguno de los campos opcionales:

## Details

![](../../.gitbook/assets/image%20%2824%29.png)

**Name**. Nombre que identifica internamente al elemento. En la app no se muestra en ningún momento pero con ese nombre puedes identificar el módulo en la vista de listado de módulos.

🚦No tiene una longitud máxima y es **obligatorio**.

**For more information check the guidelines**. Consulta las guías de diseño relativas al módulo que estás creando o editando. Revísalas para asegurar que estás subiendo contenido de la mejor calidad posible.

## Module building

![](../../.gitbook/assets/image%20%2821%29.png)

**Section Title**. Título que se muestra encima del módulo. Además, este título sirve para identificar internamente el módulo que estás creando. Con ese título puedes identificar el módulo en la vista de listado de módulos.

🚦 Tiene una longitud máxima de **25 caracteres** y es **obligatorio**.

## Cards

Las _cards_ son las secciones que componen el carrusel. Para cada módulo de tipo _Vertical cards_ configura un mínimo de 2 _cards_ y un máximo de 6.

![](../../.gitbook/assets/image%20%286%29.png)

![](https://lh5.googleusercontent.com/LV8-Qu4VT7DfhMmvYGdFOm0hHARkbOm8rVq89cWoK3IaADwlh_z-AITPDEx_I02gVcyiommxhOzes93i5o5HBOwBk4qzLkj76Hc31qO2hN_XAm72xIZPqVZxoAKd6SQGzb_uIOiB)

Para cada _card_ los campos disponibles son:

**Card 1Image - Upload an image** 📤 . URL de la imagen de la _card_. Tiene que tener el formato de URL propio del CMS.

Haz clic en el enlace **Upload an image** 📤 y selecciona la imagen directamente desde de tu ordenador. Una vez procesada la subida de la imagen, la URL se autocompleta en el campo de texto.

Cuando la imagen se haya subido se previsualiza justo debajo.

![](../../.gitbook/assets/image%20%2811%29.png)

🚦 No tiene una longitud máxima y es **opcional**. 

**Card 1 Image Accesibility Text**. Descripción de la imagen que se usa para la accesibilidad como alternativa si la imagen no se puede mostrar \(por ejemplo, para personas con problemas de visión\).

🚦 No tiene una longitud máxima y es **obligatorio**. 

**Card 1 Title**. Título de la card que aparece bajo la imagen. Además, identifica internamente a la card \(ejemplo: `iPhone X`\). 

🚦 Tiene una longitud máxima de **15 caracteres** y es **obligatorio**.

**Card 1 Tracking Name**. Nombre que no ven los usuarios pero sí se ve en Google Analytics. Sirve para identificar el producto internamente de manera más fácil. 

🚦 Es **opcional**.

**Card 1 Description**. Breve descripción del producto presentado \(ejemplo: `by Apple`\).

🚦 Tiene una longitud máxima de **22 caracteres** y es **obligatorio**.

**Card 1 Offers Row**: **Standard**. Texto que se muestra sobre el precio de la _card_, con un estilo normal \(ejemplo: `Desde`\). Combinado con otros campos de **Offers Row** los últimos campos se pueden ver afectados si usas todos los disponibles. 

🚦 Tiene una longitud máxima de **26 caracteres** y es **opcional**.

![](https://lh4.googleusercontent.com/U58Gt_-TAB8-6hP_lOnHwZTrWTwHGkEwUlQwYM307RiwVaimItNKmZ05kE-CmuAfsv1lz2iymyCPW_tjBoRR78OhsplTOmdJcfJqvP-7tyJAKkkc1Z0Vj0_AaAcaHS2_xs8A6JGH)

**Card 1 Offers Row: Highlight**. Texto que se muestra sobre el precio de la _card_, con un estilo destacado \(ejemplo: `-18%`\). Combinado con otros campos de **Offers Row** los últimos campos se pueden ver afectados si usas todos los disponibles. 

🚦 Tiene una longitud máxima de **26 caracteres** y es **opcional**.

![](https://lh6.googleusercontent.com/oYG3Qydlec2DuKc7ttf9gVM7GGkHzV0XYo8mVH2f4MJhE37Cb95CdPYH5x2UYYcrIvVuk_n0QBI8wG8APlWF8LzRGaSTVe9pWg6Sh1_ZrW5mQiEuxJyBsXk2yZEdjfhjgB4wzFw-)

Aquí tienes un conjunto de ejemplos de combinaciones de campos de **Offers Row**:

![](https://lh4.googleusercontent.com/DiHi3QS0LBDadggmHzsZil8UJdKpcV2f2lkvwmoxzqJHEiPBnEgSiSlZ_mS8BWpXo86vdPe8Q83khlKGfWrjRkGI8patA1-GyOzrbfHCJFBheR8mzSuZMug3PjJ_I4TtfYEnmnOu)

**Row 1 Price**. Precio que se muestra debajo del título y la descripción. No olvides indicar siempre un precio válido \(ejemplo `$123`\).

🚦 No tiene una longitud máxima y es **obligatorio**.

**Row 1 Price Information.** Texto para aportar información adicional acerca del precio. Se muestra debajo. En función del número de caracteres ocupa una o dos líneas \(ejemplo `Hasta 12 meses sin intereses`\).

🚦 Tiene una longitud máxima de **52 caracteres** y es **opcional**.

**Card 1 Tag**. Texto corto que se sitúa por encima de la imagen de la _card_. 

🚦 Tiene una longitud máxima de **18 caracteres** \(recomendado menos de 10\) y es **opcional**.

**Card 1 Action Url**. URL de la _card_, es decir, URL a la que se accede al hacer clic sobre la _card_. 

🚦 Es **obligatoria** y tiene que ser una URL válida \(ejemplo: [`https://www.google.com`](https://www.google.com)\)

**Card 1 Starting date and time**. Fecha y hora en la que quieres que la _card_ empiece a mostrarse a los usuarios. 

🚦 Es opcional.

**Card 1 Ending date and time**. Fecha y hora en la que quieres que la _card_ termine a mostrarse a los usuarios.

🚦 Es opcional.

🎯 La fecha de comienzo y fin son una manera de programar algunas campañas, especialmente aquellas de carácter estacional.

**Card 1 Micro-segments**. 

{% hint style="warning" %}
Recuerda que tienes que configurar un mínimo de 2 _cards_ y un máximo de 6.

Los campos para todas las cards son los mismos.
{% endhint %}

