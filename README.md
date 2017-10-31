@charset "utf-8";
/* Mídia fluida simples
   Nota: a mídia fluida exige a remoção dos seus atributos de comprimento e largura do HTML
   http://www.alistapart.com/articles/fluid-images/ 
*/
img, object, embed, video {
 max-width: 100%;
 font-size: 18px;
}
/* O IE 6 não oferece suporte a largura máxima; por isso, o padrão de largura deve ser 100% */
.ie6 img {
	width:100%;
}

/*
	Propriedades de mídia fluida do Dreamweaver
	----------------------------------
	dw-num-cols-mobile:		16;
	dw-num-cols-tablet:		18;
	dw-num-cols-desktop:	20;
	dw-gutter-percentage:	25;
	
	Inspiração do "Design da Web responsivo", por Ethan Marcotte 
	http://www.alistapart.com/articles/responsive-web-design
	
	e Sistema de grade dourada, por Joni Korpi
	http://goldengridsystem.com/
*/

/* Layout para celulares: menor ou igual a 480 px. */

.gridContainer {
	margin-left: auto;
	margin-right: auto;
	width: 89.8625%;
	padding-left: 0.5687%;
	padding-right: 0.5687%;
}
#topo {
 clear: none;
 float: left;
 margin-left: 1.2658%;
 width: 100%;
 display: none;
}
#topomobile {
	clear: both;
	float: left;
	margin-left: 0;
	width: 100%;
	display: block;
}
#topo_text {
	clear: both;
	float: left;
	margin-left: 0;
	width: 100%;
	display: block;
}
#bx1 {
	clear: none;
	float: left;
	margin-left: 7.5949%;
	width: 36.7088%;
	display: block;
}
#bx2 {
	clear: none;
	float: left;
	margin-left: 7.5949%;
	width: 36.7088%;
	display: block;
}
#bx3 {
	clear: none;
	float: left;
	margin-left: 7.5949%;
	width: 36.7088%;
	display: block;
}
#bx4 {
	clear: none;
	float: left;
	margin-left: 7.5949%;
	width: 36.7088%;
	display: block;
}
#bx5 {
	clear: none;
	float: left;
	margin-left: 7.5949%;
	width: 36.7088%;
	display: block;
}
#bx6 {
	clear: none;
	float: left;
	margin-left: 7.5949%;
	width: 36.7088%;
	display: block;
}
#corpo_text {
 clear: both;
 float: none;
 margin-left: 0;
 width: auto;
 display: block;
 padding: 5%;
 background-color: #FF3300;
 color: #FFFFFF;
}
#corpo_text2 {
 clear: both;
 float: left;
 margin-left: 0;
 width: 100%;
 display: block;
 font-family: Tahoma, Geneva, sans-serif;
 font-size: 20px;
 font-weight: bold;
 color: #333333;
 margin-top: 1%;
 margin-bottom: 1%;
}
#contexto {
 clear: both;
 float: left;
 margin-left: 0;
 width: 100%;
 display: block;
 font-size: 18px;
}
#contexto1 {
 clear: both;
 float: none;
 margin-left: 0;
 width: auto;
 display: block;
 margin-top: 1%;
 margin-bottom: 1%;
 font-family: Tahoma, Geneva, sans-serif;
 font-size: 20px;
 color: #FFF;
 background-color: #C00;
 padding: 5%;
}
#contexto3 {
 clear: both;
 float: left;
 margin-left: 0;
 width: 100%;
 display: block;
 font-family: Arial, Helvetica, sans-serif;
 font-size: 18px;
 color: #000;
}
#contexto_final {
 clear: both;
 float: none;
 margin-left: 0;
 width: auto;
 display: block;
 font-family: Tahoma, Geneva, sans-serif;
 font-size: 20px;
 font-weight: 200;
 background-color: #8C001C;
 padding: 3%;
 color: #FFF;
}
#footer {
 clear: both;
 float: left;
 margin-left: 0;
 width: 100%;
 display: block;
 margin-top: 2%;
 margin-bottom: 2%;
}

/* Layout para tablets: 481 px a 768 px. Herda estilos de: Layout para celulares. */

