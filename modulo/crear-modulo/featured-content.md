---
description: >-
  También llamado carrusel horizontal. Usa este módulo, por ejemplo, para
  resaltar contendido relevante para el usuario.
---

# Featured Content

Es un módulo ideal para resaltar contenido de máximo interés para el usuario limitando el número de elementos que puede ver, con un máximo de 6. 

Los distintos contenidos configurados pasan a modo de carrusel horizontal para que el usuario pueda verlos cómodamente.

![](../../.gitbook/assets/image%20%281%29.png)

Rellena los campos obligatorios y decide si necesitas rellenar alguno de los campos opcionales:

## Details

![](../../.gitbook/assets/image%20%2812%29.png)

**Name**. Nombre que identifica internamente al elemento. En la app no se muestra en ningún momento pero con ese nombre puedes identificar el módulo en la vista de listado de módulos.

  🚦 No tiene una longitud máxima y es **obligatorio**.

**For more information check the guidelines**. Consulta las guías de diseño relativas al módulo que estás creando o editando. Revísalas para asegurar que estás subiendo contenido de la mejor calidad posible.

## Module building

![](../../.gitbook/assets/image%20%284%29.png)

**Section Title**. Título que se muestra encima del módulo siempre que no esté posicionado en primer lugar. Cuando va en la primera posición, no hay título de sección \(en ese caso el título de sección es siempre _Explore_\). Además, este título sirve para identificar internamente el módulo que estás creando. Con ese título puedes identificar el módulo en la vista de listado de módulos.

🚦 Tiene una longitud máxima de **25 caracteres** y es **obligatorio**.

{% hint style="warning" %}
Dentro de un layout, es obligatorio que un módulo de tipo _Featured Content_ esté en primera posición.
{% endhint %}

## Cards

Las _cards_ son las secciones que componen el carrusel. Para cada módulo de tipo _Featured Content_ configura un mínimo de 2 _cards_ y un máximo de 6.

![](https://lh6.googleusercontent.com/UmWxk0rCLIHcUzAvdtWe9vfU7N0OzoAKFModTG4DN02KSIrz8fjCEdbaauNnHf18KY3U9o8cilL3uLq_573S3L6payah8BXi1DuOYhNpq_8vWJie6CZb2ysJirFh58507trWurxE)

Para cada _card_ los campos disponibles varían en función de que selecciones una imagen o un _bumper_:

* **Image**. Muestra una imagen estática.
* **Bumper**. Muestra un vídeo corto o animación.

💡 __**¿Sabías que?**

Un _bumper_ es un vídeo corto o animación. Es un formato por lo general estándar con una duración media de 6 segundos aproximadamente y suele usarse con fines comerciales. 

{% tabs %}
{% tab title="Image" %}
![](../../.gitbook/assets/image%20%282%29.png)

**Image Upload an image** 📤. URL de la imagen de la _card_. Tiene que tener el formato de URL propio del CMS.

Haz clic en el enlace **Upload an image** 📤 ****y selecciona la imagen directamente desde de tu ordenador. Una vez procesada la subida de la imagen, la URL se autocompleta en el campo de texto.

Cuando la imagen se haya subido se previsualiza justo debajo.

![](https://lh4.googleusercontent.com/dULPpwb-XaQ083yWLTZF1G1l_7MO0cW70lM7eg5-ZpMvWyZAPBHjJJpMVNjiTUDtgMy1ng2b_JaSkVRGDZd84K0oSvZnzSS9wp_ddXuGkWXzR2Loo3Pbeio_0pm5ESpRuO28cUhx)

🚦 Este campo es **obligatorio**.

**Image Accesibility Text**. Descripción de la imagen que se usa para la accesibilidad como alternativa si la imagen no se puede mostrar \(por ejemplo, para personas con problemas de visión\).

🚦 No tiene una longitud máxima y es **opcional**.
{% endtab %}

{% tab title="Bumper" %}
![](../../.gitbook/assets/image%20%286%29.png)

**Bumper Upload a bumper** 📤. Se autorrellena con el nombre del _bumper_.

Para subir un bumper tienes dos opciones: 

1. Haz clic en el enlace **Upload a bumper** 📤 y sube una imagen desde tu ordenador.
2. Despliega la lista de los bumper y selecciona uno de los que ya haya subidos.

Activa la opción **Play in loop** para que el _bumper_ se reproduzca en bucle en Explore. Con la opción desactivada se reproduce cada vez que el _bumper_ entre en pantalla pero se para cuando termina la reproducción.

![Activa o desactiva la opci&#xF3;n para reproducir en bucle](../../.gitbook/assets/image%20%287%29.png)

Cuando el _bump_e_r_ se haya subido se previsualiza justo debajo:

![](https://lh3.googleusercontent.com/3IXi0mLJsZm9bEzL8Tv-0-lZoNL-TfIve9tuIW_3fQCsNTzYPF7HhKdPi_Vl5RV-TiRr7AF3LgeRpOP-IYXqNsxsMQqz2eZ-_T-zseUG3oWU7N7coCU5szug3M2kTo65W4LYDuT_)

**Bumper Accesibility Text**. Descripción del _bumper_ que se usa para la accesibilidad como alternativa si el _bumper_ no se puede mostrar \(por ejemplo, para personas con problemas de visión\).

🚦 No tiene una longitud máxima y es **opcional**.
{% endtab %}
{% endtabs %}







