# Nunes-emprendimento
/* ==========================
   NUNES EMPREENDIMENTOS LTDA
   STYLE.CSS
========================== */

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    scroll-behavior:smooth;
    font-family:'Poppins',sans-serif;
}

body{
    background:#0d0d0d;
    color:#fff;
    overflow-x:hidden;
}

/* Header */

header{
    position:fixed;
    top:0;
    width:100%;
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:20px 8%;
    background:rgba(0,0,0,.90);
    backdrop-filter:blur(8px);
    z-index:999;
}

.logo h2{
    color:#d4af37;
    font-size:32px;
}

.logo span{
    color:#fff;
    font-size:14px;
}

nav{
    display:flex;
    gap:30px;
}

nav a{
    color:#fff;
    text-decoration:none;
    transition:.3s;
    font-weight:500;
}

nav a:hover{
    color:#d4af37;
}

/* Banner */

.banner{
    height:100vh;
    background:linear-gradient(rgba(0,0,0,.75),rgba(0,0,0,.75)),
    url("https://images.unsplash.com/photo-1520607162513-77705c0f0d4a?auto=format&fit=crop&w=1600&q=80");
    background-size:cover;
    background-position:center;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
}

.conteudo{
    max-width:900px;
    padding:20px;
}

.conteudo h1{
    font-size:60px;
    color:#d4af37;
}

.conteudo p{
    margin-top:20px;
    font-size:22px;
    line-height:35px;
}

.botao{
    display:inline-block;
    margin-top:35px;
    padding:18px 45px;
    background:#d4af37;
    color:#000;
    text-decoration:none;
    font-weight:bold;
    border-radius:50px;
    transition:.4s;
}

.botao:hover{
    transform:scale(1.08);
    box-shadow:0 0 30px #d4af37;
}

/* Títulos */

section{
    padding:90px 8%;
}

section h2{
    text-align:center;
    font-size:42px;
    margin-bottom:50px;
    color:#d4af37;
}

/* Produtos */

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
    gap:35px;
}

.card{
    background:#1b1b1b;
    border-radius:18px;
    overflow:hidden;
    transition:.4s;
    border:1px solid rgba(212,175,55,.3);
}

.card:hover{
    transform:translateY(-10px);
    box-shadow:0 0 25px rgba(212,175,55,.5);
}

.card img{
    width:100%;
    height:240px;
    object-fit:cover;
}

.card h3{
    padding:20px;
    color:#d4af37;
}

.card p{
    padding:0 20px;
    color:#ddd;
}

.card strong{
    display:block;
    padding:20px;
    font-size:24px;
}

.card button{
    width:90%;
    margin:0 5% 25px;
    padding:15px;
    background:#d4af37;
    color:#000;
    border:none;
    border-radius:10px;
    font-weight:bold;
    cursor:pointer;
    transition:.3s;
}

.card button:hover{
    background:#f3d46b;
}
