<template>
  <div class="hello">
    <!-- responsive svg -->
    <img src="../assets/lincette.svg" class="responsive center">
 
  </div>
  <div class="footer responsive">
    <a class="btn-shop" href=" https://shop.lincette.be">
      Boutique en ligne
    </a>
    <p>
      La Lincette 🍻 est une bière artisanale créée en 2020 à l'initiative du comité scolaire de l'école de Lincé (Sprimont).
    </p>
    <ul>
      <li>🔗 <a href="https://www.facebook.com/groups/429847368281109" target="_blank" rel="noopener" class="link">facebook</a></li>
      <li>✉️ <a href="mailto:contact@lincette.be" target="_blank" rel="noopener" class="link">contact@lincette.be</a></li>
   
      
    </ul>
    <ul class="small">
      <li>
        👩‍💻 <a href="https://github.com/tintamarre/lincette.be"
        target="_blank" rel="noopener" class="link">code source</a>
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
.link {
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
  width: 80%;
  margin-top: 10%;
}
.footer {
  position: fixed;
  bottom: 0;
  width: 90%;
  padding: 0px;
  color: #fff;
  font-size: 0.85em;
}
.small {
  font-size: 0.8em;
}

.btn-shop {
  align-items: center;
  background-color: #FFFFFF;
  border: 1px solid rgba(0, 0, 0, 0.1);
  border-radius: .25rem;
  box-shadow: rgba(0, 0, 0, 0.02) 0 1px 3px 0;
  box-sizing: border-box;
  color: rgba(0, 0, 0, 0.85);
  cursor: pointer;
  display: inline-flex;
  font-family: system-ui,-apple-system,system-ui,"Helvetica Neue",Helvetica,Arial,sans-serif;
  font-size: 16px;
  font-weight: 600;
  justify-content: center;
  line-height: 1.25;
  margin: 0;
  min-height: 3rem;
  padding: calc(.875rem - 1px) calc(1.5rem - 1px);
  position: relative;
  text-decoration: none;
  transition: all 250ms;
  user-select: none;
  -webkit-user-select: none;
  touch-action: manipulation;
  vertical-align: baseline;
  width: auto;
}

.btn-shop:hover,
.btn-shop:focus {
  border-color: rgba(0, 0, 0, 0.15);
  box-shadow: rgba(0, 0, 0, 0.1) 0 4px 12px;
  color: rgba(0, 0, 0, 0.65);
}

.btn-shop:hover {
  transform: translateY(-1px);
}

.btn-shop:active {
  background-color: #F0F0F1;
  border-color: rgba(0, 0, 0, 0.15);
  box-shadow: rgba(0, 0, 0, 0.06) 0 2px 4px;
  color: rgba(0, 0, 0, 0.65);
  transform: translateY(0);
}
</style>
