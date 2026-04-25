<template>
  <div>
    <nav class="navbar">
      <img src="./assets/logo.png" class="logo">
      <h2>SportMax</h2>
    </nav>

    <section class="hero">
      <h1>Bienvenido a SPORTMAX</h1>
      <p>La mejor tienda deportiva online</p>
      <button>Comprar Ahora</button>
    </section>

    <section class="productos">
      <div class="card">👟 Nike</div>
      <div class="card">⚽ Adidas</div>
      <div class="card">🏀 Puma</div>
    </section>
  </div>
</template>

<style>
body{
  margin:0;
  background:black;
  color:white;
  font-family:Arial;
}

.navbar{
  display:flex;
  align-items:center;
  padding:15px 40px;
  background:#111;
}

.logo{
  width:60px;
  margin-right:15px;
}

.hero{
  text-align:center;
  padding:80px 20px;
}

.hero h1{
  font-size:55px;
}

.hero button{
  background:red;
  color:white;
  border:none;
  padding:15px 30px;
  border-radius:10px;
  cursor:pointer;
}

.productos{
  display:flex;
  justify-content:center;
  gap:20px;
  padding:40px;
}

.card{
  background:#111;
  padding:40px;
  border-radius:15px;
  width:200px;
  text-align:center;
  transition:.3s;
}

.card:hover{
  transform:translateY(-8px);
  background:#1d1d1d;
}
</style>