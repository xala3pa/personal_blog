+++
author = "Álvaro Salazar"
categories = ["tools"]
date = "2019-11-02"
description = "All-in-one workspace"
featured = "notion.jpg"
featuredalt = "Notion.io"
featuredpath = "date"
linktitle = ""
tags = ["tools"]
title = "Notion, My brain backup"
type = "post"

+++

<BR>

Hace unos días compartía un Tweet, donde comentaba que después de un tiempo usando <a href="https://www.notion.so" target="_blank">Notion.io</a> había decidido comenzar a usarlo tanto en el trabajo como para tareas personales.

<blockquote class="twitter-tweet" data-cards="hidden"><p lang="en" dir="ltr">After a while using <a href="https://twitter.com/NotionHQ?ref_src=twsrc%5Etfw">@NotionHQ</a>, I think I&#39;m in love with the tool. I will start using it for both personal and work tasks <a href="https://t.co/erxlxYbQbm">https://t.co/erxlxYbQbm</a> <a href="https://t.co/u1ri8u4Aza">pic.twitter.com/u1ri8u4Aza</a></p>&mdash; Alvaro Salazar 🎃 (@xala3pa) <a href="https://twitter.com/xala3pa/status/1182652833583304704?ref_src=twsrc%5Etfw">October 11, 2019</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

Quiero aprovechar este post para introducir la herramienta a todas aquellas personas que todavía no la conocen o no se han decidido a darle una oportunidad y contaros algunos de los usos que le doy a día de hoy.

Después de un tiempo de uso ha comenzado a **sustituir a muchas de las herramientas** que usaba con cierta frecuencia para organizarme, herramientas como Evernote, Pocket, Trello, Keep, y en algunos casos incluso a Google docs y Slack.

## ¿Qué es Notion?

Notion se autodefine como un **“all-in-one workspace”**, una herramienta donde planificar, escribir, colaborar y organizarse.

En mi caso como os comentaba, he dejado de usar de forma paulatina, en beneficio de Notion, muchas de las herramientas que utilizo para organizarme en mi día a día. Poder tener flujos de trabajo soportados completamente en una única herramienta, ha supuesto en mi caso un incremento de productividad y sobre todo de foco.

## Conceptos básicos 

### Workspaces

*   Todo en Notion sucede dentro de un workspace, es el espacio donde podremos crear, combinar, anidar todas nuestras páginas.
*   Un workspace puede ser compartido con otros usuarios de Notion, pudiendo ver y compartir cualquier página que forme parte del mismo.
*   Podemos crear más de un workspace, para organizar nuestra información por ejemplo por temas. Notion nos permite navegar entre los distintos workspaces.

<p align="center">
    <img src="../images/Workspace-switcher.png" alt="workspace switcher">
</p>

*   Dentro de un workspace aquellas páginas compartidas de forma específica con alguno de los miembros del workspace se presentarán en el área **Shared**. El resto de miembros del workspace no tendrán acceso a dichas páginas.

![Shared](../images/shared.png "Shared")

*   Así mismo, dentro de un workspace contamos con un área **Privada**, donde podremos guardar nuestras páginas donde únicamente nosotros tendremos acceso.

![Private Space](../images/private-space.png "Private Space")
			
### Página

*   Una página en Notion es un **Canvas** limpio dentro de un workspace, donde podemos añadir el contenido que queramos.
*   Las páginas se pueden anidar creando una jerarquía.
	
![Pages](../images/pages.png "Pages")

*   Podemos compartir la visibilidad de una página. Hablaremos más adelante sobre cómo compartir y añadir colaboradores a las páginas y workspaces.

### Bloques

*   Podríamos definir un bloque como la **unidad mínima** de contenido de una página. Por ejemplo, un parágrafo, una imagen, un video, etc.
*   Otra forma de definir los bloques sería decir que son el **sistema de Lego de Notion**, permitiéndonos combinaciones casi infinitas. Nuestra imaginación es el límite.

![Blocks](../images/Blocks.png "Blocks")

*   Notion mantiene una separación de responsabilidades entre el contenido y el formateo de un bloque , lo cual nos permite **convertir un bloque en otro tipo de bloque** formateando la información en función de este nuevo tipo.
*   Más información: <a href="https://www.notion.so/What-is-a-block-e88f2d5154734d00863e1f6b97f849e5" target="_blank">What is a block?</a>

### Databases

*   Un **database** en Notion, podríamos definirlo como una estructura que nos permite organizar, filtrar, buscar, categorizar y visualizar información.
*   Existen 5 tipos de databases que podemos crear en Notion:

   *   **Lista**

    ![Database Lista](../images/Database-Lista.png "DatabaseLista")

    *   **Gallery**

    ![Database Gallery](../images/database-gallery.png "Database Gallery")

    *   **Table**

    ![Database Table](../images/database-table.png "Database Table")

    *   **Board**

    ![Database Board](../images/database-board.png "Database Board")

    *   **Calendar**

    ![Database Calendar](../images/database-calendar.png "Database Calendar")

