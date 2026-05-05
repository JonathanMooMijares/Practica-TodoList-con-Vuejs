<template>
    <header>
        <h1><span class="icon" aria-hidden="true">✅</span>Mi Aplicación</h1>
        <p>Construyendo una aplicación web con Vue.js</p>
    </header>
</template>

<style scoped>
header{
  border-bottom: 1px solid #333;
  background-color: #FFF;
}

header::after{
  content: "";
  display: block;
  height: 1px;
  box-shadow: 0px 0px 10px 0px rgba(0, 0, 0, 0.75);
}

h1{
  font-size: 2rem;
}

h1 .icon{
  font-size: 1rem;
  vertical-align: middle;
}
</style>