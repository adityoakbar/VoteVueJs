<template>
  <div class="home">
    <section class="vote">
      <h3 class="give-teh-vote">
        Silahkan Pilih Ketua Idaman Anda
      </h3>

        <div class="emoticon">
            ///Ini menjadi komponen vote
        </div>
    </section> 

    <section class="finish">
      <h4>Terimakasih telah memberikan suara</h4>
    </section>
  </div>
</template>

<script>
/* // @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue"; */

export default {
  name: "Home",
  components: {}
};
</script>

<style type="text/css">
       .container{
         display: flex;
         height: 100vh;
         align-items: center;
       }
       section{
         width: 100%;
       }
</style>