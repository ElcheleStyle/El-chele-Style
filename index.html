<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8"><meta name="viewport" content="width=device-width,initial-scale=1">
<title>EL CHELE Style</title>
<style>
body{background:#0a0a0a;color:#fff;font-family:Arial;margin:0;padding-bottom:80px}
header{display:flex;align-items:center;justify-content:space-between;padding:12px 15px;background:#0f0f0f;position:sticky;top:0;z-index:10}
.logo{width:55px;height:55px;border-radius:50%;border:2px solid #222;object-fit:cover}
.tabs{display:flex;justify-content:space-around;background:#141414;padding:12px 0;border-bottom:1px solid #222;position:sticky;top:79px;z-index:9}
.tabs button{background:none;border:none;color:#666;font-weight:900;font-size:14px;cursor:pointer;padding-bottom:8px}
.tabs button.active{color:#00d4ff;border-bottom:3px solid #00d4ff}
.grid{display:grid;grid-template-columns:1fr;gap:12px;padding:12px}
@media(min-width:600px){.grid{grid-template-columns:1fr 1fr 1fr}}
.card{background:#1a1a1a;border-radius:14px;padding:10px;border:1px solid #222}
.card img{width:100%;height:260px;object-fit:cover;border-radius:10px;background:#000}
.double{display:grid;grid-template-columns:1fr 1fr;gap:8px}
.double div{text-align:center}
.double small{color:#aaa;font-size:11px}
.precio{color:#00ff88;font-weight:bold;font-size:20px;margin:6px 0}
.tallas{font-size:12px;color:#aaa}
.btn-wa{width:100%;background:#25D366;color:#fff;border:none;padding:10px;border-radius:20px;margin-top:8px;font-weight:bold;cursor:pointer}
.wa-bar{position:fixed;bottom:0;left:0;right:0;background:#111;border-top:1px solid #222;padding:10px 15px;display:flex;justify-content:space-between;align-items:center}
</style>
</head>
<body>

<header>
  <div style="display:flex;gap:10px;align-items:center">
    <img src="images/logo.png" class="logo">
    <div style="font-weight:900;line-height:1">EL CHELE<br><span style="font-weight:400;font-style:italic">Style</span></div>
  </div>
  <div>🔍 🛒</div>
</header>

<div class="tabs">
  <button class="active" onclick="filtrar('anime',this)">ANIME</button>
  <button onclick="filtrar('marcas',this)">MARCAS</button>
  <button onclick="filtrar('doble',this)">DOBLE ESTAMPADO</button>
</div>

<div class="grid" id="tienda"></div>

<div class="wa-bar">
  <div style="display:flex;gap:8px;align-items:center"><span style="background:#25D366;padding:6px 10px;border-radius:50%">W</span><div><b>WhatsApp 6985 4456</b><br><small>Respuesta inmediata</small></div></div>
  <button onclick="window.open('https://wa.me/50369854456','_blank')" style="background:#25D366;border:none;color:#fff;padding:8px 14px;border-radius:20px;font-weight:bold">Chat</button>
</div>

<script>
const productos=[
  // ANIME - tu Luffy nueva
  {id:1, nombre:"Camiseta Luffy One Piece", subt:"Black • Estampado Back", categoria:"anime", foto:"images/luffy-nueva.jpg", precio:5},
  
  // MARCAS - tu Adidas azul
  {id:2, nombre:"Camiseta Adidas Colorblock", subt:"Navy • Dot Pattern", categoria:"marcas", foto:"images/adidas-azul.jpg", precio:5},

  // DOBLE ESTAMPADO - tu Suzuki en 1 sola publicación
  {id:3, nombre:"Camiseta Suzuki Biker Life", subt:"Black • Frente + Espalda", categoria:"doble", precio:5, esDoble:true, fotos:["images/suzuki-frente.jpg","images/suzuki-espalda.jpg"]},
];

let cat="anime";
function filtrar(c,btn){
  cat=c;
  document.querySelectorAll('.tabs button').forEach(b=>b.classList.remove('active'));
  btn.classList.add('active');
  render();
}
function render(){
  let html="";
  productos.filter(p=>p.categoria===cat).forEach(p=>{
    if(p.esDoble){
      html+=`<div class="card">
        <div class="double">
          <div><img src="${p.fotos[0]}"><small>Frente</small></div>
          <div><img src="${p.fotos[1]}"><small>Espalda</small></div>
        </div>
        <div style="margin-top:8px"><b>${p.nombre}</b><br><small style="color:#888">${p.subt}</small>
        <div class="precio">$${p.precio}</div><div class="tallas">S-M-L • $6 XL</div>
        <button class="btn-wa" onclick="pedir('${p.nombre}')">DOBLE • Pedir - 6985 4456</button></div></div>`;
    } else {
      html+=`<div class="card"><img src="${p.foto}"><div style="margin-top:8px"><b>${p.nombre}</b><br><small style="color:#888">${p.subt}</small>
      <div class="precio">$${p.precio}</div><div class="tallas">S-M-L • $6 XL</div>
      <button class="btn-wa" onclick="pedir('${p.nombre}')">${p.categoria.toUpperCase()} • Pedir</button></div></div>`;
    }
  });
  document.getElementById('tienda').innerHTML=html;
}
function pedir(nombre){
  let talla=prompt("Talla S,M,L ($5) o XL ($6)?","L");
  if(!talla) return;
  let precio=talla.toUpperCase()=="XL"?6:5;
  let msg=`Hola EL CHELE Style! Quiero ${nombre} Talla ${talla} Precio $${precio} - Visto en ${cat.toUpperCase()}`;
  window.open(`https://wa.me/50369854456?text=${encodeURIComponent(msg)}`,'_blank');
}
render();
</script>
</body>
</html>
