<template>
    <main>
        <NavBottomTwo />
        <div class='anima'>
            <div class='main-tree'>
                <div>
                    <h5><Icon name="ion:library" /> Biblioteca</h5>
                </div>
            </div>
        </div>

          <div class='main-four'>
            <div class='main-four-card'>
                <NuxtLink to="/biblioteca/caminho/interpretacao" @click.native="scrollToTop()">
<!-- 
    <img src="/img/importancia-imc.jpg" alt="A importânica do IMC">

-->
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
          <br>    </main>
</template>

<style scoped>
iframe {
    margin-left: 10px;
}

a {
    text-decoration: none;
}

i {
    color: var(--color-text);
    font-size: .9em;
    margin: auto;
}

code {
    font-size: 0.6em;
    margin-left: 15px;
    padding-left: 10px;
    border-left: solid 5px #eee;
    color: #888;
}



.divider {
    height: 15px;
    background-color: #dddddd54;
}

.nav-one {
    height: 35px;
    position: sticky;
    top: -1px;
}

.nav-one div {
    display: flex;
    justify-content: flex-end;
    flex-direction: row;
}

.nav-one a {
    text-decoration: none;
    margin: 0 14px 0 6px;
    font-size: 1.2em;
}

.nav-one i {
    color: #0000FF;
    margin-top: 8px;
    display: flex;
    justify-content: flex-end;
}

.profile {
    display: flex;
    justify-content: flex-start;
    flex-wrap: wrap;
    padding: 10px 0 5px 0;
    color: black;
}

.profile a {
    text-decoration: none;
    color: #aaa;
    font-size: .9em;
}

.profile img {
    height: 70px;
    border-radius: 50%;
    margin-left: 10px;
    padding: 0 25px 0 0;
}

.profile h1 {
    margin: 5px 0 0 -10px;
    font-size: 1.5em;
}

.profile h4 {
    margin: 0 0 0 -10px;
    font-size: .9em;
    font-weight: 100;
    color: #aaa;
}

.main-one {
    display: flex;
    justify-content: flex-start;
    flex-direction: column;
    padding: 10px 0 15px 0;
    color: black;
}

.main-one div {
    margin: 0 0 0 15px;
}

.main-one a:nth-child(1) i,
.main-one a:nth-child(2) i {
    padding-right: 4px;
    margin: 0 0 0 3px;
}

.main-one a:nth-child(3) i {
    padding-right: 2px;
    margin: 0 0 0 2px;
}

.main-one a {
    margin: 0 0 0 10px;
    color: #555;
}

.main-two {
    display: flex;
    justify-content: flex-start;
    flex-direction: column;
    padding: 15px 0 15px 0;
    color: black;
    box-shadow: 4px 4px 10px #bbb;
}

.main-tree {
    display: flex;
    justify-content: flex-start;
    flex-direction: column;
    margin: 20px 0 0 0;
    color: var(--color-text);
    overflow-x: auto;
}

.main-tree i {
    font-size: 1.2em;
    color: #555;
}

.main-tree h5 {
    margin-left: 10px;
    font-size: 1.2rem;
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
