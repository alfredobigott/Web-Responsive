# Web-Responsive
Connecting different css templates via javacrypt

<!DOCTYPE html>
<html>
  <head>
    <meta http-equiv="content-type" content="text/html"; charset="utf-8">
    <script type="text/javascript" src="js/jquery.js"></script>
    <script type="text/javascript">
      $(document).ready(inicio)
       function inicio(){
         $("select").change(cambiacss)
       }
       function cambiacss(){
         var plantilla =$("select").attr("value");
         $("plantilla").html('<link rel="stylesheet" href="css/'+plantilla+'.css" type="text/css">')
       }
    </script>
    <link rel="stylesheet" href="css/base.css" type="text/css">
    <plantilla>

    </plantilla>
    <title></title>
  </head>
  <body>
    <select name="plantilla">
      <option value="">Seleccione una plantilla</option>
      <option value="pc1">Plantilla para pc</option>
      <option value="pchd">Plantilla alta definición</option>
      <option value="movil">Plantilla para movil</option>
      <option value="tablet">Plantilla para tableta digital</option>
    </select>
    <hr>
    <div id="contenedor">
      <header>
        <div id="titulo">
          <div id="logo">
              <h1>Alfredo Manuel Bigott</h1>
              <h2>Eslogan de la web</h2>
          </div>
        </div>
        <nav>
          <ul>
            <li><a href="index.html">Inicio</a></li>
            <li><a href="blog.html">Blog</a></li>
            <li><a href="productos.html">Productos</a></li>
            <li><a href="contactos.html">Contactos</a></li>
          </ul>
        </nav>
      </header>
      <section>
        <div id="banner">
          <h3>Título del banner</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce quis convallis nunc.
             Phasellus sit amet placerat turpis. Praesent non ex rutrum odio maximus finibus vel nec elit.
              Proin laoreet placerat arcu. Quisque sed metus nibh. Quisque non congue lacus,
             quis faucibus felis. Nullam pellentesque in lorem et posuere. Curabitur quis dapibus justo.</p>
        </div>
        <article>
          <div class="imagendestacado" id="img1">
          </div>
          <h3>Título del destacado</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce quis convallis nunc.
             Phasellus sit amet placerat turpis. Praesent non ex rutrum odio maximus finibus vel nec elit.
              Proin laoreet placerat arcu. Quisque sed metus nibh. Quisque non congue lacus,
             quis faucibus felis. Nullam pellentesque in lorem et posuere. Curabitur quis dapibus justo.</p>
        </article>
        <article>
          <div class="imagendestacado" id="img1">
          </div>
          <h3>Título del destacado</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce quis convallis nunc.
             Phasellus sit amet placerat turpis. Praesent non ex rutrum odio maximus finibus vel nec elit.
              Proin laoreet placerat arcu. Quisque sed metus nibh. Quisque non congue lacus,
             quis faucibus felis. Nullam pellentesque in lorem et posuere. Curabitur quis dapibus justo.</p>
        </article>
        <article>
          <div class="imagendestacado" id="img1">
          </div>
          <h3>Título del destacado</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce quis convallis nunc.
             Phasellus sit amet placerat turpis. Praesent non ex rutrum odio maximus finibus vel nec elit.
              Proin laoreet placerat arcu. Quisque sed metus nibh. Quisque non congue lacus,
             quis faucibus felis. Nullam pellentesque in lorem et posuere. Curabitur quis dapibus justo.</p>
        </article>
      </section>
      <footer>Pié</footer>
    </div>
  </body>
</html>
