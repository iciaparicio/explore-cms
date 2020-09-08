---
description: >-
  Exibe elementos em formato vertical. Utilize-o, por exemplo, para apresentar
  ofertas de celulares.
---

# Vertical Cards

Este tipo de módulo serve para mostrar vários elementos com formato vertical. É muito útil, por exemplo, para apresentar ofertas de produtos.

Exibe-se no modo carrossel, oferece links em cada _card_ e elementos opcionais, como a etiqueta sobre a imagem ou um link para toda uma lista \(“Ver tudo”\).

![](https://github.com/iciaparicio/explore-cms/tree/2d14bb61a8e92a38fe23ad18f7cf392e8f2f8668/pt-BR/.gitbook/assets/image%20%2869%29.png)

Preencha os campos obrigatórios e decida se precisa completar quaisquer dos campos opcionais:

## Details

![](https://github.com/iciaparicio/explore-cms/tree/2d14bb61a8e92a38fe23ad18f7cf392e8f2f8668/pt-BR/.gitbook/assets/image%20%2860%29.png)

**Name**. Nome que identifica internamente o elemento. Nunca é exibido no app, mas com esse nome pode identificar o módulo ao visualizar a lista de módulos.

🔅Não há extensão máxima e é **obrigatório**.

**For more information check the guidelines**. Consulte os guias de desenho referentes ao módulo que está criando ou editando. Verifique-os para garantir que o conteúdo que está sendo carregado possui a melhor qualidade possível.

## Module building

![](https://github.com/iciaparicio/explore-cms/tree/2d14bb61a8e92a38fe23ad18f7cf392e8f2f8668/pt-BR/.gitbook/assets/image%20%2853%29.png)

**Section Title**. Título mostrado acima do módulo. Também, o título serve para identificar internamente o módulo que está criando. Com esse título, você pode identificar o módulo ao visualizar a lista de módulos.

🔅A extensão máxima é **25 caracteres** e é **obrigatório**.

## Cards

Os _cards_ são as seções que integram o carrossel. Para cada módulo tipo _Vertical cards_ configure pelo menos 2 _cards_ e um máximo de 6.

![](https://github.com/iciaparicio/explore-cms/tree/2d14bb61a8e92a38fe23ad18f7cf392e8f2f8668/pt-BR/.gitbook/assets/vertical_cards_cms.png)

Os campos disponíveis para cada _card_ são:

**Card 1Image - Upload an image** 📤 . URL da imagem do _card_. Deve ter o formato de URL próprio do CMS.

Clique no link **Upload an image** 📤 e selecione a imagem diretamente de seu computador. Uma vez processado o upload da imagem, o URL é preenchido automaticamente no campo de texto.

Quando a imagem for carregada, será possível pré-visualizá-la logo abaixo.

![](https://github.com/iciaparicio/explore-cms/tree/2d14bb61a8e92a38fe23ad18f7cf392e8f2f8668/pt-BR/.gitbook/assets/image%20%2837%29.png)

🔅Não há extensão máxima e é **opcional**.

**Card 1 Image Accesibility Text**. Descrição da imagem utilizada para acessibilidade, como alternativa se não é possível exibir a imagem \(por exemplo, para pessoas com problemas de visão\).

🔅Não há extensão máxima e é **obrigatório**.

**Card 1 Title**. Título do card que aparece abaixo da imagem. Ainda, identifica internamente o card \(por exemplo: `iPhone X`\).

🔅A extensão máxima é **15 caracteres** e é **obrigatório**.

**Card 1 Tracking Name**. Nome que não será visualizado pelos usuários, mas sim no Google Analytics. Serve para uma identificação interna e mais fácil do produto.

🔅É **opcional**.

**Card 1 Description**. Breve descrição do produto apresentado \(por exemplo: `by Apple`\).

🔅A extensão máxima é **22 caracteres** e é **obrigatório**.

**Card 1 Offers Row**: **Standard**. Texto que aparece em cima do preço do _card_, e com estilo normal \(por exemplo: `​A partir de`\). Combinado com outros campos de **Offers Row** os últimos campos podem ser afetados se forem utilizados todos os disponíveis.

🔅A extensão máxima é **26 caracteres** e é **opcional**.

![](https://lh4.googleusercontent.com/U58Gt_-TAB8-6hP_lOnHwZTrWTwHGkEwUlQwYM307RiwVaimItNKmZ05kE-CmuAfsv1lz2iymyCPW_tjBoRR78OhsplTOmdJcfJqvP-7tyJAKkkc1Z0Vj0_AaAcaHS2_xs8A6JGH)

**Card 1 Offers Row: Highlight**. Texto que aparece em cima do preço do _card_, com estilo em destaque \(exemplo: `-18%`\). Combinado com outros campos de **Offers Row** os últimos campos podem ficar afetados se você utilizar todos os disponíveis.

🔅A extensão máxima é **26 caracteres** e é **opcional**.

![](https://lh6.googleusercontent.com/oYG3Qydlec2DuKc7ttf9gVM7GGkHzV0XYo8mVH2f4MJhE37Cb95CdPYH5x2UYYcrIvVuk_n0QBI8wG8APlWF8LzRGaSTVe9pWg6Sh1_ZrW5mQiEuxJyBsXk2yZEdjfhjgB4wzFw-)

Aqui poderá encontrar uma série de exemplos para combinar campos de **Offers Row**:

![](https://lh4.googleusercontent.com/DiHi3QS0LBDadggmHzsZil8UJdKpcV2f2lkvwmoxzqJHEiPBnEgSiSlZ_mS8BWpXo86vdPe8Q83khlKGfWrjRkGI8patA1-GyOzrbfHCJFBheR8mzSuZMug3PjJ_I4TtfYEnmnOu)

**Row 1 Price**. Preço que aparece abaixo do título e da descrição. Lembre-se sempre de indicar um preço válido \(por exemplo, `$123`\).

🔅Não há extensão máxima e é **obrigatório**.

**Row 1 Price Information.** Texto que apresenta informações adicionais sobre o preço e é exibido embaixo. Segundo o número de caracteres, ocupará uma ou duas linhas \(por exemplo: ​ `Até 12 meses sem juros`\).

🔅A extensão máxima é **52 caracteres** e é **opcional**.

**Card 1 Tag**. Texto curto posicionado por cima da imagem do _card_.

🔅A extensão máxima é **18 caracteres** \(recomenda-se menos de 10\) e é **opcional**.

**Card 1 Action Url**. URL do _card_, isto é, URL que é acessada ao clicar no _card_.

🔅É **obrigatória** e deve ser uma URL válida \(por exemplo: [`https://www.google.com`](https://www.google.com)\)

**Card 1 Starting date and time**. Data e hora que você deseja para iniciar a exibição do _card_ aos usuários.

🔅É opcional.

**Card 1 Ending date and time**. Data e hora desejados para que o _card_ finalize a exibição para os usuários.

🔅É opcional.

**Display the ending date on the card**. Ative esta opção para informar o usuário que o conteúdo irá expirar.

![](https://github.com/iciaparicio/explore-cms/tree/2d14bb61a8e92a38fe23ad18f7cf392e8f2f8668/pt-BR/.gitbook/assets/image%20%2827%29.png)

**Como é visualizada a data de validade?**

Se a opção de exibir a data de validade estiver habilitada, a exibição dessa data dependerá do dia em que expirar o _card_.

`FINALIZA HOJE hh:mm AM` ou `FINALIZA HOJE hh:mm PM` ou `FINALIZA HOJE hh:mm` \(o formato varia segundo o país\) para indicar que o _card_ expira no mesmo dia na hora indicada, pela manhã ou pela tarde, respectivamente. Por exemplo `FINALIZA HOJE 9:00AM`.

![](https://github.com/iciaparicio/explore-cms/tree/2d14bb61a8e92a38fe23ad18f7cf392e8f2f8668/pt-BR/.gitbook/assets/image%20%2855%29.png)

`AMANHÃ` indica que a data de validade é o dia seguinte.

![](https://github.com/iciaparicio/explore-cms/tree/2d14bb61a8e92a38fe23ad18f7cf392e8f2f8668/pt-BR/.gitbook/assets/image%20%286%29.png)

`FINALIZA dd mm` para indicar que a diferença é de mais de dois dias. Por exemplo `FINALIZA 30 JUN​`.

![](https://github.com/iciaparicio/explore-cms/tree/2d14bb61a8e92a38fe23ad18f7cf392e8f2f8668/pt-BR/.gitbook/assets/image%20%2824%29.png)

🎯 A data de início e finalização é uma maneira de programar algumas campanhas, especialmente naquelas de caráter sazonal.

**Card 1 Micro-segments**. Etiquetas que é possível adicionar, sempre separadas com vírgulas, para realizar uma segmentação dos usuários que observarão o conteúdo que está sendo criado.

🔅É **opcional**.

{% hint style="warning" %}
Lembre-se que deve configurar pelo menos 2 _cards_ e no máximo 6.

Os campos são iguais para todos os cards.
{% endhint %}

**Categorias do cartão 1 \(obrigatório\)**

As categorias permitem filtrar o conteúdo no Explore. As categorias são mostradas na parte superior, como um carrossel horizontal, para que o usuário possa navegar pelas categorias e selecionar aquele que deseja ver.

Quando o usuário seleciona uma categoria, o conteúdo é exibido no formato vertical \(em vez de rolagem horizontal\), para que o usuário não perca nenhum conteúdo.

![](https://github.com/iciaparicio/explore-cms/tree/2d14bb61a8e92a38fe23ad18f7cf392e8f2f8668/pt-BR/.gitbook/assets/categories_divices.png)

Em Explore CMS, selecione a categoria ou categorias que se aplicam ao cartão que você está configurando:

![](https://github.com/iciaparicio/explore-cms/tree/2d14bb61a8e92a38fe23ad18f7cf392e8f2f8668/pt-BR/.gitbook/assets/categories.png)

* **Accessories**. Acessórios: fones de ouvido, estojos, relógios.
* **Bundles**. Pacotes: pacotes, planos, pacotes de produtos.
* **Devices**. Dispositivos: smartphones, tablets.
* **Loyalty**. Fidelidade: associação, conteúdo de programas de fidelidade / fidelidade \(Valoriza, Priority, Movistar Club ...\)
* **Promos**. Promoções: conteúdo promocional que se encaixa e pode até existir com outras categorias.
* **Plans**.Planos: tarifas, planos, atualizações do plano.
* **Services**. Serviços: serviços de valor agregado \(novos recursos\), aplicativos, e outros serviços de TEF.
* **TV**. Televisão: planos de televisão, conteúdo em destaque.

{% hint style="info" %}
A categoria **Todos**, que é a primeira a ser exibida, não é uma categoria em si, mas é a maneira do usuário de ver todo o conteúdo.

Por padrão, quando um usuário abre o Explore, ele vê todo o conteúdo, todos os cartões configurados e, portanto, a categoria selecionada é sempre **Todos**.
{% endhint %}

#### O que devo ter em mente ao usar as categorias?

Consulte a seção [**Categorias**](https://app.gitbook.com/@tef-novum/s/explore-cms/~/drafts/-LyYX2WN5Qc794RVRWmG/faq#categorias) das [perguntas frequentes](../../faq.md) para responder a todas as suas perguntas!

### Mudar a ordem dos _cards_

Dentro do módulo, é possível movimentar os cards para mudar a ordem em que são exibidos.

![](https://github.com/iciaparicio/explore-cms/tree/2d14bb61a8e92a38fe23ad18f7cf392e8f2f8668/pt-BR/.gitbook/assets/drag-and-drop.png)

Para movimentar um _card_ arraste-o até a posição onde será exibido e solte-o.

![](https://github.com/iciaparicio/explore-cms/tree/2d14bb61a8e92a38fe23ad18f7cf392e8f2f8668/pt-BR/.gitbook/assets/drag-and-drop_demo.gif)

## Link

De maneira opcional, é possível adicionar links que aparecerão na parte inferior do módulo.

![](https://github.com/iciaparicio/explore-cms/tree/2d14bb61a8e92a38fe23ad18f7cf392e8f2f8668/pt-BR/.gitbook/assets/link_module.png)

Para isso, preencha para cada link que deseja adicionar \(máximo de 5 links\) os campos abaixo:

**Name**. Nome do link \(por exemplo, ​ `Vantagens`\).

🔅 A extensão máxima é **38 caracteres** e é **obrigatório**.

**Action URL.** Link que aparece ao clicar no **Name**, isto é, no nome do link.

🔅 É obrigatório e deve ser uma URL válida \(por exemplo: [`https://www.google.com`](https://www.google.com)\)

![](https://github.com/iciaparicio/explore-cms/tree/2d14bb61a8e92a38fe23ad18f7cf392e8f2f8668/pt-BR/.gitbook/assets/vertical_cards_link.png)

