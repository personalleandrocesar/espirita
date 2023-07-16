<script setup>
import LCLogo from '@/components/LCLogo.vue'
</script>
<template>
    <header>
        <div class='logo'>
            <LCLogo/>
            <!-- <img alt="leandrocesar.com logo" class="logo" src="@/assets/logo.svg" width="300" height="300" /> -->
            <span class='logoAnimationSeven'>
                <h1>Espírita Top</h1>
            </span>
            <span class='logoAnimationSevenTwo'>
                <h3></h3>
            </span>
        </div>
    </header>

</template>
<script>
export default {
    methods: {
        scrollToTop() {
            window.scrollTo(0, 0);
        }
    },
}

</script>

<style scoped>
.logo {
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: center;
    flex-wrap: wrap;
    margin-top: 1rem;
}


h1 {
    margin-top: 2.5rem;
    font-size: 1.6rem;
    color: #53DD84;
    text-shadow: 4px 4px 10px #205461, -4px 4px 10px #205461, 4px -4px 10px #205461, -4px -4px 10px #205461, 5px 5px 10px #205461, -5px 5px 10px #205461, 5px -5px 10px #205461, -5px -5px 10px #205461 ;
}

h3 {
    color: var(--color-text);
  transition: all .3s linear;
  cursor: pointer;
  margin:-15px 0 50px 0;
  text-align: center;
    font-size: 1rem;
}

h3:nth-child(2) {
  margin-top: -60px;
}

</style>