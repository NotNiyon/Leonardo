<template>
  
  <div class="container">
    <h1>Kontakt</h1>
    <p class="subheading">Hier können Sie uns unter folgender Nummer Kontaktieren</p>
    <img src="~/static/img/contact-us.jpg" width="1000"/>
    <p>E-Mail: testemail@gmx.de</p>
    <p>+49 04220/1235</p>
   
  </div>


</template>

<script>
export default {
     head() {
         return {
             title: 'Kontakt',
             meta: [
                 {name: 'description', content: 'Kontaktieren Sie uns.'},
                 {name: 'keywords', content: 'contact us, Leonardo da vinci, Restaurant'},
             ]
         }
     }

}
</script>

<style>

</style>

