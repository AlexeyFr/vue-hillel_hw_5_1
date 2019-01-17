<template>
  <div id="app">
    <div class="comtainer">
      <Home/>
    </div>

  </div>
</template>

<script>
import Home from './components/Home.vue'

export default {
  name: 'app',
  components: {
    Home
  }
}
</script>

<style>
  /*Reset*/
  html,body,div,span,applet,object,iframe,blockquote,pre,a,abbr,acronym,address,big,cite,code,del,dfn,em,font,img,ins,kbd,q,s,samp,small,strike,strong,sub,sup,tt,var,b,u,i,center,p,h1,h2,h3,h4,h5,h6,dl,dt,dd,ol,ul,li,fieldset,form,legend,table,tbody,tfoot,thead,tr,th{margin:0;padding:0;border:0;outline:0;font-size:100%;vertical-align:baseline;background:transparent}body{line-height:1}ol,ul{list-style:none}blockquote,q{quotes:none}:focus{outline:0}ins{text-decoration:none}del{text-decoration:line-through}table{border-collapse:collapse;border-spacing:0}
  /*Reset*/
  body {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    font-weight: normal;
    font-style: normal;
    line-height: 1.2;
    font-size: 12px;
    background: #fafafa;
    color: #444;
  }
  .comtainer {
    width: 100%;
    max-width: 980px;
    margin: 0 auto;
  }
  *:focus {
    outline: none;
  }
  a {
    text-decoration: none;
  }
</style>