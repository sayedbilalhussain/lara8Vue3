<template>
   <div>
       Hello there {{greeting}}
   </div>
</template>

<script>
import { ref } from 'vue';
export default {
   setup(){
       const greeting = ref("Bilal Hussain");
       return{
           greeting,
       }
   }
}
</script>
