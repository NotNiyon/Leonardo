<template>
  <div class="container">
    <h1>Historie</h1>
    <p class="subheading">Lernen sie unsere Geschichte kennen</p>
    <img src="~/static/img/oldclock.jpg" width="400"/>
    <p>Die Geschichte von Leonardo´s Ristorante begann am 16.7.1980. Es war ein stürmischer Tag und es herrschte dichter Schnee. Es sah nicht gut aus für Da Vinci, doch dann sah er eine kleine Pizzeria, welche ihn rettete. Von diesem Tag an wollte er genau so einen lebensrettenen Status haben und deswegen eröffnete er sein eigenes Restaurant: Leonardo´s Ristorante. </p>
  </div>
</template>

<script>
export default {
     head() {
         return {
             title: 'Historie',
             meta: [
                 {name: 'description', content: 'Erfahren Sie etwas über unsere Geschichte.'},
                 {name: 'keywords', content: 'contact us, Leonardo da vinci, Restaurant'},
             ]
         }
     }

}
</script>

<style>

</style>
