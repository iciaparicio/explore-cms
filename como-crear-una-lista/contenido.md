# Contenido

El contenido de una lista de extras son justamente los extras. Usa este segundo paso para añadirlos, gestionarlos o borrarlos si ya no son necesarios.

![](../.gitbook/assets/content\_add\_module.png)

Haz clic en **Add new extra** para añadir un extra a la lista y rellena los campos necesarios:

**List provider**. Indica de dónde viene la información para configurar los extras de la lista:

* **Provider by user CMS**. Selecciona esta opción para configurar manualmente el extra.
* **Provider by Product ID**. Selecciona esta opción para indicar un Product ID y recibir la información del Extra a través de API.

{% hint style="info" %}
Esta información te la debería proporcionar tu equipo de desarrollo.
{% endhint %}

**Icon**

Añade el icono que representa al extra. La versión por defecto (la de **Icon**) es obligatoria y opcionalmente puedes añadir la versión **Dark icon,** que sería el icono que se muestra al usuario cuando está en _dark mode_ desde la app.

{% hint style="success" %}
Es recomendable que subas ambas versiones del icono y que lo hagas en formato SVG. También admite formato PNG.
{% endhint %}

**Name of the extra module**. Nombre del extra que aparece bajo el icono.&#x20;

{% hint style="info" %}
:bulb:Es recomendable que uses un nombre muy corto porque de lo contrario aparecerá cortado.
{% endhint %}

**Action configuration of your extra**

* **Not include clickable action**. Selecciona esta opción, marcada por defecto, si no quieres que el icono + texto del extra sean clicables.
* **Include clickable action**. Marca esta opción para hacer clicable el conjunto de icono + texto del extra y configurar la URL a la que se dirige al usuario cuando haga clic.
  * **Action navigation to**:&#x20;
    * **URL**. Selecciona esta opción para incluir una URL manualmente. Indica en el campo Web address la URL a la que dirigir al usuario cuando haga clic en el extra.
    * **Preconfigured**. Selecciona esta opción para elegir un punto concreto de la app. Indica en el desplegable el punto concreto.

**Audiences**. Selecciona la audiencia a la que tiene que pertenecer el usuario para que pueda ver el extra.

{% hint style="success" %}
🤓Ten en cuenta que dentro de una lista de extras puedes tener extras configurados para diferentes audiencias. Obviamente esto no es un problema pero es importante que no lo olvides porque cuando hagas test o las pruebas necesarias que para que un extra se vea es imprescindible que el usuario pertenezca a esa audiencia.
{% endhint %}

Si necesitas añadir más extras haz clic en el botón **Add new extra** y repite los pasos descritos en esta sección.

Haz clic en **Continue** para pasar al último paso.
