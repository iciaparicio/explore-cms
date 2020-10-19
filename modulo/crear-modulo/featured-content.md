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

{% page-ref page="../../card/crear-una-card/" %}

#### Si has seleccionado la opción Reuse card

Ahora la sección **Module building** contiene la card que has seleccionado en el desplegable **Reuse Card** del paso anterior.

![](../../.gitbook/assets/reuse_card_add.png)

## Link

De forma opcional puedes añadir enlaces que aparecerán en la parte inferior del módulo.

![](../../.gitbook/assets/link_module.png)

Para hacerlo rellena, para cada enlace que quieras añadir \(hasta un máximo de 5 enlaces\), los siguientes campos:

**Name**. Nombre del enlace \(ejemplo `Beneficios`\).  
🔅 Tiene una longitud máxima de **38 caracteres** y es **obligatorio**.

**Action URL.** Enlace ****que se abre al hacer clic sobre el **Name**, es decir, sobre el nombre del enlace.  
🔅 Es obligatorio y tiene que ser una URL válida \(ejemplo: [`https://www.google.com`](https://www.google.com)\)

![](../../.gitbook/assets/link_module_app.png)

### Cambiar el orden de las _cards_

Dentro del módulo puedes mover las cards para cambiar el orden en el que se muestran. 

![](../../.gitbook/assets/drag-and-drop.png)

Para mover una _card_ arrástrala a la posición en la que quieres que se muestre y suéltala.

![](../../.gitbook/assets/drag-and-drop_demo.gif)

