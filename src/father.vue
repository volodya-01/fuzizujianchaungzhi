<template>
    <div>father
        <er @parentMethod="macSelect"></er>
    </div>
</template>
<script>
import er from '@/er'
export default {
    name:"father",
    components:{
        er
    },
     method:{
        macSelect(){
            //方法体
            alert("123")
        }
    }
}
</script>
