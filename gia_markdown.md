<p align="center">
    <img src="imagen/Alan_Diaz.png">
</p>

# Realizando Practicas en Markdown
En este apartado se estará creando ciertas actividades o prácticas usando **Markdown** para las siguientes prácticas que se estarán realizando durante el curso.

Hasta incluso se estará haciendo tareas con este tipo de plataformas en la clase de sistemas programables

# ¿Qué es Markdown?
> Esta herramienta fue creada en 2004 por John Gruber, y se distribuye de manera gratuita bajo una licencia BSD.

>Aunque en realidad Markdown también se considera un lenguaje que tiene la finalidad de permitir crear contenido de una manera sencilla de escribir, y que en todo momento mantenga un diseño legible, así que para simplificar puedes considerar Markdown como un método de escritura.

![](imagen/office.jpg)

# Por qué utilizar Markdown
> Este tipo de formato siempre será compatible con todas las plataformas que utilices, así que utilizar Markdown es una manera de mantener todo tu contenido siempre accesible desde cualquier dispositivo (smartphones, ordenadores de escritorio, tablets…), ya que en cualquiera de ellas siempre encontrarás las aplicaciones adecuadas para leer y editar este tipo de contenido.

# Codigo de ejemplo en JavaScript
```javascript
//Escribir con JavaScript Simplificado
let writingf = (strs) => {
	let arrFromStrs = strs.split('');
	let j = 0;

	let printStrf = setInterval(function(){
		document.getElementById('texto2').innerHTML += arrFromStrs[j];
		j++;

		if(j === arrFromStrs.length){
			clearInterval(printStrf);
		}
	},400);
};

writingf('Hola Mundo');
```

# Comparacion de HTML/CSS y Markdown
Teniendo en referencia que es mi punto de vista al usar los dos lenguajes al escribir texto en ellos mismos.

| HTML y CSS                                                               | Markdown                                                                           |   |   |   |
|--------------------------------------------------------------------------|------------------------------------------------------------------------------------|---|---|---|
| Se tiene que poner en etiquetas para expecificar lo que quieres realizar | En este lenguaje solo debes conocer ciertos caracteres que especifican cada cosa   |   |   |   |
| La colocacion de imagenes es similar pero usando etiquetas               | En este se usa su sintaxis especifico en ![]() o puedes usar la etiqueta de html.  |   |   |   |
| En este no se puede usar caracteres de Markdown                          | Pero en Markdown puede usar ciertas etiquetas que se utiliza en html               |   |   |   |
# Referencias
s.a. (s.a.). Markdown - La guía definitiva en español. Recuperado en: https://markdown.es/
