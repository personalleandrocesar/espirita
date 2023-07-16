
<template>
  <div>
    <Nav />
    <div class='anima'>
      <div class='profile'>
        <img src='/img/myFotoTwo.jpg' alt=''>
        <div>
          <h1>Personal Leandro Cesar</h1>
          <h4><Icon name="ooui:user-group-ltr" /> Professor de Educação Física</h4>
        </div>
      </div>

      <div class='main-one'>
        <a href="https://instagram.com/personalleandrocesar">
          <Icon name="ooui:user-group-ltr" /> Instagram/personalleandrocesar
        </a>

        <a>
          <Icon name="solar:square-academic-cap-2-bold" /> Graduação em Educação Física
        </a>
        <a>
          <Icon name="ph:identification-card-fill" /> CREF: 029260-G/RJ
        </a>

        <a href="http://lattes.cnpq.br/3830820363501969">
          <Icon name="ph:files-bold" /> Currículo Lattes
        </a>
      </div>

      <div class='divider'></div>

      <div class='main-two'>
        <code>
              <b>#vemtreinarcomigo</b>
              <br>
              Bora treinar junto! 
            </code>
        <a
          href='https://api.whatsapp.com/send?phone=5521936184024%20&text=Ol%C3%A1%20Leandro%20Cesar,%20fiquei%20interessado(a)%20na%20sua%20Consultoria%20e%20nos%20seus%20Servi%C3%A7os,%20me%20chamo%20'>
          <Icon name="fa6-brands:square-whatsapp" /> Marcar Horário
        </a>
      </div>

      <div class='divider'></div>
      <div class='main-tree'>
        <div>
          <ArrowsRight />
          <h5><Icon name="material-symbols:person-play-rounded"/> Serviços</h5>
        </div>
      </div>

      <div class='main-four'>

        <h5>
          Clique em um dos serviços abaixo! 👇
        </h5>
      </div>
      <div class='main-five'>

        <NuxtLink to='/personal' @click.native="scrollToTop()">

          <div class='main-five-card'>
            <div>
              <img src='/img/myFotoTwo.jpg' alt='' class='mini-profile'>
              <p><Icon name="ooui:user-group-ltr" /> Serviço presencial</p>
            </div>
            <div>
              <h4>Personal Trainer</h4>
              <h5>R$ 50,00 hora/aula</h5>
              <p>Serviço de treinamento particular, individualizado em academias; </p>
            </div>
          </div>
        </NuxtLink>
        <NuxtLink to='/consultoria' @click.native="scrollToTop()">

          <div class='main-five-card'>
            <div>
              <img src='/img/myFotoTwo.jpg' alt='' class='mini-profile'>
              <p>Serviços:<br> <Icon name="ooui:user-group-ltr" /> presencial <br>+<br><Icon name="solar:smartphone-bold" /> Digital </p>
            </div>
            <div>
              <h4>Consultoria Online +<br> Avaliação Física (Gratuita)</h4>
              <h5>A partir de R$ 40,00 mensais</h5>
              <p>Séries individuais em aplicativo para treinamento em academias + avaliação física presencial gratuita;
              </p>
            </div>
          </div>
        </NuxtLink>
        <NuxtLink to='/avaliacao' @click.native="scrollToTop()">

          <div class='main-five-card'>
            <div>
              <img src='/img/myFotoTwo.jpg' alt='' class='mini-profile'>
              <p><Icon name="ooui:user-group-ltr" /> Serviço presencial</p>
            </div>
            <div>
              <h4>Avaliação Fisica</h4>
              <h5>R$ 40,00</h5>
              <p>Avaliação Antropométrica, com percentual de gordura feita com dobras cutâneas ou com balança de
                bioimpedância;</p>
            </div>
          </div>
        </NuxtLink>
        <NuxtLink to='/kravmaga' @click.native="scrollToTop()">

          <div class='main-five-card'>
            <div>
              <img src='/img/myFotoTwo.jpg' alt='' class='mini-profile'>
              <p><Icon name="ooui:user-group-ltr" /> Serviço presencial</p>

            </div>
            <div>
              <h4>Krav-Maga</h4>
              <h5>R$ 70,00 hora/aula</h5>
              <p>Treinamento individual ou em grupo de defesa pessoal, criado por Imi Lichtenfeld; Escola Bukan de
                Krav-maga;</p>
            </div>
          </div>
          <br>
        </NuxtLink>
        <br>
      </div>

      <div class='divider'></div>
    </div>
    <NavBottomTwo />
  </div>
</template>
<script>
export default {
  methods: {
    scrollToTop() {
      window.scrollTo(0, 0);
    }
  }
}

</script>

<style scoped>
a {
  text-decoration: none;
  color:  var(--color-text);
}

i {
  color:  var(--color-text);
  font-size: .9em;
  margin: auto;
}

code {
  font-size: 0.8em;
  padding-left: 10px;
  border-left: solid 5px var(--color-text);
  color: var(--color-text);
  margin-left: 10px;
}

.divider {
  height: 15px;
  background-color: var(--color-background);
}

.divider-ultimate {
  height: 30px;
  background-color: var(--color-background);
}

.profile {
  background: var(--color-background); 
  display: flex;
  justify-content: flex-start;
  flex-wrap: wrap;
  padding: 20px 0 5px 0;
  margin-top: -10px;
}

.profile a {
  text-decoration: none;
  color: var(--color-background); 
  font-size: .9em;
}

.profile img {
  height: 70px;
  border-radius: 50%;
  margin-left: 10px;
  margin-right: -20px;
  padding: 0 25px 0 0;
}

