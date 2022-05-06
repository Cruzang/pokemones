# pokemones
Proyecto de uso de la API de Pokemon bla bla
<html><head>
<script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">

</head>  

<body>
<div id="app1" class="container">  
    <h1>{{titulo}}</h1>
    
    <div class="row">
        <div class="col">
    <ul>    
        <li v-for="poke in pokemones">
  <a v-for:click="poke.url">{{poke.name}}</a>
  </li>
    </ul>     
    <button v-on:click="pokes(siguiente)" class="btn btn-primary">siguiente</button>
    Total de pokemones: {{totalpokes}}
    <button v-on:click="pokes(anterior)" class="btn btn-warning">Anteriores</button>
     
</div>
        <div class="col">
            <h3>Imagen del Pokemon</h3>
            <img src="">
        </div>
<script>
</script>    

</div></div></body></html>
