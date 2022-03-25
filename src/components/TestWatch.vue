
<template>
    <div id = "testwatch-1">
    <p style = "font-size:25px;">计数器: {{ counter }}</p>
    <button @click = "counter++" style = "font-size:25px;">点我</button>
    </div>
</template>>

<script>
export default {
    name: 'TestWatch',
    props: {
    counter: {
        type: Number,
        default: 0
    }
  }
}

var counterData = {
    counter: 0
}

Vue.component('testwatch-1', {
    data: function(oval, nval) {
        alert('计数器值的变化 :' + oval + ' 变为 ' + nval + '!');
     }
})
new Vue({ el: '#testwatch-1' })

</script>>