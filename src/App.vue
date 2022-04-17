 <template>
   <div class="wrapper">
    <v-header/>
     <div class="wrapper__content">
       <div class="container">
         <div class="example">
           <clock/>
         </div>
       </div>
     </div>
     <v-footer/>
   </div>
</template>

 <script lang="ts">
 import HelloWorld from "@/components/HelloWorld.vue";
 import Clock from "@/components/Clock.vue";
 import VHeader from "@/components/Header.vue";
 import VFooter from "@/components/Footer.vue";
 export default {
   components: {VFooter, VHeader, Clock, HelloWorld },
   setup() {

   }
 }
 </script>
<style lang="scss">
  @import "assets/styles/main";
</style>
