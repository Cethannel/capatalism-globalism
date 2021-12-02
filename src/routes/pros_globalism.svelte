<script lang="ts">
  import Writeup from '../components/Writeup.svelte';
  import Item from '../components/Item.svelte';

  let baseImagePath = 'ProsGlob/';
</script>

<Writeup>
  <Item>
    <div slot="left">
      The graph to the right shows the amount of involvement each country has
      with globalization. The giant countries like the U.S, Japan, Russia,
      China, and India are at the bottom. Small countries like Ireland,
      Netherlands, Belgium, and the UK are receiving the most help over the
      years.
    </div>
    <div slot="right">
      <img src="{baseImagePath}graph.png" alt="Very pretty graph" />
    </div>
  </Item>
  <Item>
    <div slot="left">
      Out of 42 countries studied about the effects of globalization, all 42 had
      in increase of GDP per capita from 1990 to late 2010s
      <ul>
        <li>Japan highest income gains</li>
        <li>Finland highest average per capita income gains</li>
      </ul>
    </div>
    <div slot="right" />
  </Item>
  <Item>
    <div slot="left">
      Here is an example of how globalization affected Germany and how much
      growth the nation owes to it.
    </div>
    <div slot="right">
      <img src="{baseImagePath}quote.png" alt="Quote" />
    </div>
  </Item>
  <Item>
    <div slot="left">
      Through the effects of increased GDP per capita and QOL, better
      communities and societies are made.
      <ul>
        <li>Cultural Mixing</li>
        <li>Spread of better technologies and innovation</li>
      </ul>
    </div>
    <div slot="right" />
  </Item>
  <Item>
    <div slot="left">
      <a href="http://aei.pitt.edu/73921/1/2014.1.pdf"
        >Who really benefits from globalization</a
      >
    </div>
    <div slot="right" />
  </Item>
  <Item>
    <div slot="left">
      <a
        href="https://ged-project.de/globalization/globalization-report-2018-who-benefits-most-from-globalization"
        >Globalization Report 2018: Who Benefits Most from Globalization?</a
      >
    </div>
    <div slot="right" />
  </Item>
  <Item>
    <div slot="left">
      <a
        href="https://www.charitynavigator.org/index.cfm?bay=content.view&cpid=42"
        >With so much money, global corporations donate a lot of money to
        charities</a
      >
      <ul>
        <li>In 2017, almost 21 billion dollars were donated</li>
      </ul>
    </div>
    <div slot="right" />
  </Item>
  <Item>
    <div slot="left">
      <a
        href="https://www.cnn.com/2020/11/16/business/amazon-jeff-bezos-earth-fund-scn-trnd/index.html"
        >In 2020, Jeff Bezos donated almost 800 million dollars to various
        climate change organizations</a
      >
    </div>
    <div slot="right" />
  </Item>
  <Item>
    <div slot="left">
      <a
        href="https://www.cambridge.org/core/journals/world-politics/article/multinational-corporations-and-politics-in-developing-countries/8A6A2DEA581973407BD893BBB70A9E0B"
        >Multinational corporations, depending on which country they spread in,
        offer increasing help in political struggles, either with donations or
        sheer resources</a
      >
    </div>
    <div slot="right" />
  </Item>
</Writeup>

<style lang="scss">
  @import '../styles/Writing.scss';
</style>
