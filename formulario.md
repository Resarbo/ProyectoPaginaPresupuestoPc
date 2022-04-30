# ProyectoPaginaPresupuestoPc
<html>
    <head>
        <title>formulario</title>
    </head>
    <body> 
    
<!--tipo de uso-->
<div> 
    <h2>Tipo de Uso </h2>
        <input type="radio" id="rbnPCMultimedia" name="tipodeuso" value="PCMultimedia">
        <label for="rbnPCMultimedia">PC Multimedia</label><br>
        <input type="radio" id="rbnPCGaming" name="tipodeuso" value="PCGaming">
        <label for="rbnPCGaming">PC Gaming</label><br>
        <input type="radio" id="rbnPCEdicion" name="tipodeuso" value="PCEdicion">
        <label for="rbnPCEdicion">PC Edicion</label><br>
        <input type="radio" id="rbnPCStreaming" name="tipodeuso" value="PCMStreaming">
        <label for="rbnPCStreaming">PC Streaming</label><br>
</div>

<!--tipos de presupuestos-->
    <h2>Ttipo de presupuesto </h2>
        <input type="radio" id="rbnLomaseconomico" name="tipodepresupuesto" value="Lomaseconomico">
        <label for="rbnLomaseconomico">Lo mas economico</label><br>
        <input type="radio" id="rbnEquilibrado" name="tipodepresupuesto" value="Equilibrado">
        <label for="rbnEquilibrado">Equilibrado</label><br>
        <input type="radio" id="rbnLomejor" name="tipodepresupuesto" value="Lomejor">
        <label for="rbnLomejor">Lo mejor</label><br>


<!--tamaño del PC-->
    <h2>tamaño de PC </h2>
        <input type="radio" id="rbnMini" name="tamañodelPC" value="Mini">
        <label for="rbnMini">Mini(ITX)</label><br>
        <input type="radio" id="rbnPequeño" name="tamañodelPC" value="Pequeño">
        <label for="rbnPequeño">Pequeño(Micro ATX)</label><br>
        <input type="radio" id="rbnEstandar" name="tamañodelPC" value="Estandar">
        <label for="rbnEstandar">Estandar (ATX)</label><br>
        <input type="radio" id="rbnGigante" name="tamañodelPC" value="Gigante">
        <label for="rbnMini">Gigante(ATX Y EATX)</label><br>
<!--Diseño  -->
    <h2>Diseño </h2>
        <input type="radio" id="rbnBasico" name="diseño" value="Basico">
        <label for="rbnBasico">Basico</label><br>
        <input type="radio" id="rbnRGB" name="diseño" value="RGB">
        <label for="rbnRGB">RGB</label><br>
        <input type="radio" id="rbnMinimal" name="diseño" value="Minimal">
        <label for="rbnMinimal">Minimal</label><br>
        <input type="radio" id="rbnDediseño" name="diseño" value="Dediseño">
        <label for="rbnDediseño">De diseño</label><br>

    <h2>Fundas de cable </h2>
<!--fundas de cable -->
        <input type="radio" id="rbnNO" name="fundasdecable" value="NO">
        <label for="rbnNO">NO</label><br>
        <input type="radio" id="rbnSI" name="fundasdecable" value="SI">
        <label for="rbnSI">SI</label>  <br>

    <h2>Tipos de refrigeracion </h2>
<!--tipos de Refrigeracion-->

        <input type="radio" id="rbnStock" name="tipoderefrigeracion" value="Stock">
        <label for="rbnStock">Stock</label> <br>
        <input type="radio" id="rbnAire" name="tipoderefrigeracion" value="Aire">
        <label for="rbnAire">Aire</label> <br>
        <input type="radio" id="rbnLiquida" name="tipoderefrigeracion" value="Liquida">
        <label for="rbnLiquida">Liquida</label> <br>
        <input type="radio" id="rbnLiquidaCustom" name="tipoderefrigeracion" value="LiquidaCustom">
        <label for="rbnLiquidaCustom">Liquida Custom</label> <br>





    <br>
       <h1> <input type="submit" value="Buscar"></h1>
    </body>   
</html>
