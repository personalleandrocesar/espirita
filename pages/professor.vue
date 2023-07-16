<template>
  <div>
    <NavTwo />
    <div class='anima'>



      <div class='main-tree'>
        <div>
          <h5><font-awesome-icon icon="fa-solid fa-ranking-star" /> Serviços</h5>
        </div>
      </div>


      <div class='main-five'>

        <div class='main-five-card'>

          <div>
            <img src='/img/myFotoTwo.jpg' alt='' class='mini-profile'>
            <p><font-awesome-icon icon="fa-solid fa-people-arrows" /> Serviço presencial</p>
          </div>
          <div>
            <h4>Personal Trainer</h4>
            <h5>R$ À combinar!</h5>
            <p>Serviço de Personal trainer, para treinamento personalizados em academias; </p>
          </div>
        </div>

        <div class='main-two'>
          <code>
                  <b>#vemtreinarcomigo</b>
                  <br>
                  Bora treinar junto! 
                </code>
          <a
            href='https://api.whatsapp.com/send?phone=5521936184024%20&text=Ol%C3%A1%20Leandro%20Cesar,%20fiquei%20interessado(a)%20no%20seu%20serviço%20de%20Personal,%20me%20chamo%20'>
            <font-awesome-icon icon="fa-brands fa-whatsapp" /> Marcar Horário
          </a>
        </div>

        <div class='divider'></div>

        <br>
        <div class='main-six'>
          <div class='main-six-card'>
            <h5><b>Vantagens:</b></h5>
            <p>
            <ul>
              <li>
                <b>Treino na medida e com resultado + rápido:</b> o conhecimento de um treinador pessoal permitirá
                potencializar o treino, através de estímulos e metodologias de trabalho diferentes.
              </li>
              <li>
                <b>Permite corrigir erros:</b> serão corrigidos os erros de execução de cada técnica, preocupando-se
                com a correta posição postural, afim de evitar má posturas e lesões.
              </li>
              <li>
                <b>+ seguro:</b> tendo em conta os objetivos e a condição física do cliente, a intesidade e o volume
                são ajustados com bases no conhecimento do treinador.
              </li>
              <li>
                <b>+ motivador:</b> o personal trainer ajudará a evitar a rotina e monotonia dos treinos, isso claro,
                se o aluno tiver obediência na hora do planejamento da sessão de treino e rotina de ir à academia.
              </li>
              <li>
                <b>Facilmente quantificável:</b> as reavaliações periódicas da composição corporal e capacidades físicas
                permitem analisar a evolução em todos os parâmetros e reajustar o treino de acordo com os objetivos
                traçados.
              </li>
            </ul>
            </p>
            <div class='divider'></div>
            <h5><b>Benefícios:</b></h5>
            <p>
              <b><font-awesome-icon icon="fa-solid fa-clipboard-check" /> Avaliação inicial gratuita:</b> mensuração de
              medidas antropométricas, para ver a composição corporal; realização
              de teste para ver o condicionamento.
              <br>
              <b><font-awesome-icon icon="fa-solid fa-mobile" /> Acesso a aplicativo:</b> nos dias em que for treinar
              sozinho, terá sua planilha de treinamento para não ficar perdido;
              e continuar a evoluir sem escapar do planejamento.
              <br>
              <b><font-awesome-icon icon="fa-solid fa-chart-pie" /> Reavaliações de 2 em 2 meses:</b> Analise dos
              resultados dos testes e medidas para readaptação dos treinos para
              chegar ao objetivo pre-determinado pelo cliente.
              <br>
              <b><font-awesome-icon icon="fa-solid fa-tag" /> Direito à descontos:</b> direito a descontos em terapias e
              parcerias, exclusivas para clientes;

            </p>
          </div>

        </div>
        <a class='button-call'
          href='https://api.whatsapp.com/send?phone=5521936184024%20&text=Ol%C3%A1%20Leandro%20Cesar,%20fiquei%20interessado(a)%20no%20seu%20serviço%20de%20Personal,%20me%20chamo%20'>
          <font-awesome-icon icon="fa-brands fa-whatsapp" /> Marcar Horário
        </a>

      </div>

      <div class='divider'></div>
      <br><br>
      <br><br>
    </div>
    <NavBottomTwo />
  </div>
</template>
<script>
export default {
  head: {
    title: 'Personal Leandro Cesar',
    htmlAttrs: {
      lang: 'pt-br'
    },
    meta: [
      { charset: 'utf-8' },
      { name: 'viewport', content: 'width=device-width, initial-scale=1' },
      { hid: 'description', name: 'description', content: 'Professor Leandro Cesar Ramos da Costa | Personal Trainer | Niterói - RJ' },
      { hid: 'keywords', name: 'description', content: 'Personal trainer, Treinamentos, Musculação' },
      { name: 'format-detection', content: 'telephone=no' },
      { name: 'msapplication-TileColor', content: '#fff' },
      { name: 'theme-color', content: '#fff' }
    ],
    link: [
      { rel: 'icon', type: 'image/x-icon', href: '/img/favicon.ico' },
      { rel: 'shortcut icon', type: 'image/x-icon', href: '/img/favicon.svg' },
      { rel: 'apple-touch-icon', size: '180x180', href: '/img/apple-touch-icon.png' },
      { rel: 'icon', type: 'image/png', size: '32x32', href: '/img/favicon-32x32.png' },
      { rel: 'icon', type: 'image/png', size: '16x16', href: '/img/favicon-16x16.png' },
      { rel: 'apple-touch-icon', size: '180x180', href: '/img/apple-touch-icon.png' },
      { rel: 'mask-icon', href: '/img/safari-pinned-tab.svg', color: '#fff' }
    ],
  }
}
</script>

