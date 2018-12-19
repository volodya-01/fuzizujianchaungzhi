<template>
   <div>
        <button v-on:click="clickParent">点击</button>
        <fu ref="fu"></fu>
   </div>
</template>
<script>
import fu from "@/fu"
export default {
    name:"ye",
    components:{fu},
     methods: {
            clickParent() {
                this.$refs.fu.handleParentClick("ssss");
            }
        }
}
</script>
