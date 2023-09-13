<template>
  <div class="hello">
    <!-- responsive svg -->
    <img src="../assets/lincette.svg" class="responsive center">
   
   
  </div>
  <div class="footer">
    <h3></h3>
    <p>
      La Lincette 🍻 est une bière artisanale créée en 2020 à l'initiative du comité scolaire de l'école de Lincé (Sprimont).
    </p>
    <ul>
      <li><a href="https://www.facebook.com/groups/429847368281109" target="_blank" rel="noopener">facebook</a></li>
      <li><a href="mailto:contact@lincette.be" target="_blank" rel="noopener">contact@lincette.be</a></li>
   
      
    </ul>
    <ul class="small">
      <li>
        <a href="https://github.com/tintamarre/lincette.be"
        target="_blank" rel="noopener">code source</a>
      </li>
    </ul>
  </div>
</template>

<script>

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #ccc;
}
.responsive {
  width: 100%;
  height: auto;
}

.center {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 90%;
  margin-top: 10%;
}
.footer {
  position: fixed;
  bottom: 0;
  width: 100%;
  padding: 20px;
  color: #fff;
}
.small {
  font-size: 0.8em;
}
</style>
