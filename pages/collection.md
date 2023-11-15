---
layout: page
title: Navega la colección
permalink: /collection/
---

Navega la colección de imágenes por distintos tipos de categorías. Haz clic en un ítem de la colección para ver una imagen ampliada e información sobre la obra.

#### Por autor
{% include collection_gallery.html facet_by='nombre_completo' collection='comics' %}

#### Por fecha
{% include collection_gallery.html facet_by='anno' collection='comics' %}

#### Por categoría
{% include collection_gallery.html facet_by='categoria' collection='comics' %}

#### Por publicación
{% include collection_gallery.html facet_by='publicacion' collection='comics' %}
