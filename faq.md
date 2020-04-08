---
description: >-
  Sección de Preguntas Frecuentes donde puedes consultar las dudas más
  habituales sobre el uso de Explore CMS.
---

# FAQ

## ¿Un módulo puede estar en varios layouts a la vez?

Sí, claro que sí. Por tanto, ten en cuenta que los cambios que hagas en un módulo pueden afectar a varios layouts. 

Al editar un módulo puedes ver en qué layout o layouts está:

![](.gitbook/assets/image%20%281%29.png)

## Quiero cambiar solo un detalle de un módulo para un layout pero ese módulo está también en uso en otro layout, ¿qué puedo hacer?

Si quieres que ese cambio afecte solo a un layout entonces crea otro módulo igual pero que incluya además el detalle que quieres modificar. En ese momento tendrás dos módulos creados. Usa en cada layout el módulo que necesites.

{% hint style="info" %}
Ejemplo

_Tengo los layouts **Layout android prepay** y **Layout ios prepay**. En ambos tengo el módulo **Rows Club Movistar**:_ 

_He decidido que una de las informaciones sobre el precio que quiero mostrar no es la misma para Android que para iOS._

_¿Cómo debo proceder?_

En ese caso lo que que tienes que hacer es crear un nuevo módulo. Llámalo, por ejemplo, _Club Movistar iOS_. La configuración será la misma que el módulo que ya tenías \(_Club Movistar_\) pero con el dato sobre el precio para iOS modificado, tal y como querías.

A continuación, cuando tengas ese módulo creado, accede al repositorio de Layouts y edita **Layout ios prepay**. Elimina el módulo **Row Club Movistar** y añade el nuevo módulo que has creado **Row Club Movistar iOS**.
{% endhint %}

{% hint style="warning" %}
No olvides ordenar los módulos tal y como quieras que aparezcan dado que el nuevo módulo que has añadido aparecerá en último lugar.
{% endhint %}

## He hecho un cambio en un módulo y quiero publicarlo. ¿Desde dónde lo hago?

En realidad los módulos no se publican, lo que publicas es el layout. La razón es sencilla: un cambio en un módulo puede afectar a varios layouts al mismo tiempo y es posible que esa no sea tu intención. Por esa razón lo que siempre vas a publicar son layouts.

🎯 ¿No sabes cómo publicar un layout? Esto te interesa 👇 

{% page-ref page="layout/publicar-layouts.md" %}

## He hecho cambios a un layout pero aún no los he publicado. ¿Puedo previsualizar esos cambios antes de hacerlos visibles a todos los usuarios?

Sí, claro que puedes hacerlo. Consulta este enlace 👇 

{% page-ref page="test-lines.md" %}

## Quiero crear un nuevo layout, ¿cómo lo hago?

No puedes crear un nuevo layout dado que los layouts vienen ya configurados en función de la segmentación de tus clientes. Recuerda, sistema operativo, modelo de pago.

## Quiero usar un módulo de tipo _Featured Content_ pero me gustaría que se viese después de otro módulo que había creado. ¿Es posible situarlo en cualquier posición?

Por supuesto. Puedes situarlo en la posición que quieras dentro del layout. Eso sí, ten en cuenta que el título que se muestra en ese caso es el que hayas definido en el campo **Section Title**.

![](.gitbook/assets/image%20%2850%29.png)

{% hint style="warning" %}
Ten en cuenta que en primera posición siempre tiene que ir un módulo de tipo _Featured Content_, independientemente de que uses más de este tipo en tu composición del layout.
{% endhint %}

## No tengo usuario para acceder a Explore CMS, ¿cómo lo obtengo?

Ponte directamente en contacto con tu equipo de NOVUM. Ellos gestionarán tu acceso.

## Categorías

Desde esta sección puedes resolver todas tus dudas referentes a la configuración de categorías y que te ayudarán a configurarlas de forma óptima:

### ¿Todo el contenido de Explore CMS tiene que estar categorizado?

Sí, así es. Todo el contenido tiene que tener asignada, al menos, una categoría.

### ¿Puedo editar, crear o eliminar una categoría desde Explore CMS?

No, no es posible ni crear, ni editar el nombre, ni eliminar una de las categorías existentes desde Explore CMS. Pero no te preocupes porque las categorías que puedes seleccionar han sido acordadas con tu OB para que no necesites crear categorías nuevas.

Si aún así consideras que hay contenido que no se adapta a ninguna de las categorías disponibles no dudes en ponerte en contacto con el responsable de tu OB para que pueda trasladar al equipo de NOVUM tu petición. Juntos decidirán si efectivamente es necesario hacer algún cambio.

### He visto que hay muchas categorías predefinidas en Explore CMS pero no las necesito todas.

No pasa nada. Si hay alguna categoría que no necesitas no la uses. En ese caso esa categoría no se muestra al usuario.

### ¿Puedo usar solo una categoría para todo mi contenido?

No, necesitas usar al menos 3 categorías de las propuestas. Piensa que si solo usas 1 o 2 categorías el contenido que muestras al usuario es prácticamente el mismo.

De todos modos seguro que tienes un contenido muy interesante para usar al menos esas 3 categorías. De hecho la recomendación es que uses entre 3 y 5 categorías. Eso hará que la experiencia del usuario al usar Explore mejore considerablemente.

### ¿Puedo cambiar el orden en el que se van a mostrar las categorías en Explore?

Desde Explore CMS no. Pero no te preocupes porque antes del lanzamiento de las categorías el orden se ha acordado ya con los responsables de tu OB. 

Si fuera necesario algún cambio, comunícalo a la persona responsable de tu OB para que lo pueda gestionar con el personal de NOVUM.

