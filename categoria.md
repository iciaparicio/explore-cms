---
description: Todos los pasos detallados de cómo crear una categoría en Explore CMS
---

# Categoría

Las categorías permiten a los usuarios poder consumir, filtrado, el contenido de Explore. Estas categorías se muestran en la parte superior de Explore.

![](.gitbook/assets/categoria_detalle.png)

La creación y la gestión de categorías está disponible desde el menú lateral izquierdo **Explore &gt; Explore Categories**.

![](.gitbook/assets/menu_categorias.png)

### Crear una categoría

Para crear una categoría accede a **Explore &gt; Explore Categories** y haz clic en **Add category**.

![](.gitbook/assets/categories_general.png)

Para cada nueva categoría rellena los siguientes campos:

![](.gitbook/assets/configuracion_categoria.png)

#### Category

**Internal name**. Es el nombre interno que identifica la categoría. Este nombre no se muestra en la app en ningún momento pero sí se utiliza para crear el deep link que identifica la categoría. También es el nombre que se usa en Google Analytics para identificar esa categoría.  
🔅Es un campo **obligatorio**, que **no** admite ni **mayúsculas, espacios y caracteres especiales**.

{% hint style="warning" %}
Pese a que es un nombre interno asegúrate de crearlo correctamente porque una vez generada la categoría **no puedes modificar** este campo.
{% endhint %}

{% hint style="success" %}
_Ejemplo de un internal name incorrecto y de otro correcto_

👎 `InternetYTelevision`

👍 `internet_y_television`
{% endhint %}

Si necesitas más información sobre deep links consulta esta sección 👇 

{% page-ref page="deeplinks-en-explore.md" %}



**Category name**. Es el nombre de la categoría que ven los usuarios en la sección de Explore.  
🔅Tiene una longitud máxima de **11 caracteres** y es **obligatorio**.

![](.gitbook/assets/detalle_category_name.png)

**Icon**. Selecciona el icono para que se muestre en la app sobre el nombre de la categoría. Dispones de dos opciones para subir los iconos:

Para añadir un icono directamente desde tu equipo haz clic en **Upload icon** 📥.  
🔆 El icono tiene que tener unas **medidas de 90x90px** y formato **`.png`**

Para añadir un icono de la librería de Brand Factory haz clic en el botón **Go to Brand Factory**. 

{% hint style="info" %}
👩💻 Para poder añadir iconos desde BrandFactory necesitas estar logado con tu cuenta de empleado de Telefónica. 

El icono, además, debe cumplir el siguiente requisito:  
`App/iOS/text-preset-7/Regular/left/testPrimarySpecial0 icon Font`
{% endhint %}

![](.gitbook/assets/detalle_cagtegory_icon.png)

{% hint style="success" %}
El color del icono se cambia automáticamente, no tienes que hacer nada especial 😉 .
{% endhint %}

**Activate category**

**Active**. Es el estado por defecto con el que se crean las categorías. Las categorías en estado **Activado** son las que se muestran como categorías asignables en las cards.

**Inactive**. La categoría marcada con este estado no se muestra en la lista de categorías disponibles en las cards.

Haz clic en **Save** para guardar los cambios.

