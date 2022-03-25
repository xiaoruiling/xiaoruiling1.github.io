<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="欢迎来到菜鸟程序"/>
  <TestCheckBox :checked=true />
  <TestButton :counter=0></TestButton>
  <TestWatch :counter=0 />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import TestCheckBox from './components/TestCheckBox.vue'
import TestButton from './components/TestButton.vue'
import TestWatch from './components/TestWatch.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    TestCheckBox,
    TestButton,
    TestWatch

    }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
