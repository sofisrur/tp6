<template>
  <section class="src-components-home">
    <div id="header">
      <h1>The Great <br>
        <span id="colorDisplay">{{color || 'RGB' }} </span>
        <br>
        Guessing Game</h1>
    </div> 
    <Navigator @actualColor="color=$event" />
  </section>

</template>

<script>
import Navigator from './Navigator.vue'

  export default  {
  components: { Navigator },
    name: 'src-componentes-header',
    props: [],
    mounted () {

    },
    data () {
      return {
        color:" "

      }
    },
    methods: {

    },
    computed: {

    }
}


</script>

<style scoped lang="css">
 #header {
  transition: all 0.3s;
	background: steelblue;
	text-transform: uppercase;
	text-align: center;
	margin: 0;
	color: white;
  }
  #colorDisplay {
	font-size: 200%;
}
h1 {
	font-weight: normal;
	line-height: 1.1;
	padding: 20px 0;

}

</style>
