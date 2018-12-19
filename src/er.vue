<template>
   <div class="bet-action">
        <button class="mac-select" @click="childMethod">机选</button>
    </div>
</template>
<script>
export default {
    name:"er",
     methods: {
          childMethod() {
              console.log('请求父组件方法');
              this.$emit('parentMethod');  //使用$emit()引入父组件中的方法
          }
      },
}
</script>