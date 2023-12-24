<!-- <script>
export default {
  name: 'App',
  mounted() {
    // Access the .intro and .logo elements using refs
    let intro = this.$refs.introRef;
    let logoSpans = intro.querySelectorAll('.logo');
    let logoHeader = intro.querySelector('.logo-header');


    window.addEventListener('DOMContentLoaded', () => {
      setTimeout(() => {
        logoSpans.forEach((span, idx) => {
          setTimeout(() => {
            span.classList.add('active');
          }, (idx + 1) * 400);
        });
      }, 200);

      setTimeout(() => {
        logoSpans.forEach((span, idx) => {
          setTimeout(() => {
            span.classList.remove('active');
            span.classList.add('fade');
          }, (idx + 1) * 50);
        });
      }, 2000);

      setTimeout(() => {
        intro.style.top = '-100vh';
      }, 3000);
    });
  },
};
</script> -->


<!-- <template>
  <div class="intro">
    <h1 class="logo-header">
      <span class="logo">Carl</span>
      <span class="logo"> James</span>  
    </h1>
  </div>
  <header>
    <h4>Code by Carl</h4>
  </header>

</template>

<script>

// import PreloaderPage from './components/PreloaderPage.vue'

export default {
  name: 'App',
  components: {
    // PreloaderPage
  }
}
</script>

<style>

header{
  position: relative;
  left: 0;
  top: 0;
  width:100% ;
  height: 80px;
}

header h4{
  position: absolute;
  left: 10%;
  bottom: 1rem;
  font-size: 1.6rem;
}

/* splash screen */

.intro{
  position: fixed;
  z-index: 1;
  left: 0;
  top: 0;
  width: 100%;
  height: 100vh;
  background-color: black;
  transition: 1s;
}

.logo-header {
  position: absolute;
  top: 40%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: white;
}


#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
 -->