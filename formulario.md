<!DOCTYPE html>
<html lang="es">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
        <link rel="shortcut icon" type="image/ico" href="img/equipo.ico">
        <link rel="stylesheet" href="css1/estilos.css">
        <link rel="stylesheet" href="css1/normalize.css">
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Lato:wght@300&family=Water+Brush&display=swap" rel="stylesheet">
        <link rel="stylesheet" href="css1/fonts.css">
        <link rel="stylesheet" href="css1/main.css">
        <link rel="stylesheet" href="css1/mystyle.css">
        <title>Proyecto Pc</title>

        <meta name="keywords" content="" />
        <meta name="description" content="">
        <meta name="author" content="">
    </head>

    <body> 
        <div id="cabezera">
            <header>
                    <div class="barra bg-nav" >
                      <a href="index.html"><img class="imagen-logo" src="img/logo.png" alt="LogoEmpresa" ></a>
                       <span style="color: white;">  </span>
                      <nav> 
                        <div class="flexcaja-texto">
                          <div class="efecto-click">
                          <a href="index.html" class="nav-texto">Inicio</a> 
                          </div>
                          <div  class="efecto-click">
                          <a href="ArmaTupc.html" class="nav-texto">Arma Tu PC</a>
                          </div>
                          <div  class="efecto-click">
                            <a href="Presupuesto.html" class="nav-texto">Presupuesto</a>
                          </div>
                        </div>
                        
                      </nav>
                    </div>
            </header>
        </div>
        
    <div id="container">
      <div id="titulo">
        Presupuesto 
    </div>
   <div id="subtitulo"> <n>Escoge lo que nesesitas y selecciona tu PC a tu gusto</n></div>
 
    <div id="TIPO-DE-USO" > 
    <!--tipo de uso-->
      <h1>Tipo de uso</h1>
          <input type="radio" id="rbnPCMultimedia" name="tipodeuso" value="PCMultimedia">
          <label for="rbnPCMultimedia">PC Multimedia</label><br>
          <input type="radio" id="rbnPCGaming" name="tipodeuso" value="PCGaming">
          <label for="rbnPCGaming">PC Gaming</label><br>
          <input type="radio" id="rbnPCEdicion" name="tipodeuso" value="PCEdicion">
          <label for="rbnPCEdicion">PC Edicion</label><br>
          <input type="radio" id="rbnPCStreaming" name="tipodeuso" value="PCMStreaming">
          <label for="rbnPCStreaming">PC Streaming</label><br>
    </div> 

   
<div id="TIPO-DE-PRESUPUESTO">
<!--tipos de presupuestos-->
        <h1>Tipo de presupuesto </h1>
        <input type="radio" id="rbnLomaseconomico" name="tipodepresupuesto" value="Lomaseconomico">
        <label for="rbnLomaseconomico">Lo mas economico</label><br>
        <input type="radio" id="rbnEquilibrado" name="tipodepresupuesto" value="Equilibrado">
        <label for="rbnEquilibrado">Equilibrado</label><br>
        <input type="radio" id="rbnLomejor" name="tipodepresupuesto" value="Lomejor">
        <label for="rbnLomejor">Lo mejor</label><br>
</div>

<div id="TAMAÑO-DE-PC" >
    <!--tamaño del PC-->
    <h1>Tamaño de PC </h1>
        <input type="radio" id="rbnMini" name="tamañodelPC" value="Mini">
        <label for="rbnMini">Mini(ITX)</label><br>
        <input type="radio" id="rbnPequeño" name="tamañodelPC" value="Pequeño">
        <label for="rbnPequeño">Pequeño(Micro ATX)</label><br>
        <input type="radio" id="rbnEstandar" name="tamañodelPC" value="Estandar">
        <label for="rbnEstandar">Estandar (ATX)</label><br>
        <input type="radio" id="rbnGigante" name="tamañodelPC" value="Gigante">
        <label for="rbnMini">Gigante(ATX Y EATX)</label><br>
</div>

<div id="DISEÑO">
    <!--Diseño  -->
    <h1>Diseño </h1>
        <input type="radio" id="rbnBasico" name="diseño" value="Basico">
        <label for="rbnBasico">Basico</label><br>
        <input type="radio" id="rbnRGB" name="diseño" value="RGB">
        <label for="rbnRGB">RGB</label><br>
        <input type="radio" id="rbnMinimal" name="diseño" value="Minimal">
        <label for="rbnMinimal">Minimal</label><br>
        <input type="radio" id="rbnDediseño" name="diseño" value="Dediseño">
        <label for="rbnDediseño">De diseño</label><br>

