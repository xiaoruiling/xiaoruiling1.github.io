<template>
 <div id="testbutton">
  <button @click="counter += 1">增加 1</button>
  <p>这个按钮被点击了 {{ counter }} 次。</p>
</div> 

<div id="testbuttonfunction">
  <!-- `greet` 是在下面定义的方法名 -->
  <button @click="greet">点我</button>
</div>
 
</template>>


<script>
export default {
  name: 'TestButton',
  props: {
    counter: Number,
    default: 0
  }
}
</script>