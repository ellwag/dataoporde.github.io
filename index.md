---
layout: default
title: Home
nav_order: 1
description: "Just the Docs is a responsive Jekyll theme with built-in search that is easily customizable and hosted on GitHub Pages."
permalink: /
---

# Documentatie Datasets - Mobiliteitsonderzoek
{: .fs-9 }

Deze website dient als naslagwerk voor de datasets die beschikbaar zijn binnen het team Mobiliteitsonderzoek
(“MBZ”) van Gemeente Utrecht. Deze documentatie biedt een overzicht van de verschillende datasets die
gebruikt worden, de modaliteiten en afhankelijkheden binnen mobiliteitsonderzoek
{: .fs-6 .fw-300 }

[Instructies en Toelichting](#instructies-en-toelichting){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 }
[View it on GitHub][Just the Docs repo]{: .btn .fs-5 .mb-4 .mb-md-0 }

---

Elke sectie van dit document biedt informatie over de herkomst, het gebruik, de opslag en de transformaties van de data. Tevens worden de datakwaliteit, potentiële verrijkingsmogelijkheden en de relaties tussen verschillende datasets besproken. Om het daadwerkelijke gebruik van de datasets te begrijpen kan je via de handleiding secties onder de dieper in het gebruik van de datasets duiken.

Het doel van deze documentatie is om een volledig beeld te geven van de datasets en hun kenmerken. Om dieper in te gaan op het praktische gebruik van de datasets, bieden de handleiding-secties gedetailleerde instructies. Deze secties zijn ontworpen om gebruikers  (waar mogelijk) te begeleiden bij het werken met de data, van basis query's tot analyses. Ze bevatten praktische voorbeelden, tips voor analyses en richtlijnen voor het optimaal benutten van de beschikbare gegevens.



## Instructies en Toelichting

Voor iedere dataset komen de volgende onderwerpen aanbod:

1. **Herkomst van de data**: In deze sectie wordt de oorsprong van de datasets belicht. Er wordt ingegaan op de bronnen waaruit de gegevens zijn verzameld, of het nu gaat om interne systemen, externe leveranciers, of publieke databronnen. Ook wordt er aandacht besteed aan de frequentie waarmee de data wordt bijgewerkt en de betrouwbaarheid van de bronnen.
2. **Gebruik van de data**: Hier wordt uitgelegd hoe de datasets in de praktijk worden toegepast. Er worden voorbeelden gegeven van specifieke use cases, analyses en rapporten waarvoor de data wordt ingezet. Daarnaast worden de belangrijkste stakeholders en eindgebruikers van de data geïdentificeerd.
3. **Opslag van de data**: Deze sectie beschrijft de technische aspecten van dataopslag. Er wordt ingegaan op de gebruikte databases of datawarehouses, de formaten waarin de data wordt opgeslagen, en de beveiligingsmaatregelen die zijn getroffen om de integriteit en vertrouwelijkheid van de gegevens te waarborgen.
4. **Transformaties van de data**: Hier worden de verschillende bewerkingen en transformaties beschreven die de ruwe data ondergaat voordat deze wordt gebruikt. Dit kan variëren van eenvoudige opschoningsprocessen tot complexe calculaties. Er wordt ook aandacht besteed aan de tools en technieken die hiervoor worden ingezet.
5. **Datakwaliteit**: In deze sectie worden de maatregelen en processen besproken die zorgen voor de kwaliteit van de data. Er wordt ingegaan op aspecten zoals accuraatheid, volledigheid, consistentie en tijdigheid van de gegevens. Ook worden eventuele bekende kwaliteitsproblemen en de aanpak daarvan besproken.
6. **Potentiële verrijkingsmogelijkheden**: Hier worden mogelijkheden verkend om de waarde van de datasets te vergroten. Bijvoorbeeld door het combineren van andere interne of externe databronnen.
7. **Relaties tussen verschillende datasets**: Deze sectie belicht de onderlinge verbanden en afhankelijkheden tussen de verschillende datasets. Er wordt uitgelegd hoe de datasets met elkaar samenhangen en hoe ze gezamenlijk kunnen worden gebruikt om een nog betere analyses te kunnen uitvoeren.

{: .note }

Dit document is continu in ontwikkeling. De inhoud wordt regelmatig bijgewerkt om de meest recente informatie over datasets weer te geven. Als u merkt dat bepaalde secties verouderd zijn, informatie mist, of als u suggesties heeft voor verbeteringen, neem dan contact op met:<br> Elliot Wagner, E-mail: [elliot.wagner@utrecht.nl](mailto:elliot.wagner@utrecht.nl). Aarzel niet om vragen, opmerkingen of voorstellen voor aanvullingen door te geven. 



You can easily set the site created by the template to be published on [GitHub Pages] – the [template README] file explains how to do that, along with other details.

If [Jekyll] is installed on your computer, you can also build and preview the created site *locally*. This lets you test changes before committing them, and avoids waiting for GitHub Pages.[^2] And you will be able to deploy your local build to a different platform than GitHub Pages.

{: .warning }

> This website documents the features of the current `main` branch of the Just the Docs theme. See [the CHANGELOG]({% link CHANGELOG.md %}) for a list of releases, new features, and bug fixes.

More specifically, the created site:

- uses a gem-based approach, i.e. uses a `Gemfile` and loads the `just-the-docs` gem
- uses the [GitHub Pages / Actions workflow] to build and publish the site on GitHub Pages

Other than that, you're free to customize sites that you create with the template, however you like. You can easily change the versions of `just-the-docs` and Jekyll it uses, as well as adding further plugins.

{: .note }
See the theme [README][Just the Docs README] for how to use the theme as a gem without creating a new site.

## About the project

Just the Docs is &copy; 2017-{{ "now" | date: "%Y" }} by [Patrick Marsceill](https://patrickmarsceill.com).

### License

Just the Docs is distributed by an [MIT license](https://github.com/just-the-docs/just-the-docs/tree/main/LICENSE.txt).

### Contributing

When contributing to this repository, please first discuss the change you wish to make via issue,
email, or any other method with the owners of this repository before making a change. Read more about becoming a contributor in [our GitHub repo](https://github.com/just-the-docs/just-the-docs#contributing).

#### Thank you to the contributors of Just the Docs!

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"></a>
  </li>
{% endfor %}
</ul>

### Code of Conduct

Just the Docs is committed to fostering a welcoming community.

[View our Code of Conduct](https://github.com/just-the-docs/just-the-docs/tree/main/CODE_OF_CONDUCT.md) on our GitHub repository.

----

[^1]: The [source file for this page] uses all three markup languages.

[^2]: [It can take up to 10 minutes for changes to your site to publish after you push the changes to GitHub](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll#creating-your-site).

[Jekyll]: https://jekyllrb.com
[Markdown]: https://daringfireball.net/projects/markdown/
[Liquid]: https://github.com/Shopify/liquid/wiki
[Front matter]: https://jekyllrb.com/docs/front-matter/
[Jekyll configuration]: https://jekyllrb.com/docs/configuration/
[source file for this page]: https://github.com/just-the-docs/just-the-docs/blob/main/index.md
[Just the Docs Template]: https://just-the-docs.github.io/just-the-docs-template/
[Just the Docs]: https://just-the-docs.com
[Just the Docs repo]: https://github.com/just-the-docs/just-the-docs
[Just the Docs README]: https://github.com/just-the-docs/just-the-docs/blob/main/README.md
[GitHub Pages]: https://pages.github.com/
[Template README]: https://github.com/just-the-docs/just-the-docs-template/blob/main/README.md
[GitHub Pages / Actions workflow]: https://github.blog/changelog/2022-07-27-github-pages-custom-github-actions-workflows-beta/
[customize]: {% link docs/customization.md %}
[use the template]: https://github.com/just-the-docs/just-the-docs-template/generate
