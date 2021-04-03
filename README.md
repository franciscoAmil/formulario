<html lang="en">
<head>
          <meta charset="UTF-8">
          <meta http-equiv="X-UA-Compatible" content="IE=edge">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>Document</title>
</head>

          <img src="tecnm.png">
          <img src="logo.png" style="float: right;"> 

          <center>    
                    <h1 style="text-align: center;">FORMULARIO DE ALUMNOS DEL TECNOLOGICO </h1>
          </center>
      
    <form action="https://franciscoamil.github.io/formulario/" >

      <table style=" table-layout: fixed;
      width: 60%;
      height: 650px;
      border-collapse: collapse;
      border: 3px solid black;"
      align="center">
      

        <tr>
          <td>NC:</td>
          <td><input type="text" name="nc"></td><br>
        </tr>
        <tr>
          <td>Contraseña:</td>
          <td><input type="password" name="nc"></td>
        </tr>
        <tr>
          <td>Nombre:</td>
          <td><input type="text" name="nom"></td>
        </tr>
        <tr>
          <td>Apellidos:</td>
          <td><input type="text" name="ap"></td>
        </tr>
        <tr>
          <td>Especialidad:</td>
          <td>
            <select name="esp">
              <option value="1"> Ing. Sistemas computacionales
              <option value="2"> Ing. Civil 
              <option value="3"> Ing. Biquímica
              <option value="4"> Ing. Gestión Empresarial
              <option value="6"> Ing. Mecatrónica
              <option value="7"> Ing. Electrónica
              <option value="8"> Ing. Industrial
              <option value="9"> Ing. logística
              <option value="10"> Lic. Contaduria
              <option value="11"> Lic. Administración
            </select>
          </td>
        </tr>
        <tr>
          <td>Fecha de nacimiento:</td>
          <td><input type="text" name="Ed"></td>
          
        </tr>
        <tr>
          <td>Genero:</td>
          <td>
            <input type="radio" name="gn" value="F">Femenino<br>
            <input type="radio" name="gn" value="M">Masculino
          </td>
        </tr>
        <tr>
          <td>Fecha de ingreso:</td>
          <td><input type="text" name="fi"></td>
        </tr>
        <tr>
          <td>Seleccione si fue el caso</td>
          <td>
            <input type="checkbox" name="rep">¿Reprobo alguna materia?
          </td>
        </tr>
        <tr>
          <td>Comentarios:</td>
          <td>
            <textarea name="comenta" rows="5" cols="30"></textarea>
          </td>
        </tr>
        <td> </td>
          <td><input type="submit" value="guardar"></td>
        
      
    </form>

</html>
