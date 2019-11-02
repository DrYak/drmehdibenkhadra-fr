---
title: Contacter
description: Me contacter
permalink: contact
order: 5
---

## {{ page.description }}

Je reçois uniquement sur rendez-vous.

Vous pouvez me contactez :

{: .fa-ul}

- <span><i></i>{: .fa .fa-phone}</span>{: .fa-li}
  Par téléphone : [{{ site.phone | replace: "+33-", "+33(0)" | replace: "-", "." }}](tel:{{ site.phone | replace: "-", "" }})

  N’hésitez pas à laisser un message si je ne peux pas répondre
  (je serai peut-être en rendez-vous ou en intervention).
  Je vous rappellerai au plus vite.

- <span><i></i>{: .fa .fa-envelope}</span>{: .fa-li}
  Par courriel : [{{ site.email }}](mailto:{{ site.email }})

- <span><i></i>{: .fa .fa-address-card}</span>{: .fa-li}
  Carnet d'addresses : [Ajouter le contact](drmehdibenkhadra.vcf)

{% include social.html %}
