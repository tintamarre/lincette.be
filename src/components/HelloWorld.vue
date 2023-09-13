<template>
  <div class="hello">
    <!-- responsive svg -->
    <img src="../assets/lincette.svg" class="responsive center">
   
   
  </div>
  <div class="footer">
    <h3>Informations</h3>
    <ul>
      <li><a href="mailto:contact@lincette.be" target="_blank" rel="noopener">contact@lincette.be</a></li>
      <li><a href="https://www.facebook.com/groups/429847368281109" target="_blank" rel="noopener">facebook</a></li>
      
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
  color: #42b983;
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
  color: #ccc;
}
</style>
