<script>
export default {
  methods: {
    scrollToTop() {
      window.scrollTo(0, 0);
    }
  }
}
</script>

<template>
  <div class="homeAnimation">
      

      <div class='main-tree'>
        <div>
          <h5>
          </h5>
        </div>
      </div>

      <div class='main-four'>
        <div class='main-four-card'>
          <NuxtLink to="/biblioteca/caminho/interpretacao" @click.native="scrollToTop()">
            <br>
            <h4>
              <Icon name="material-symbols:keyboard-double-arrow-right" />
              
              Caminho, verdade e vida </h4>
            <p>Fonte auxiliar de esclarecimento nos estudos dos textos evangélicos.</p>
          </NuxtLink>
        
        </div>
        <div class='main-four-card'>
          <NuxtLink to="/biblioteca/caminho/interpretacao" @click.native="scrollToTop()">
            <br>
            <h4>
                            <Icon name="material-symbols:keyboard-double-arrow-right" />
 
               O Livro dos Espíritos</h4>
            <p>Livro que marca o nascimento da Doutrina Espírita e inicia a Codificação organizada por Allan Kardec.</p>
          </NuxtLink>
        
        </div>
        <div class='main-four-card'>
          <NuxtLink to="/biblioteca/caminho/interpretacao" @click.native="scrollToTop()">
            <br>
            <h4>
                            <Icon name="material-symbols:keyboard-double-arrow-right" />

               Aleatório</h4>
            <p>Mensagens espíritas aleatórias para se inspirar no seu dia-a-dia!</p>
          </NuxtLink>
        
        </div>
        
      </div>
      <br>
      <br>
      <br>
    </div>
</template>
<style scoped>

i {
  color: var(--color-text);
  font-size: .9em;
  margin: auto;
}

iframe {
  margin-left: 10px;
}

code {
  font-size: 0.5em;
  margin-left: 15px;
  padding-left: 10px;
  border-left: solid 5px var(--color-text);
}


.main-tree {
  display: flex;
  justify-content: flex-start;
  flex-direction: column;
  margin: -10px 0 10px 0;
  color: var(--color-text);
  overflow-x:auto;
}

.main-tree i {
  font-size: 1.2em;
  color: var(--color-text);
}

.main-tree h5{
  margin-left: 10px;
}

.main-four {
  display: flex;
  justify-content:center;
  flex-direction: row;
  margin: 0px 0 0 0;
  color: #aaa;
  overflow-x:auto;
  flex-wrap: wrap;
}

.main-four i {
  font-size: 1.2em;
  color: var(--color-text);
}

.main-four h5{
  margin-left: 10px;
}

.main-four-card {
  height: 180px;
  width: 180px;
  display: flex;
  justify-content: flex-start;
  flex-direction: row;
}

.main-four-card a {
  border: solid 1px #53DD8470;
  box-shadow: 0 0px 5px #53DD8470;
  border-radius: 3% 3% 3% 3%;
  margin: 0px 5px 20px 0px;
  width: 500px;
  transform: translateY(1em);
  transition: all .4s linear;
}

.main-four-card a:hover {
  transform: translateY(0.8em) ;
  box-shadow: 0 5px 5px #53DD8480;
  background-color: #53DD8420;
}

.main-four-card span {
  position: relative;
  top: -6px;
  left: -14px;
}

.main-four-card h4 {
  margin: 0 5px 0 10px;
  color:var(--color-text);
}

.main-four-card p {
  margin: 0 10px;
  font-size: .8em;
}


@media only screen and (max-width: 382px) {
  .main-tree-card {
    width: 90%;
  }
}
</style>