.profile h1 {
  margin: 5px 0 0 10px;
  font-size: 1.5em;
  color: #fadb41;
}

.profile h4:nth-child(2) {
  margin: 0 0 0 10px;
  font-size: .9em;
  font-weight: 100;
  color: var(--color-text);
}

.profile h4 {
  margin: 0 0 0 -10px;
  font-size: .9em;
  font-weight: 100;
  color:  var(--color-text);
}

.main-one {
  display: flex;
  justify-content: flex-start;
  flex-direction: column;
  padding: 10px 0 15px 0;
  box-shadow: 0px 10px 5px var(--color-text);
  background: var(--color-background); 
}

.main-one div {
  margin: 0 0 0 15px;
}

.main-one a i {
  padding-right: 4px;
  margin: 0 0 0 3px;
}

.main-one a:nth-child(2) i {
  padding-right: 0px;
  margin: 0 0 0 3px;
}

.main-one a {
  margin: 0 0 0 10px;
  color:  var(--color-text);
}

.main-two {
  display: flex;
  justify-content: space-around;
  flex-direction: row;
  padding: 15px 0 18px 0;
  color: var(--color-text);
  background: var(--color-background); 
  color: var(--color-background); 
}

.main-two a {
  margin: 20px 0 0 0px;
  color:  var(--color-text);
  font-weight: 600;
}

.main-two a:hover {
  color: #fadb41;
}

.main-two i {
  color:  var(--color-text);
  font-size: 1.1em;
  font-weight: 600;
}

.main-tree {
  display: flex;
  justify-content: flex-start;
  flex-direction: column;
  margin: 0px 0 0 0;
  color:  var(--color-text);
  background: var(--color-background); 
  overflow-x: auto;
}

.main-tree i {
  font-size: 1.2em;
  color:  var(--color-text);
}

.main-tree h5 {
  margin: 10px 0px 22px 10px;
}

.main-four {
  display: flex;
  justify-content: flex-start;
  flex-direction: column;
  margin: -15px 0 0 0;
  padding: 0 0 15px 0;
  color: var(--color-text);
  background-color: var(--color-background);
  box-shadow: 0px 10px 5px #fadb41;
  overflow-x: auto;
  display: flex;
  justify-content: flex-start;
  flex-direction: collumn;
}

.main-four img {
  height: 70px;
  border-radius: 50%;
  margin-left: 10px;
  padding: 0 25px 0 0;
}

.main-four i {
  font-size: 1em;
  color: var(--color-text);
}

.main-four h4 {
  margin: 10px 0 0 10px;
  color:  var(--color-text);
}

.main-four h5:nth-child(1) {
  margin: 0px auto 5px auto;
  color: var(--color-text);
}

.main-four h5 {
  margin: 0px 10px 0px 10px;
  color:  var(--color-text);
}

.main-four div {
  border-radius: 3% 3% 3% 3%;
}

.main-four-card {
  margin: 0px 10px 20px 10px;
border: solid 1px #fadb4170;
  box-shadow: 0 0px 5px #fadb4170;  display: flex;
  justify-content: flex-start;
  flex-direction: row;
}

.main-four p {
  padding: 0px;
  margin: 10px 0 10px 10px;
  font-size: .8em;
}

.main-four .mini-profile {
  height: 6em;
  border-radius: 50%;
  margin: 10px 10px 0 10px;
  padding: 0 15px 0 0;
}

.main-five {
  display: flex;
  justify-content: flex-start;
  flex-direction: column;
  margin: -10px 0 0 0;
  color: var(--color-text);
  background-color: var(--color-background);
  box-shadow: 0px 10px 5px #fadb41;
  overflow-x: auto;
  height: 500px;
  display: flex;
  justify-content: flex-start;
  flex-direction: collumn;
}

.main-five img {
  height: 70px;
  border-radius: 50%;
  margin-left: 10px;
  padding: 0 25px 0 0;
}

.main-five i {
  font-size: 1em;
  color: var(--color-text);
}

.main-five h4 {
  margin: 10px 0 0 10px;
  color: #fadb41;
}

.main-five h5:nth-child(1) {
  margin: 0px auto 5px auto;
  color: var(--color-text);
}

.main-five h5 {
  margin: 0px 10px 0px 10px;
  color: #00ff00;
}

.main-five div {
  border-radius: 3% 3% 3% 3%;
}

.main-five-card {
  margin: 0px 10px 20px 10px;
border: solid 1px #fadb4170;
  box-shadow: 0 0px 5px #fadb4170;  display: flex;
  justify-content: flex-start;
  flex-direction: row;
  transform: translateY(1em);
  transition: all .4s linear;
}

.main-five-card:hover {
  transform: translateY(0.8em) ;
  box-shadow: 0 5px 5px #fadb4180;
  background-color: #fadb4120;
}

.main-five p {
  padding: 0px;
  margin: 10px 0 10px 10px;
  font-size: .8em;
}

.main-five .mini-profile {
  height: 6em;
  border-radius: 50%;
  margin: 10px 10px 0 10px;
  padding: 0 15px 0 0;
}

.mini-profile {
  height: 25px;
  border-radius: 50%;
  margin: 10px 0 0 0px;
  padding: 0 15px 0 0;
}

.dateYear {
  color: var(--color-text);
  padding: 0 10px 0 10px;
}

.dateYearHover {
  color: var(--color-text);
  border-bottom: solid .2px #000;
  padding: 0 10px 0 10px;
}

@media only screen and (max-width: 369px) {}</style>  