*   Podemos crear un database como cualquier otro bloque seleccionando el tipo que más se adapte a nuestra necesidades.

    ![Database Tipos](../images/databases-tipos.png "Database Tipos")

*   Un database puede tener diferentes tipos de vistas, es decir, podemos transformar una de tipo Lista en una de tipo Gallery.

    ![List To Gallery](../images/listToGallery.gif "List to Gallery")

*   El contenido de un database se puede filtrar y ordenar.
*   Existen dos formatos: **Full page**, creando el database a página completa o **In-line**, embebida en otra página.
*   Podemos hacer referencia del contenido de un database desde otra página o database. 

![linked database](../images/linked-database.gif "linked database")

*   El contenido de un database se puede definir como un template, de modo que podamos replicar su contenido, estructura y propiedades con un solo click.

![Database Template Detalle](../images/database-template-detalle.png "Database Template Detalle")

*   Una vez definido el formato de un database, si queremos prevenir que nadie más lo cambie, podemos bloquear dicho database.

![Lock database](../images/lock-database.gif "Lock Database")

*   Notion nos permite conectar información de dos databases por medio de la propiedad **relation**, de este modo podemos linkar información de una tabla en otra tabla y relacionar el contenido de ambas databases.

![Relation](../images/relation.png "Relation")

*   Además de poder linkar información de dos databases, podemos mostrar información de un database en una columna de otra database, por medio de la propiedad **rollup.** Una vez linkeadas ambas databases, haciendo uso de la propiedad **rollup**, podemos seleccionar qué propiedad de un database mostrar en una columna del otro database.

![Rollup Column](../images/rollup-column.png "Rollup Column")

*   Más información: <a href="https://www.notion.so/Intro-to-databases-fd8cd2d212f74c50954c11086d85997e#0fd9d18ac48f43988b81e45418fae84d" target="_blank">Intro to Databases</a>

### Templates

*   Es común que después de estar un rato combinando bloques, necesitemos reutilizar el mismo formato en otra página. Los **templates** nos permitirán esencialmente hacer uso de dicho formato tantas veces como nos sea necesario.
*   Podemos en nuestras páginas replicar contenido de forma sencilla por medio de los **Template Buttons.** Seleccionando desde el listado de bloques la opción de **Template button.** Pudiendo incluso duplicar el formato de una página completa con un solo click.

![Template-button](../images/Template-button.png "Template-button")

*   Más información sobre las Template Buttons: <a href="https://www.notion.so/Create-your-own-templates-5c033c12ac3b4c1fb4703491be74550d" target="_blank">Create your own templates</a>
*   Por otro lado, la mayoría de las databases tienen contenido del mismo tipo que necesitamos reutilizar constantemente como os comentaba en el apartado anterior. Para poder reproducir este contenido una y otra vez de manera sencilla podemos hacer uso de las **Database Templates.**

![Database Template Detalle](../images/database-template-detalle.png "Database Template Detalle")

*   Más información: <a href="https://www.notion.so/Database-templates-454ed5ab5bd24226b58d176697bd7e10" target="_blank">Databases Templates</a>
*   Además de la templates que hemos comentado, Notion nos proporciona un listado de más de 50 templates que podemos usar y personalizar según nuestras necesidades. Para acceder al listado de templates podremos hacerlo desde el menú lateral, opción: **templates**.

![templates-menu](../images/templates-menu.png "templates-menu")

*   Listado completo de templates: <a href="https://www.notion.so/Notion-Template-Gallery-181e961aeb5c4ee6915307c0dfd5156d" target="_blank">Notion Template Gallery</a>
*   Otra opción que nos brinda Notion es poder hacer pública alguna de nuestras páginas para que otro usuario pueda duplicar dicha página en su workspace. Más información sobre la publicación de páginas: <a href="https://www.notion.so/Public-pages-web-publishing-9a1cbda1c1b5438390b93a7ee0f481ae" target="_blank">Public pages & web publishing</a>
*   Basado en esta idea, existe una página web donde la comunidad sube sus páginas para que las podamos usar a modo de plantilla, duplicando la página en nuestro workspace: <a href="https://notionpages.com/" target="_blank">Notion Pages ⚡️</a>

![share_page](../images/share_page.png "share_page")

## Compartir y colaborar en Notion

*   En Notion podemos compartir nuestro workspace con otros usuarios, añadiéndoles como colaboradores, pudiendo a su vez compartir, editar o colaborar en las páginas de forma conjunta. Podemos incluso añadir todos los miembros de un dominio de  forma sencilla.

![add-member](../images/add-member.png "add-member")

*   Otra forma de colaboración en Notion es compartiendo alguna de nuestras páginas o databases, pudiendo incluso hacer una página pública. Una vez compartida una página podemos gestionar los permisos sobre dicha página.
*   Las páginas las podemos compartir de forma individual o crear grupos dependiendo según la necesidad.

