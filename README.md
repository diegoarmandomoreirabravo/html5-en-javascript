html5-en-javascript
===================
<html>
	<head>
		<title>html5 en script</title>
	</head>
	<body bgcolor="black" text="white" background="portada de dragon ball z.gif" onload="llamar()">
		<form>
			<div id="script"></div>
		</form>
	</body>
</html>

<script>
	function llamar () 
	{
		var etiquetas="";
		etiquetas+="<center> <h1> <i> <font face='Times New Roman'>BV DIEGO MOREIRA XD</font></i> </h1> </center>"
		etiquetas+="<nav><ul><li> <b> <h3> <a href='1'>Inicio</a> </h3> </b> </li><li> <b> <h3> <a href='2'>Sobre nosotros</a> </h3> </b> </li><li> <b> <h3> <a href='3'>Contactenos</a> </h3> </b> </li></ul></nav>"
		etiquetas+="<p><figure><img src='dragon ball z2.gif'  width='400px' height='450px'hspace='430'> <center><figcaption>DRAGON BALL BUDOKAI</figcaption></center></figure></p>"
		+"<aside><font color='black'> <p align='justify'> Para empezar, puede pedir una buena película. Lo cual Dragon Ball Z: La batalla de los Dioses no lo es. Es un epílogo de 89 minutos a una serie que duró una década y le sobran los epílogos. No quita ni agrega nada, no posee ninguna ambición, empieza antes de que se den cuenta y termina antes de que se den cuenta que empezó. Es el tipo de entretenimiento inconsecuente que sólo quiere conciliarse con el espectador fanático, que estará más que satisfecho con encontrarse que nada ha cambiado desde su infancia. Los demás se verán alienados y anonadados por la insensatez de la trama.</p> </font></aside>"
		+"<section><header><font color='blue'><h4> Sinfonia de Dragon ball gt</h4></font></header></section>"
		+"<p><audio src='D:\DIEGO\Diego U\programacion web\deber\sinfonia dragon ball gt.mp3'preload='auto'controls loop></p>"
		+"<section><header><font color='blue'><h1>Naruto Shippuden 329</h1></font></header></section>"
        +"<p><video src='D:\DIEGO\Diego U\programacion web\deber\Naruto shippuden 329.mp4'width='1100'height='700' controls></video></p>"
        +"<hgroup><font color='black'><h1>ANIME NARUTO SHIPPUDEN</h1><h2>PERSONAJES</h2></font></hgroup>"
        +"<p>Uzumaki Naruto<bdi>??? ????</bdi></p><p>Uchiha Sasuke<bdi>??? ???</bdi></p>"
        +"<mark> <label>Dinos cual es tu color favorito:</label> </mark>"
        +"<input type='text'id='color_favorito'list='colores' />"
        +"<datalist id='colores'><option value='Azul' /><option value='Amarillo' /><option value='Rojo' /><option value='Verde' /><option value='Negro' /><option value='Blanco' /><option value='Naranja' /></datalist>"
        +"<table border='1'><tr><th>January <dialog open>primer mes del año</dialog></th><th>February <dialog open>segundo mes del año</dialog> </th><th>March <dialog open>tercer mes del año</dialog> </th></tr><tr><td>31</td><td>28</td><td>31</td></tr></table>"
        +"<embed src= 'Naruto shippuden 6th opening (HQ).mp3'type='audio/mp3'autostart='false'width='500' height='' volume='100'></embed>"
        +"<p>Descarga en progreso:</p>"
        +"<progress value='22' max='100'></progress><br>"
        +"<ruby>?<rp>???</rp></ruby><ruby>?? <rt>???</rt></ruby>"
        +"<summary>Cliqueame para mostrar o esconder</summary>"
        +"<p>Aquí va el contenido que se muestra o esconde dependiendo de nuestro clic. Recuerda, aquí no se está usando absolutamente nada de Javascript!</p><br>"
        +"<p> LA HORA ES:</p>"
        +"<timer> 22:02:30 </timer>"
        +"<footer><font color='black'><p>© 2010 Html 5 Todos los derechos reservados.</p></font></footer>"


		document.getElementById('script').innerHTML=etiquetas;
	}
</script>

