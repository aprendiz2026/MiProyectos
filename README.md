<html>
<head>
    <meta charset="UTF-8">
    <title>Formularios e Inputs</title>
</head>
<body>
    <button type ="button">INICIO</button>
    <h1>Formulario de registro</h1>
    <p>
        pide al usuario opciones de registro, como nombre, 
        correo electrónico y contraseña.
    </p>

        <p>
            si pones requiquired en el input, 
            el usuario no podra enviar el formulario si 
            no llena ese campo.
        </p>
    <h2>Formulario de registro usando atributos placeholder</h2>
<form>
    para que el usuario sepa que debe ingresar en cada campo,
    se puede usar el atributo placeholder, que muestra un texto

    <input type="text"  placeholder="Nombre">     
    <input type="password" placeholder="Contraseña">
    <input type="checkbox"  placeholder="Contraseña">
    <input type="email"  placeholder="email">
    <input type="radio"  placeholder="radio">
    <input type="date"  placeholder="datos">   
    <button type="submit">Ingresar</button>

   <p>
    hace que el usuario no pueda enviar el formulario si no 
    llena ese campo.
   </p>

    <h3>Formulario de registro usando atributos required</h2>
    <input type="text" name="Nombre" required>     
    <input type="password" name="clave" required>
    <input type="checkbox" name="clave" required>
    <input type="email" name="email" required>
    <input type="radio" name="clave" required>
    <input type="date" name="clave" >   
    <button type="submit">Ingresar</button>

    <p>
        
    </p>

    <h2>Formulario de registro usando atributos name</h2>

    <input type="text"  name ="Nombre">     
    <input type="password" name="contraseña" >
    <input type="checkbox" name="caja" >
    <input type="email" name="EMAIL" >
    <input type="radio" name="espacio" >
    <input type="date" name="clave">   
    <button type="submit">Ingresar</button>

    <h2>Formulario de registro usando atributos minlength y 
    maxlength, decide cuanto es el maximo o minimo de caracteres</h2>

    <input type="text" name="Nombre" required minlength="3" maxlength="10">     
    <input type="password" name="clave" required minlength="3" maxlength="10">
    <input type="checkbox" name="clave" required minlength="3" maxlength="10">
    <input type="email" name="email" required>
    <input type="radio" name="clave" required>
    <input type="date" name="clave" >   
    <button type="submit">Ingresar</button>

    
    </form>

</body>
</html>