![sharing](../images/sharing.png "sharing")

*   Notion permite colaboración en tiempo real, cualquier colaborador puede editar el contenido de una página o databases al mismo tiempo que nosotros. Notion nos mostrará su avatar en la sección que dicho usuario esté modificando.

![realtime-collaboration](../images/realtime-collaboration.png "realtime-collaboration")

*   Dentro de todas las opciones de colaboración que nos provee Notion, podremos mencionar a una persona usando @ seguido de su nombre de usuario. 
*   Todas las páginas en Notion tienen un área donde podemos añadir comentarios anotando a otros colaboradores a modo de “**Slack**”

![discussions](../images/discussions.png "discussions")

*   Notion también nos permite añadir comentarios sobre un texto, imagen u otro bloque de una página.

![add-comments](../images/add-comments.gif "add-comments")

### Varios

*   Notion cuenta con app para escritorio, Mac y Windows así como versión móvil para iOS y Android.
*   Tanto en versión móvil como desktop podemos salvar contenido de internet directamente en alguna de las páginas de nuestro workspace. Para la versión desktop contamos con un add-on para las versiones de navegador Chrome y Firefox. Más información: <a href="https://www.notion.so/Web-Clipper-ba54b19ecaeb466b8070b9e683c5fce1" target="_blank">Web Clipper</a>.
*   Notion nos permite conectar aplicaciones de terceros, incluso facilitando el volcado de información de otras aplicaciones con Trello, Asana, Evernote…
*   Notion tiene un plan gratuito que nos permite 1000 bloques por cada workspace. Yo estoy haciendo uso tanto para temas personales y laborales y no he necesitado de momento hacer el upgrade a la versión de pago, que por otro lado tiene un precio muy razonable de 4$ al mes.

### Mejoras y opinión personal

*   Después de unos meses usando Notion, creo que todavía tiene mucho margen de mejora, pero siendo honesto el equipo de Notion está haciendo un gran trabajo.
*   Echo de menos cosas como un sistema de scripting que me permita programar cosas o una API pública que pueda usar y me dé flexibilidad para incluirlo en otras herramientas o automatizar flows dentro de la herramienta.
*   También creo que tienen cosas por mejorar, como es la experiencia de la aplicaciones desktop y nativas, así como el rendimiento de la aplicación en general, a veces los tiempos de respuesta no son buenos.
*   Y algo que echo mucho de menos ahora que tengo más contenido es un buen buscador, el actual no indexa bien el contenido y dejar de tener sentido encontrar información por medio del buscador.

## Usos y aplicaciones de Notion

Gracias a la flexibilidad que nos dan los bloques los usos y aplicaciones que le podemos dar a Notion son casi infinitos, hay gente muy creativa haciendo uso espectacular de Notion.

Os dejo por aquí alguno de los usos más comunes de Notion y alguno otro no tan común:

### Meeting Notes

![meeting-notes](../images/meeting-notes.png "meeting-notes")

### To-Do

![todo](../images/todo.png "todo")

### Wiki

![wiki](../images/wiki.png "wiki")

### Company Home

![home](../images/Home.png "home")

Estos son algunos de los usos más comunes de Notion, os dejo por aquí el link a la galería de templates de Notion que os comentaba antes: <a href="https://www.notion.so/Notion-Template-Gallery-181e961aeb5c4ee6915307c0dfd5156d" target="_blank">Notion Template Gallery</a> y el enlace a Notion Pages , donde la comunidad comparte sus templates: <a href="https://notionpages.com/" target="_blank">Notion Pages ⚡️</a>.

Antes de terminar quería aprovechar para compartir alguno de los usos que hago de Notion en mi día a día y en particular en mi actual empresa.

Hace unos días compartía un post sobre cómo es el <a href="https://xala3pa.github.io/blog/onboarding/" target="_blank">Onboarding</a> que estamos construyendo en Lookiero y comentaba que una de las herramientas que usamos para ello es Notion. 

![onboarding](../images/onboarding.png "onboarding")

Dependiendo del equipo, hemos preparado una template diferente que nos ayude a hacer tracking de cómo está yendo el proceso de onboarding, como os comentaba en el post.

![onboarding-templates](../images/onboarding-templates.png "onboarding-templates")

Otro de los usos que hago es para gestionar mis OKRs (Comentaré en un post futuro sobre los OKRs):

![OKRs](../images/OKRs.png "OKRs")

Para cada uno de los OKRs, internamente tengo una tabla donde defino el Objetivo y los Key Results. Por medio de un **Relation** vínculo cada KR con el **action item** de otra de las databases donde tengo todos mis **To-Do**.

![Key Result](../images/KR.png "Key Result")

Espero que si has llegado hasta aquí te haya resultado útil el post, como os comentaba Notion es una herramienta muy flexible de modo que encontrarás alguna manera de que encaje en tu día a día sin problemas. 

Si te ha gustado el post por favor compártelo para que le pueda llegar a más gente. ¡Muchas gracias!

<BR>
