<template>
  <div class="hello">
    <info></info>
  </div>
</template>

<script type="text/babel">
import info from '../../info.md';
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  components:{
    info
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
  @import 'highlight.js/styles/color-brewer.css';
  .hello {
    margin: 20px auto;
    width: 50%;
  }
  a {
    color: #409EFF;
    text-decoration: none;
  }

  code {
    background-color: #f9fafc;
    padding: 0 4px;
    border: 1px solid #eaeefb;
    border-radius: 4px;
  }

  .hljs {
    line-height: 1.8;
    font-family: Menlo, Monaco, Consolas, Courier, monospace;
    font-size: 12px;
    padding: 18px 24px;
    background-color: #fafafa;
    border: solid 1px #eaeefb;
    margin-bottom: 25px;
    border-radius: 4px;
    -webkit-font-smoothing: auto;
  }
</style>