</div>
<div id="FUNDAS-DE-CABLE">
    <h1>Fundas de cable </h1>
<!--fundas de cable -->
        <input type="radio" id="rbnNO" name="fundasdecable" value="NO">
        <label for="rbnNO">NO</label><br>
        <input type="radio" id="rbnSI" name="fundasdecable" value="SI">
        <label for="rbnSI">SI</label>  <br>

</div>
<div id="TIPOS-DE-REFRIGERACION">
    <h1>Tipos de refrigeracion </h1>
    <!--tipos de Refrigeracion-->
    
            <input type="radio" id="rbnStock" name="tipoderefrigeracion" value="Stock">
            <label for="rbnStock">Stock</label> <br>
            <input type="radio" id="rbnAire" name="tipoderefrigeracion" value="Aire">
            <label for="rbnAire">Aire</label> <br>
            <input type="radio" id="rbnLiquida" name="tipoderefrigeracion" value="Liquida">
            <label for="rbnLiquida">Liquida</label> <br>
            <input type="radio" id="rbnLiquidaCustom" name="tipoderefrigeracion" value="LiquidaCustom">
            <label for="rbnLiquidaCustom">Liquida Custom</label> <br>
</div >

    <br>
    <div class="contenedor-boton">
        <button class="boton"><span>GENERAR PRESUPUESTO</span></button>
    </div>
    </div>
    <div class="social-bar">
        <a href="https://www.facebook.com" class="icon icon-facebook" target="_blank"></a>
        <a href="https://twitter.com" class="icon icon-twitter" target="_blank"></a>
        <a href="https://www.youtube.com" class="icon icon-youtube" target="_blank"></a>
        <a href="https://www.instagram.com" class="icon icon-instagram" target="_blank"></a>
      </div>
      
   <div style="color: aliceblue;">
    <br>.<br>.<br>.<br>.<br>.<br>.<br>.<br>.<br>.<br>.<br>.<br>.
    <br>.<br>.<br>.<br>.<br>.<br>.<br>.<br>.<br>.<br>.<br>.<br>.
    <br>.<br>.<br>.<br>.<br>.<br>
    <br>.<br>.<br>.<br>.<br>.<br>.<br>.<br>.<br>.<br>.<br>.<br>.
    <br>.<br>.<br>.<br>.<br>.<br>.<br>.<br>.<br>
  </div>

      <footer class="text-center text-lg-start bg-light text-muted " >
   
    
        <hr>
        
    
        <div class="bg-color-footer"></div>
  
        <section class="mr-derecha" >
          <div class="container text-center text-md-start mt-5">
        
            <div class="row mt-3">
            
              <div class="col-md-3 col-lg-4 col-xl-3 mx-auto mb-4 ">
           
                
                <h4 class="text-uppercase fw-bold mb-4">
                  <i class="fas fa-gem me-3"></i>TECNOempresa
                </h4>
                <p>
                  Empresa dedicada a la contización y venta de articulos tecnologicos para computadoras.
                </p>
              </div>
              
           
              <div class="col-md-3 col-lg-2 col-xl-2 mx-auto mb-4">
         
                <h4 class="text-uppercase fw-bold mb-4">
                  Sobre Nosotros
                </h4>
                <p>
                  <a href="#!" class="text-reset">Privacidad</a>
                </p>
                <p>
                  <a href="#!" class="text-reset">Medio de pago</a>
                </p>
                <p>
                  <a href="#!" class="text-reset">Garantia</a>
                </p>
                <p>
                  <a href="#!" class="text-reset">Politica</a>
                </p>
              </div>
       
              <div class="col-md-4 col-lg-3 col-xl-3 mx-auto mb-md-0 mb-4">
               
                <h4 class="text-uppercase fw-bold mb-4">
                  Contacto
                </h4>
                <p><i class="fas fa-home me-3"></i> ICA, San Francisco, Perú</p>
                <p>
                  <i class="fas fa-envelope me-3"></i>
                  TECNO@gmail.com
                </p>
                <p><i class="fas fa-phone me-3"></i> + 51 958248856</p>
               
              </div>
              <!-- Grid column -->
            </div>
            <!-- Grid row -->
          </div>
        </section>
        <!-- Section: Links  -->
      
        <!-- Copyright -->
        <div class="text-center p-4" style="background-color: rgba(0, 0, 0, 0.05);">
          © 2021 Copyright:
          <a class="text-reset fw-bold" href="">TECNOempresa.com</a>
        </div>
      
        <!-- Copyright -->
      </footer>
    </body>

</html>
