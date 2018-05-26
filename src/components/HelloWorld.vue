<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Christian William Et Samuel Christie</h2>
    <h3>OCinfo Sismondi 2017-2018</h3>
    <h4> Merveille du monde </h4>
    <h5> Cliquez sur les liens ci-dessous et vous verrez de belles photos </h5>
    <p>
    <img src="http://www.clker.com/cliparts/Z/v/l/v/f/n/camera-logo-md.png" alt = "logo"/>
    </p>
   <ul>
      <li>
        <a
          href="https://www.parisinfo.com/var/otcp/sites/images/media/1.-photos/02.-sites-culturels-630-x-405/tour-eiffel-trocadero-630x405-c-thinkstock/37221-1-fre-FR/Tour-Eiffel-Trocadero-630x405-C-Thinkstock.jpg"
          target="_blank"
        >
          Tour Eiffel
        </a>
        <p> Voici le lien pour la tour Eiffel !<br/>
        Elle a été construite en 1889 pour l'exposition universel et mesure plus de 300 mètre.</p>
      </li>
      <li>
        <a
          href="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1d/Taj_Mahal_%28Edited%29.jpeg/1200px-Taj_Mahal_%28Edited%29.jpeg"
          target="_blank"
        >
          Taj Mahal
        </a>
        <p> Voici le lien pour le Taj Mahal !</p>
      </li>
      <li>
        <a
          href="https://www.llamatravel.com/media/image-cache/07a52fe1-feda-4301-b099-82e65df58e12/900-0-1-2310-1276/1502466643-1502466626-1472814703-1472814695-1450193463-llama-at-machu-picchu-peru.jpg"
          target="_blank"
        >
          Machu Picchu
        </a>
        <p> Voici le lien pour le Machu Picchu !</p>
      </li>
      <li>
        <a
          href="http://www.fondsecran.eu/pictures/2013/1224/1/statue-of-jesus-rio-de-janeiro-wallpaper-6049.jpg"
          target="_blank"
        >
          Chris Rédempteur
        </a>
        <p> Voici le lien pour le Chris Rédempteur!</p>
      </li>
      <br>
      <li>
        <a
          href="https://crm48.com/wp-content/uploads/2016/11/912579831_Pyramides_Gizeh.jpg"
          target="_blank"
        >
          Pyramides de Gizeh
        </a>
        <p> Voici le lien pour la Pyramides de Gizeh !</p>
      </li>
      <li>
        <a
          href="https://www.nationalgeographic.com/content/dam/archaeologyandhistory/rights-exempt/history-magazine/2016/01-02/petra/Petra-opener.jpg"
          target="_blank"
        >
          Pétra
        </a>
        <p> Voici le lien pour Pétra!</p>
      </li>
      <li>
        <a
          href="https://upload.wikimedia.org/wikipedia/commons/thumb/8/8d/El_Castillo_Stitch_2008_Edit_1.jpg/1200px-El_Castillo_Stitch_2008_Edit_1.jpg"
          target="_blank"
        >
          Chichén Itzá
        </a>
        <p> Voici le lien pour le Chichén Itzá !</p>
      </li>
      <li>
        <a
          href="https://www.voyagevietnam.co/wp-content/uploads/2017/12/Principales-raisons-de-visiter-Angkor-Wat.jpg"
          target="_blank"
        >
          Angkor
        </a>
        <p> Voici le lien pour le Angkor!</p>
      </li>
      <li>
        <a
          href="https://upload.wikimedia.org/wikipedia/commons/thumb/4/42/Kiyomizu-dera_in_Kyoto-r.jpg/1200px-Kiyomizu-dera_in_Kyoto-r.jpg"
          target="_blank"
        >
          Kiyomizu-dera
        </a>
       <p> Voici le lien pour le Kiyomizu-dera!</p>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Bienvenue sur notre site web'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 16px;
}
a {
  color:red;
}
</style>
