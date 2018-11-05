<template>
  <main>
    <div class="left">
      <img src="../assets/logo.png">
    </div>
    <div class="right">
      <p>{{welcome}}</p>
      <p>{{hello}}</p>
    </div>
  </main>
</template>

<script lang="ts">
import Vue from 'vue'
import Component from 'vue-class-component'

@Component({})
export default class HelloWorld extends Vue {
  name:String = 'Been'
  welcome:String = 'Welcome  ' + this.name
  hello:String = 'Hello World!'
}
</script>
<style scoped>
p{
  color: green;
  font-size: 20px;
}
.left{
  width: 100px;
  height: 100px;
  margin-left: 100px;
  float: left;
}
img{
  width: 100px;
  height: 100px;
}
.right{
  height: 100px;
  margin-left:400px;
}
</style>
