<script>
  import {lang} from '../stores.js'
</script>

<div class="card flex flex-col justify-center items-center">
  <div class="card-title h1 p-2">
    {#if $lang == "en"}
      ABOUT
    {:else if $lang == "fr"}
      SUR CE SITE
    {/if}
  </div>
  <div class="card-body flex flex-col justify-center items-center">
    <p class="w-3/4 py-2">
      {#if $lang == "en"}
        My name is Naémie, I’m a film student and I wanted to do this project
        because i was afraid for my future, the close future. So I left school
        for a year and began my journey.
      {:else if $lang == "fr"}
        Je m’appelle Naémie, je suis une étudiante en cinéma et je voulais
        commencer ce projet, parce que j’avais peur, peur pour mon futur. J’ai
        donc arrêté la fac pendant un an et j’ai commencé ce projet.
      {/if}
    </p>
    <hr />
    <p class="w-3/4 py-2">
      {#if $lang == "en"}
        Climate change is the battle of our century and we still have a chance
        to make a change. It’s also an opportunity to rethink our connection to
        the world and suppress social inequalities, which are at the center of
        climate change.
      {:else if $lang == "fr"}
        Le changement climatique est le combat de ce siècle, and nous avons
        encore une chance de faire changer les choses. C’est aussi une
        opportunité pour repenser notre connexion au monde et supprimer les
        inégalités sociales, qui sont au centre du changement climatique. Il y a
        besoin d’une prise de conscience de mass sur ce que nous risquons
        d’affronter, alors regarder le documentaire et partager le à d’autres !
      {/if}
    </p>
    <hr />
    <p class="w-3/4 py-2">
      {#if $lang == "en"}
        We need more awareness on what we are facing. So watch this and share it
        with others ! This production is completely indepedent and I want to say
        a big thanks to all the donors to the crowd-funding and to my family for
        the support. Thank you.
      {:else if $lang == "fr"}
        Cette production est complètement indépendante et je veux remercier les
        donateurs du financement participatif qui ont rendu ce projet possible
        et ma famille pour leurs soutiens. Merci.
      {/if}
    </p>
  </div>
</div>
