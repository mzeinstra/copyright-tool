<template>
  <div
    class="container"
  >
    <div class="column-result">
      <div class="container container-small padding-top-null">
        <h1>Colofon &amp; disclaimer</h1>
        <p>Regeljerechten.nl is een beslismodel auteursrechten. Het is een hulpmiddel bij het uitzoeken en clearen van auteursrechten op werken in collecties. Het is met de grootste zorg ontwikkeld. Aan de uitkomsten kunnen geen rechten worden ontleend; gebruikers worden er dan ook op gewezen dat ze zelf verantwoordelijk blijven voor het op een juiste manier regelen van de rechten.</p>
        <p>Het Netwerk Digitaal Erfgoed (NDE) kan niet aansprakelijk worden gesteld voor fouten, technische storingen, incidenten en problemen die het gevolg kunnen zijn van toegang en/of het gebruik van regeljerechten.nl en daaruit voortvloeiende schade.</p>

        <h2>Ontwikkeling</h2>
        <p>Regeljerechten.nl is in 2020 ontwikkeld binnen het NDE, in samenwerking met juridisch deskundigen van de KB, nationale bibliotheek, Het Utrechts Archief, Erfgoed Leiden en Omstreken, Rijksdienst voor het Cultureel Erfgoed, Beeld & Geluid, Eye Filmmuseum en DEN Kennisinstituut cultuur & digitale transformatie. Sezen Kapan heeft meegewerkt als auteursrecht jurist en projectmedewerker. <a href="https://ip-squared.com">Maarten Zeinstra</a> heeft in 2025 de inhoud van het platform geüpdatet.</p>

        <h2>Websites van derden</h2>
        <p>
          De websites van derden waarnaar op deze website hyperlinks zijn opgenomen, worden niet door het NDE gecontroleerd, gemaakt of onderhouden. Het NDE aanvaardt dan ook geen aansprakelijkheid voor de inhoud van die websites. Mocht een hyperlink niet meer werken, geef dit dan door via <a href="mailto:info@netwerkdigitaalerfgoed.nl">info@netwerkdigitaalerfgoed.nl</a>.
        </p>

        <h2>Persoonlijke gegevens</h2>
        <p>
          Regeljerechten.nl gebruikt cookies, maar deze bevatten alleen sessiegegevens, bijvoorbeeld hoe lang je een pagina bekijkt, geen persoonsgegevens.
        </p>

        <h2>Auteursrechten</h2>
        <p>
          De teksten van regeljerechten.nl zijn beschikbaar onder de <a href="https://creativecommons.org/licenses/by/4.0/deed.nl" target="_blank">Creative Commons Naamsvermelding-GelijkDelen 4.0 Internationaal-licentie</a>, tenzij anders aangegeven bij specifieke materialen.
        </p>

        <h2>
          Technische details
        </h2>
        <p>
          Regeljerechten.nl is een opensourceproject en ontwikkeld door <a href="https://mirjamverloop.nl/" target="_blank">Mirjam Verloop</a> in JavaScript met behulp van het Vue framework. De code is beschikbaar via Github en gepubliceerd onder de EUPL v1.2-licentie.
        </p>
        <p>
          Het beslismodel is getest in de meest recente versies van Chrome, Firefox, Edge en Safari. Daarnaast is het beslismodel met behulp van Axe getoetst op de WCAG 2.1-toegankelijkheidsrichtlijnen.
        </p>

        <h2>Contact</h2>
        <p>Heb je vragen of opmerkingen, stuur dan een mail naar <a href="mailto:info@netwerkdigitaalerfgoed.nl">info@netwerkdigitaalerfgoed.nl</a>.</p>


        <div class="buttons">
          <router-link to="/" @click.native="scrollToTop" tag="button" class="btn">
            Terug naar de homepagina
          </router-link>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  import { useHead } from '@vueuse/head';

  export default {
    created() {
      useHead({
        title: 'Colofon'
      });
    },

    methods: {
      scrollToTop() {
        window.scrollTo(0, 0);
      }
    }
  };
</script>
