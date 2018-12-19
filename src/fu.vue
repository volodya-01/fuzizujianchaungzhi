<template>
   <div>
      <sunzi ref="sun"> </sunzi>
   </div>
</template>
<script>
import sunzi from "@/sunzi"
export default {
    name:"fu",
    components:{
        sunzi
    },
     props: "msg",
        methods: {
            handleParentClick(e) {
                alert("123456")
               this.$refs.sun.handleSunClick("s"); 
            }
        }
}
</script>

