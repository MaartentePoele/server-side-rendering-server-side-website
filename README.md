> Ontwerp en ontwikkel een server-side website voor een opdrachtgever
De instructie vind je in: [INSTRUCTIONS.md](https://github.com/fdnd-task/server-side-rendering-server-side-website/blob/main/docs/INSTRUCTIONS.md)

# Categoriepagina Milledoni

## Inhoudsopgave

  * [Beschrijving](#beschrijving)
  * [Gebruik](#gebruik)
  * [Kenmerken](#kenmerken)
  * [Installatie](#installatie)
  * [Bronnen](#bronnen)
  * [Licentie](#licentie)

## Beschrijving
<!-- In de Beschrijving staat kort beschreven wat voor project het is en wat je hebt gemaakt -->
<!-- Voeg een mooie poster visual toe 📸 -->
<!-- Voeg een link toe naar Github Pages 🌐-->
Check [hier](url) de website.

## Gebruik
<!--Bij Gebruik staat hoe je project er uit ziet, hoe het werkt en wat je er mee kan. -->

## Kenmerken
<!-- Bij Kenmerken staat welke technieken zijn gebruikt en hoe. Wat is de HTML structuur? Wat zijn de belangrijkste dingen in CSS? Wat is er met Javascript gedaan en hoe? Misschien heb je een framwork of library gebruikt? -->
### Loops
In mijn code gebruik ik een Liquid loop om alle cadeaus weer te geven op de pagina:
```
{% for product in products %}
    <a href="/gift/{{ product.slug }}">
      <article>
        <img class="product-image" src="{{ product.image }}" alt="">
        <h3>{{ product.name }}</h3>
      </article>
    </a>
  {% endfor %}
```

### Partials
Voor mijn website gebruik ik een partial voor de header en footer, zodat het op meerder pagina's gebruikt kan worden:
```
{% include 'partials/head.liquid' %}
{% include 'partials/foot.liquid' %}
```

## Installatie
<!-- Bij Instalatie staat hoe een andere developer aan jouw repo kan werken -->

## Bronnen

## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).
