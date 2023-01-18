<template>
  
  <div style="padding:0;">
    <navBar :index="index"></navBar>
    
    <footerBar></footerBar>
  </div>
</template>

<script>
import navBar from './components/navBar.vue';
import footerBar from './components/footerBar.vue';
//import infoPage from './components/infoPage.vue'
export default{
  name:'App',
  components:{
    navBar,
    footerBar
    
  },
  data(){
    return{ index : 1}
   
  }
  ,
  methods: {
    F1(){
        this.index=1;
        console.log(this.index);
    },
    F2(){
        this.index=2
    },
    F3(){
        this.index=3
    },
    F4(){
        this.index=4
    }
  }
};
</script>
<style>
body{
  margin:0px;
}
</style>