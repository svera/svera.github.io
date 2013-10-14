---
layout: post
title: Crear un nuestro sitio en GitHub Pages
---
GitHub cuenta con un interesante servicio que nos permite alojar nuestras páginas
(estáticas) de forma gratuita llamado _GitHub Pages_. Debido a que utiliza su plataforma para la 
creación y edición, está principalmente dirigido a profesionales del sector con 
proyectos alojados en dicho servicio o con experiencia en otros similares 
como BitBucket, ProjectLocker, etc.

Para comenzar a utilizar _Pages_, lo primero que debemos hacer es, obviamente, crearnos
una cuenta en GitHub. Una vez creada, contaremos con una URL de estilo **http://_usuario_.github.io**
(donde _usuario_ es nuestro nombre de usuario).
Si introducimos esta dirección en nuestro navegador se nos mostrará un bonito error 404, 
informándonos que actualmente nuestra sitio no cuenta con contenido alguno.

Existen dos maneras de añadir contenido en nuestro recién estrenado espacio. La primera es
mediante el llamado _automatic generator_, un editor visual en el que insertamos contenido
mediante un formulario. Esta herramienta nos permite un control limitado sobre el aspecto de nuestro sitio,
así que nos centraremos en la segunda manera, que nos permite subir nuestro propio HTML.

Para ello, simplemente hemos de crear un nuevo repositorio, cuyo nombre sigue el mismo esquema de la URL, 
es decir, _usuario_.github.io. Una vez creado, simplemente tenemos que subir los archivos que queramos
a él. Tras unos minutos, nuestra flamante página estará disponible para todo aquel que acceda a 
http://_usuario_.github.io.

Por supuesto, si estas fueran todas sus posibilidades, _Pages_ no pasaría de ser un servicio de alojamiento
gratuito más. Lo verdaderamente interesante viene por la posibilidad de usar [jekyll](http://jekyllrb.com/)
para dotar a nuestro sitio con una estructura de blog a partir de archivos de texto plano y ciertas convenciones...
pero eso es materia para una próxima entrada.