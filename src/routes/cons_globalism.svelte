<script lang="ts">
  import Writeup from '../components/Writeup.svelte';
  import Item from '../components/Item.svelte';

  let baseImagePath = 'ConsGlob/';
</script>

<Writeup>
  <div slot="heading"><h1>CONS OF GLOABLISM</h1></div>
  <Item>
    <div slot="left">
      Loss of jobs/wages, unbalance between countries, Diseases, stealing of
      technology between countries which also leads to bad relations between
      said countries, different tax rates in different countries makes it easier
      for international countries to pay less in taxes, businesses increasingly
      affecting political decisions across the globe, ruining the environment.
    </div>
  </Item>
  <h1 class="inner_heading">Economic:</h1>
  <Item>
    <div slot="left">
      Higher productivity (value/cost), difference going to higher up executives
      and investors. Companies are also offshoring more money in order to bypass
      the tax laws of their countries.
    </div>
  </Item>
  <Item>
    <div slot="left">
      The chart to the left shows the &percnt; of value distributed to various
      places after the selling of an iPhone in 2010. Notice how the cost of the
      inputs is about 25&percnt;, and the vast majority of it is the cost of the
      materials. The labor cost is roughly 5&percnt;, nothing compared to the
      profits that Apple rakes in. The cost of the newest iphone in 2010 was
      200$ for a 16GB model, or 300$ for a 32GB model, so 5&percnt; of that
      would be about 10$ and 15$ respectively. Would you agree with being paid
      that amount for the assembly of one iphone?
    </div>
    <div slot="right">
      <img src="{baseImagePath}piechart.png" alt="Pie Chart" />
    </div>
  </Item>
  <Item>
    <div slot="left">
      "From 1979 to 2020, net productivity rose 61.8%, while the hourly pay of
      typical workers grew far slower—increasing only 17.5% over four decades
      (after adjusting for inflation)." (Economic Policy Institute, 2021)
    </div>
  </Item>
  <Item>
    <div slot="left">
      The table to the left shows the percentages of reserves of various
      companies that are held in offshore tax havens. In total, 81.5&percnt; of
      all reserves of those companies are held offshore.
    </div>
    <div slot="right">
      <img
        src="{baseImagePath}taxHavens.png"
        alt="Table of taxhaven holdings"
      />
    </div>
  </Item>
  <h1>Social</h1>
  <Item>
    <div slot="left">
      The existence of sweatshops in other countries allows for exploitation and
      underpayment of employees in general as well as large wage differences
      between workers of one country and those of another, despite similar
      productivity. In addition to this, working conditions in a lot of
      countries are poor, such as fainting during work, and not having suitable
      shelter or necessities.
    </div>
  </Item>
  <Item>
    <div slot="left">
      The table to the left details the productivity of a worker in various
      countries in various years. Notice how all numbers are above 1.
    </div>
    <div slot="right">
      <img
        src="{baseImagePath}productivity.png"
        alt="Table of productivity per worker."
      />
    </div>
  </Item>
  <Item>
    <div slot="left">
      "A cleated gangplank runs from the alleyway up to the raised dilapidated
      shelter that houses all 11 members of the immediate family. A covered
      area, opened on one side to the outside, provides a gathering space for
      cooking and washing. Behind, two adjoining rooms sleep eight in one room,
      three in the other. There is power, as the hysteria of wires running
      through one room attests. There is no running water. A damp thickness of
      refuse carpets the ground below, nuzzled at the moment by an enormous
      rat.... Neang pays a monthly rent of $30 (U.S.) for the shanty. The
      monthly utilities total 75,000 riels, or about $18. (Cambodian Centre for
      Human Rights, 2014: 15–16)16" (Selwyn, 2019, 86).
      <p>
        These are some of the things to expect when working textiles in
        Cambodia. The conditions that workers can afford are abysmal, and are
        just barely livable. Companies outsource these labor shops, where laws
        stopping exactly this kind of work aren’t in effect, in order to turn a
        higher profit. While this is more of a case where a country needs to
        improve, it still shows the predatory nature of globalism under
        capitalism, where other developing countries are used by wealthy
        companies in the U.S. in order to pay workers nothing while still
        getting their product out.
      </p>
    </div>
  </Item>
  <Item>
    <div slot="left">
      The Chinese electronics industry and the Cambodian textile industry both
      show that workers in these sectors are "(1) highly productive, (2) receive
      base wages that are insufficient to meet their individual let alone their
      dependents' social reproduction requirements, (3) are required by firms
      (often by force) and by economic necessity (as a consequence of
      insufficient base wages) to undertake large amounts of overtime, and as a
      consequence of 1–3 are (4) physically and emotionally degraded." (Selwyn,
      2019, 84). This makes avoiding poverty impossible for workers in other
      countries.
    </div>
  </Item>
  <Item>
    <div slot="left">
      Once in poverty, very bad things happen: Research has consistently shown
      that, "individuals from low-income families in highly developed countries
      are at increased risk for being OWOB [7, 8]. Similarly, adolescents [9,
      10] and adults [11, 12] in the US from low-income families are at a higher
      risk of being OWOB than their higher income counterparts."" (Weaver,
      Brazendale, Hunt, Sarzynski, Beets, White, 2019, 1-2)
    </div>
  </Item>
  <Item>
    <div slot="left">
      Obesity, Tuberculosis, substance abuse, and suicide all are much more
      common among homeless populations, who are the ones who are at the worst
      part of globalism. While not all poverty will result in homelessness,
      homelessness in itself is a symptom of workers not being paid enough to
      afford housing.
    </div>
  </Item>
  <Item>
    <div slot="left">
      The table to the left details that monthly food intake for Cambodian
      textile workers are vastly under what they need to be, as of 2013. Almost
      every quantity of food needed for a healthy diet is under what it needs to
      be, and the overall calorie count is nearly half the recommended value.
      These are basic human needs being taken away from these people in exchange
      for more money for huge companies. The profits must come from someone, and
      it has to either be the worker being exploited, or the consumer over
      paying.
    </div>
    <div slot="right">
      <img src="{baseImagePath}food.png" alt="Food" />
    </div>
  </Item>
  <Item>
    <div slot="left">
      Working conditions for Chinese workers in the electronic sector are also
      dire.Workers at Compeq reported that they “need to apply dangerous
      chemical agents including copper sulfate, sulfuric acid, nitric acid,
      paint, cleaning-machine solvent, thinner, industrial alcohol and
      gold-coating agent”. Many workers suffer skin problems as a result (SACOM,
      2008: 29; see also China Labour Watch, 2011). “The documentary film
      Complicit highlights the proliferation of occupational Leukemia in China’s
      electronics industry.” (Selwyn, 2019, 87) Not only are workers not being
      paid enough, but in addition, they are being exposed to chemicals,
      overworked in the form of overtime, and unable to secure a place to live
      or food to eat.
    </div>
  </Item>
  <h1>Political</h1>
  <Item>
    <div slot="left">
      Lobbying is worse now than ever, which is affecting extremely important
      political decisions due to huge corporations having vast amounts of
      wealth. If you want to play around with it, there’s actually another
      website you can go to that tracks this called <a href="http://opensecrets.org"
        >opensecrets.org</a
      >. Here’s some important people who have taken loads of money from
      industries that are generally seen as corrupt:
      <ul>
        <li>Joe Manchin (D/WV/Senate) - $577,060 from Oil and Gas companies</li>
        <li>
          Joe Biden (D/President) - $1,369,458 from Lawyers and Law firms.
        </li>
        <li>
          Charles E Schumer (D/NY/Senate) - $222,433 from Pharmaceutical/Health
          Product companies
        </li>
        <li>
          Charles E Schumer (D/NY/Senate) - $114,051 from Airline companies
        </li>
      </ul>
    </div>
  </Item>
  <Item>
    <div slot="left">
      The point is, companies can abuse their workers, and then using the money
      they made from doing that, can buy off people in power so that they can
      continue to make money in that way.
    </div>
  </Item>
  <h1>Environmental</h1>
  <Item>
    <div slot="left">
      Destroying the environment due to global warming. The cons of capitalism
      cover this as well, but some food for thought is nice.
      <ul>
        <li>
          Logically, globalism creates a lot of greenhouse gases, due to the
          cost of transporting products from other countries to the U.S.
        </li>
        <li>
          Companies are also disentivised from following a carbon tax if they
          can just pollute in other countries instead.
        </li>
      </ul>
    </div>
  </Item>
  <Item>
    <div slot="left">
      Any Next Steps?
      <ul>
        <li>
          There is no preventing globalization, it’s already happened and will
          continue to happen. The best thing to do is to be more strict on
          policies from the U.S. applying to companies based in the U.S., even
          if they operate in other countries.
        </li>
      </ul>
    </div>
  </Item>
</Writeup>

<style lang="scss">
  @import '../styles/Writing.scss';

  .inner_heading {
    text-align: left;
  }

  hr {
    border-top: 1px solid lightgray;
    width: 97%;
    margin-left: 0;
  }
</style>