@media only screen and (min-width: 481px) {
.gridContainer {
	width: 91.9666%;
	padding-left: 0.5166%;
	padding-right: 0.5166%;
}
#LayoutDiv1 {
	clear: both;
	float: left;
	margin-left: 0;
	width: 100%;
	display: block;
}
#topo {
	clear: none;
	float: left;
	margin-left: 1.1235%;
	width: 100%;
	display: block;
}
#topomobile {
 clear: both;
 float: left;
 margin-left: 0;
 width: 100%;
 display: none;
}
#topo_text {
 clear: both;
 float: left;
 margin-left: 0;
 width: 100%;
 display: block;
}
#bx1 {
 clear: both;
 float: left;
 margin-left: 11.2359%;
 width: 21.3483%;
 display: block;
}
#bx2 {
 clear: none;
 float: left;
 margin-left: 6.7415%;
 width: 21.3483%;
 display: block;
}
#bx3 {
 clear: none;
 float: left;
 margin-left: 6.7415%;
 width: 21.3483%;
 display: block;
}
#bx4 {
 clear: both;
 float: left;
 margin-left: 11.2359%;
 width: 21.3483%;
 display: block;
}
#bx5 {
 clear: none;
 float: left;
 margin-left: 6.7415%;
 width: 21.3483%;
 display: block;
}
#bx6 {
 clear: none;
 float: left;
 margin-left: 6.7415%;
 width: 21.3483%;
 display: block;
}
#corpo_text {
 clear: both;
 float: none;
 margin-left: 0;
 width: auto;
 display: block;
 padding: 5%;
 background-color: #FF3300;
 color: #FFFFFF;
 font-weight: bold;
 font-family: Tahoma, Geneva, sans-serif;
 font-size: 18px;
}
#corpo_text2 {
 clear: both;
 float: left;
 margin-left: 0;
 width: 100%;
 display: block;
 margin-bottom: 1%;
 margin-top: 1%;
 font-size: 20px;
}
#contexto {
 clear: both;
 float: left;
 margin-left: 0;
 width: 100%;
 display: block;
}
#contexto1 {
 clear: both;
 float: none;
 margin-left: 0;
 width: auto;
 display: block;
 font-family: Tahoma, Geneva, sans-serif;
 font-size: 20px;
 color: #FFF;
 background-color: #C00;
 padding: 5%;
}
#contexto3 {
 clear: both;
 float: left;
 margin-left: 0;
 width: 100%;
 display: block;
}
#contexto_final {
 clear: both;
 float: left;
 margin-left: 0;
 width: 100%;
 display: block;
}
#footer {
 clear: both;
 float: left;
 margin-left: 0;
 width: 100%;
 display: block;
 margin-top: 2%;
 margin-bottom: 2%;
}
}

/* Layout para desktops: 769 px até o máximo de 1232 px. Herda estilos de: Layout para celulares e Layout para tablets. */

@media only screen and (min-width: 769px) {
.gridContainer {
 width: 100%;
 max-width: 1232px;
 padding-left: 0.45%;
 padding-right: 0.45%;
 margin: auto;
}
#LayoutDiv1 {
	clear: both;
	float: left;
	margin-left: 0;
	width: 100%;
	display: block;
}
#topo {
 clear: both;
 float: left;
 margin-left: 0;
 width: 100%;
 display: block;
 margin-top: 2%;
}
#topomobile {
 clear: both;
 float: left;
 margin-left: 0;
 width: 100%;
 display: none;
}
#topo_text {
 clear: both;
 float: left;
 margin-left: 0;
 width: 100%;
 display: block;
}
#bx1 {
 clear: both;
 float: left;
 margin-left: 0;
 width: 14.1414%;
 display: block;
 font-size: 18px;
}
#bx2 {
 clear: none;
 float: left;
 margin-left: 1.0101%;
 width: 14.1414%;
 display: block;
 font-size: 18px;
}
#bx3 {
 clear: none;
 float: left;
 margin-left: 1.0101%;
 width: 14.1414%;
 display: block;
 font-size: 18px;
}
#bx4 {
 clear: none;
 float: left;
 margin-left: 1.0101%;
 width: 19.1919%;
 display: block;
 font-size: 18px;
}
#bx5 {
 clear: none;
 float: left;
 margin-left: 1.0101%;
 width: 14.1414%;
 display: block;
 font-size: 18px;
}
#bx6 {
 clear: none;
 float: left;
 margin-left: 1.0101%;
 width: 19.1919%;
 display: block;
 font-size: 18px;
}
#corpo_text {
 clear: both;
 float: none;
 margin-left: 0;
 width: auto;
 display: block;
 font-family: Tahoma, Geneva, sans-serif;
 font-size: 22px;
 margin-top: 2%;
 background-color: #C00;
 padding: 5%;
 color: #FFFFFF;
 font-weight: bold;
}
#corpo_text2 {
 clear: both;
 float: left;
 margin-left: 0;
 width: 100%;
 display: block;
 margin-top: 2%;
 font-size: 20px;
 margin-bottom: 1%;
}
#contexto {
 clear: both;
 float: left;
 margin-left: 0;
 width: 100%;
 display: block;
 font-size: 18px;
 color: #333333;
}
#contexto1 {
 clear: both;
 float: none;
 margin-left: 0;
 width: auto;
 display: block;
 font-size: 20px;
 color: #FFFFFF;
 font-family: Tahoma, Geneva, sans-serif;
 background-color: #C00;
 padding: 5%;
 line-height: 100px;
}
#contexto3 {
 clear: both;
 float: left;
 margin-left: 0;
 width: 100%;
 display: block;
}
#contexto_final {
 clear: both;
 float: left;
 margin-left: 0;
 width: 100%;
 display: block;
}
#footer {
 clear: both;
 float: left;
 margin-left: 0;
 width: 100%;
 display: block;
 font-family: Tahoma, Geneva, sans-serif;
 font-size: 20px;
 margin-top: 2%;
 margin-bottom: 2%;
}
}