<style scoped>
a {
  text-decoration: none;
  color: var(--color-text);
}

.svg-inline--fa {
  color: var(--color-text);
  font-size: .9em;
  margin: auto;
}

code {
  font-size: 0.8em;
  padding-left: 10px;
  border-left: solid 5px #fadb41;
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
  background-color: var(--color-background);
  display: flex;
  justify-content: flex-start;
  flex-wrap: wrap;
  padding: 20px 0 5px 0;
  margin-top: -10px;
}

.profile a {
  text-decoration: none;
  color: var(--color-text);
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
  color: var(--color-text);
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
  color: var(--color-text);
}

.main-one {
  display: flex;
  justify-content: flex-start;
  flex-direction: column;
  padding: 10px 0 15px 0;
  box-shadow: 0px 10px 5px #bbb;
  background-color: var(--color-background);
}

.main-one div {
  margin: 0 0 0 15px;
}

.main-one a .svg-inline--fa {
  padding-right: 4px;
  margin: 0 0 0 3px;
}

.main-one a:nth-child(2) .svg-inline--fa {
  padding-right: 1px;
  margin: 0 0 0 3px;
}

.main-one a {
  margin: 0 0 0 10px;
  color: var(--color-text);
}

.main-two {
  display: flex;
  justify-content: space-between;
  flex-direction: row;
  padding: 15px 40px 18px 10px;
  color: var(--color-text);
  background-color: var(--color-background);
  color: var(--color-text);
}

.main-two a {
  margin: 20px 0 0 0px;
  color: var(--color-text);
  font-weight: 600;
}

.main-two a:hover {
  color: #fadb41;
}

.main-two .svg-inline--fa {
  color: var(--color-text);
  font-size: 1.1em;
  font-weight: 600;
}


.main-tree {
  display: flex;
  justify-content: flex-start;
  flex-direction: column;
  margin: 0px 0 0 0;
  color: var(--color-text);
  background-color: var(--color-background);
  overflow-x: auto;
}

.main-tree .svg-inline--fa {
  font-size: 1.2em;
  color: var(--color-text);
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

.main-four .svg-inline--fa {
  font-size: 1em;
  color: var(--color-text);
}

.main-four h4 {
  margin: 10px 0 0 10px;
  color: var(--color-text);
}

.main-four h5:nth-child(1) {
  margin: 0px auto 5px auto;
  color: var(--color-text);
}

.main-four h5 {
  margin: 0px 10px 0px 10px;
  color: var(--color-text);
}

.main-four div {
  border-radius: 3% 3% 3% 3%;
}

.main-four-card {
  margin: 0px 10px 20px 10px;
  display: flex;
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
  overflow-x: auto;
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

.main-five .svg-inline--fa {
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
  color: rgb(0, 255, 0);
}

.main-five div {
  border-radius: 3% 3% 3% 3%;
}

.main-five-card {
  margin: 0px 10px 20px 10px;
  display: flex;
  justify-content: flex-start;
  flex-direction: row;

  border: solid 1px #fadb4170;
  box-shadow: 0 0px 5px #fadb4170;
}

.main-five p {
  padding: 0px;
  margin: 10px 0 10px 10px;
  font-size: .8em;
}

.main-six {
  margin: -10px 0 0 0;
  color: var(--color-text);
  background-color: var(--color-background);
  overflow-x: auto;
}

.main-six img {
  height: 70px;
  border-radius: 50%;
  margin-left: 10px;
  padding: 0 25px 0 0;
}

.main-six .svg-inline--fa {
  font-size: 1em;
  color: var(--color-text);
}

.main-six p:nth-child(2) {
  margin-left: -15px;
}

.main-six h4 {
  margin: 10px 0 0 10px;
  color: var(--color-text);
}

.main-six h5:nth-child(1) {
  margin: 0px 10px 0px 10px;
  color: var(--color-text);
}

.main-six h5 {
  margin: 30px 10px 0px 10px;
  color: var(--color-text);
}

b {
  color: #fadb41;
}

.main-six div {
  border-radius: 3% 3% 3% 3%;
}

.main-six-card {
  margin: 0px 10px 20px 10px;
  display: flex;
  justify-content: flex-start;
  flex-direction: column;
}

.button-call {
  padding: 5px 10px;
  margin: auto;
  transition: all .4s linear;
  background-color: var(--color-background);
  border: solid 1px #fadb4170;
  box-shadow: 0 0px 5px #fadb4170;
  border-radius: 8px;
  cursor: pointer;
}

.button-call:hover {
  background-color: #fadb4120;
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