<template>
  <div class="container">
    <h1>Leonardo´s ristorante</h1>
    <p class="subheading">Exklusives Restaurant von Da Vinci</p>
    <p>Erleben Sie ein Italienisches Restaurant vom feinsten! </p>
    <img src="~/static/img/pizza.jpg" width="850"/>
    <p class="subheading">Unser Angebot</p>
    <img src="~/static/img/salamipizza.jpg" width="500"/>
    <img src="~/static/img/margaritapizza.jpg" width="500"/>
    <p>Je Pizza 3,99€, bei Bestellung von 2 Pizzen insgesamt nur 5,00€</p>
    <img src="~/static/img/funghipizza.jpg" width="500"/>
  </div>
</template>

<script>
export default {
     head() {
         return {
             title: 'Home',
             meta: [
                 {name: 'description', content: 'Home Page'},
                 {name: 'keywords', content: 'contact us, Leonardo da vinci, Restaurant'},
             ]
         }
     } 

}
</script>

<style>
.container {
  text-align: center;
  padding: 10px;
}
.subheading {
  padding: 10px;
  color: (0, 219, 146);
}
</style>
