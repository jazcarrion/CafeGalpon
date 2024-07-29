<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css/estilos.css">
    <link rel="icon" href="imgs/Icono Nescafe.webp">

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">
    <title>Nescafé®</title>
</head>
<body>
    <header>
            <a href="index.html" id="logo">
                <img src="imgs/Logo Nescafe.png" alt="Logo de la empresa Nescafe">
                <h1>Nescafe</h1>
            </a>
    
                <nav> 
                    <ul>
                        <li><a href="index.html">Inicio</a></li>
                        <li><a href="#historia">Nosotros</a></li>
                        <li><a href="pages/productos.html">Comprar</a></li>
                        <li><a href="#suscripcion">Suscribirse</a></li>
                    </ul>     
                </nav>
    </header>

    <main>
        <section>
            <figure>
                <img id="banner" src="imgs/Banner Nescafe Estandar.jpg" alt="Banner publicitario Producto Nescafe">
            </figure>
        </section>

        <section id="video">
            <h2>Conocé tu Nescafé</h2>

            <div id="filaVideo">
                <div id="iframe">
                    <iframe width="560" height="315" src="https://www.youtube.com/embed/Mi0ecEOiShI?si=5U8w9Ni4DpBQ7wyx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen=""></iframe>
                </div>
                <div id="texto">
                    <p>Elaborado a partir de una mezcla cuidadosamente seleccionada de granos de cafe Arabica de alta calidad. Los granos utilizados en provienen países como Colombia, Brasil, Honduras, Vietnam e Indonesia, conocidos por su calidad. El aroma es verdaderamente cautivador. Desde el momento en que abres el frasco, el delicioso aroma del café tostado se apodera de tus sentidos. Su versatilidad permite preparar una variedad de bebidas, como café con leche, capuchinos, lattes, e incluso se puede utilizar como base para recetas de postres y cócteles.</p>
                </div>
            </div>
        </section>



        <section id="historia">
            <div id="contenidoHistoria">
                    <h2>La fascinante historia de Nescafé</h2>
                    <p>Nescafé® está en las estanterías y mesas de todo el mundo. Es una fuente segura de inspiración, a la que puedes recurrir una y otra vez para disfrutar al máximo de tus mañanas, con o sin amigos. Es casi como si Nescafé® siempre hubiera estado ahí, dispuesto a ofrecer su maravilloso y exquisito sabor, que todo el mundo conoce y adora. Pero no siempre ha sido así; la historia de Nescafé® es tan inspiradora como una buena taza de café.
                    La historia se remonta a 1929, cuando Louis Dapples, Presidente del Consejo de Administración de Nestlé®, recibió una petición muy especial de Brasil. Para paliar el enorme excedente de café del país, se propuso que Nestlé® creara un producto de café que fuera rápido de elaborar y que, además, redujera la cantidad de residuos innecesarios de las cosechas de granos de café de Brasil. Inicialmente, la idea era fabricar una pastilla de café en forma de cubo, a la que simplemente había que añadir agua caliente para obtener una infusión instantánea. Sin embargo, tras muchas investigaciones, no se pudo conservar el sabor característico, por lo que el formato en pastillas no era viable. Descartada esta idea, el químico Max Morgenthaler volvió a la carga.</p>
            </div>

        </section>

        <section id="productos">
            <h2>Nuestros productos más vendidos.</h2>
            <p>Explorá toda la variedad de NESCAFÉ® y encuentra tu café perfecto.</p>
            <article>
                <figure>
                    <img src="imgs/Nescafe Gold.png" alt="Producto Nescafe Gold">
                </figure>
                <p id="estrellas">★★★★★</p>
                <p>Nescafé Gold</p>
                <p><strong>$13.500</strong></p>

                <div>
                    <a href="#prod1">Detalles</a>
                </div>
            </article>

            <article>
                <figure>
                    <img src="imgs/Nescafe Fina Selección Alta Rica.webp" alt="Producto Nescafe Fina Seleccion ALta Rica">
                </figure>
                <p id="estrellas">★★★★★</p>
                <p>Origenes Alta Rica</p>
                <p><strong>$11.275</strong></p>

                <div>
                    <a href="#prod2">Detalles</a>
                </div>
            </article>

            <article>
                <figure>
                    <img src="imgs/Nescafé Fina Selección Colombia.webp" alt="Producto Nescafe Fina Seleccion Colombia">
                </figure>
                <p id="estrellas">★★★★★</p>
                <p>Origenes Colombia</p>
                <p><strong>$11.275</strong></p>

                <div>
                    <a href="#prod3">Detalles</a>
                </div>
            </article>

            <article>
                <figure>
                    <img src="imgs/Nescafe Descafeinado.webp" alt="Producto Fina Selección Descafeinado">
                </figure>
                <p id="estrellas">★★★★★</p>
                <p>Nescafé Descafeinado</p>
                <p><strong>$7.599</strong></p>

                <div>
                    <a href="#prod4">Detalles</a>
                </div>
            </article>
            <div>
                <a id="verMas" href="pages/productos.html">Ver más</a>
            </div>
        </section>



        
<!--Ventana modal-->
<!--PROCUCTO 1-->
        <div id="prod1">
            <div id="modal">
                <div id="contenido">
                    <header>
                        <a href="#productos" class="cerrar">✖</a>
                        <h2>Nescafe Gold</h2>
                    </header>
                     <main>

                        <div id="flex1">
                                <figure>
                                    <img src="imgs/Nescafe Gold.png" alt="Producto Nescafe Gold">
                                </figure>
                            <div>
                                <p>Los granos de Arábica y Robusta que usamos para crear esta mezcla exclusiva son tostados con maestría para realzar sus sabores y aromas. Cada grano se tuesta a la temperatura óptima, hasta que alcanzan los estándares que hemos establecido para cada frasco de NESCAFÉ® GOLD.</p>
                                <a class="botonVentana" href="pages/productos.html">Comprar</a>
                            </div>
                        </div>
                        
                     </main>
                </div>
            </div>
        </div>


<!--PROCUCTO 2-->
        <div id="prod2">
            <div id="modal">
                <div id="contenido">
                    <header>
                        <a href="#productos" class="cerrar">✖</a>
                        <h2>Nescafe Alta Rica</h2>
                    </header>
                     <main>
                        <div id="flex1">
                            <figure>
                            <img src="imgs/Nescafe Fina Selección Alta Rica.webp" alt="Producto Nescafe Alta Rica">
                            </figure>
                        
                        

                            <div>
                                <p>NESCAFÉ® Gold Alta Rica es un café elaborado con granos arábicos de Latino América seleccionados cuidadosamente con notas a cacao.</p>
                                <a class="botonVentana" href="pages/productos.html">Comprar</a>
                            </div>
                        </div>
                     </main>
                </div>
            </div>
        </div>


<!--PROCUCTO 3-->
<div id="prod3">
    <div id="modal">
        <div id="contenido">
            <header>
                <a href="#productos" class="cerrar">✖</a>
                <h2>Nescafe Colombia</h2>
            </header>
             <main>

                <div id="flex1">
                        <figure>
                            <img src="imgs/Nescafé Fina Selección Colombia.webp" alt="Producto Nescafe Colombia">
                        </figure>
                
                    <div>
                        <p>NESCAFÉ Gold Origins Colombia es un café cosechado en la altura en clima tropical, con granos especialmente seleccionados por los cafecultores.</p>
                        <a class="botonVentana" href="pages/productos.html">Comprar</a>
                    </div>
                </div>
             </main>
        </div>
    </div>
</div>


<!--PROCUCTO 4-->
<div id="prod4">
    <div id="modal">
        <div id="contenido">
            <header>
                <a href="#productos" class="cerrar">✖</a>
                <h2>Nescafe Descafeinado</h2>
            </header>
             <main>

                <div id="flex1">
                        <figure>
                            <img src="imgs/Nescafe Descafeinado.webp" alt="Producto Nescafe Descafeinado">
                        </figure>
                

                    <div>
                        <p>NESCAFÉ® Decafeinado es un café unico con cuerpo y aroma delicado. Ideal para aquellas personas que quieren disfrutar de su café favorito sin cafeína.</p>
                        <a class="botonVentana" href="pages/productos.html">Comprar</a>
                    </div>
                </div>
             </main>
        </div>
    </div>
</div>






        
        <section id="suscripcion">
            <h2>¡SUSCRÍBETE!</h2>
            <p>¿Querés recibir un kit de productos NESCAFÉ® todos los meses? Hace tu suscripción, elegí tu línea favorita y ¡Listo! Vas a recibir mensualmente los productos de la linea que elegiste. Completa tus datos aqui.</p>

            <form action="pages/gracias.html" method="get">

                <div class="filas">
                    <div class="columnas">
                        <label for="nom"></label>
                        <input class="tamaño" type="text" name="nombre" id="nom" placeholder="Nombre">
                    </div>
                    <div class="columnas">
                        <label for="email"></label>
                        <input class="tamaño" type="email" name="email" id="email" placeholder="Email">
                    </div>
                </div>

                <div class="filas">
                    <div class="columnas">
                        <label for="seleccion"></label>
                        <select class="tamaño" id="seleccion" name="seleccion">
                        <option value="">Seleccione su Línea preferida</option>
                        <option value="classic">NESCAFÉ® Classic</option>
                        <option value="gold">NESCAFÉ® Gold</option>
                        <option value="farmers-origins">NESCAFÉ® Farmers Origins</option>
                        <option value="dolce-gusto">NESCAFÉ® Dolce Gusto</option> 
                        </select>
                    </div>
                </div>


                <div class="filas">
                    <div class="columnas">
                        <input class="boton" type="submit" value="Enviar">
                    </div>
                </div>
            </form>
        </section>   
    </main>


    <footer>
        <a href="index.html" id="logoFooter">
            <img src="imgs/Logo Nescafe.png" alt="Logo de la empresa Nescafe">
        </a>

        <ul id="redesSociales">
            <li class="iconos">
                <figure>
                    <a href="https://www.instagram.com/nescafeargentina/?hl=es"><img src="imgs/Logo Instagram.png" alt="Logo de Instagram"></a>
                </figure>
            </li>

            <li class="iconos">
                <figure>
                    <a href="https://twitter.com/nescafearg?lang=es"><img src="imgs/Logo Twitter.png" alt="Logo de Twitter"></a>
                </figure>
            </li>

            <li class="iconos">
                <figure>
                    <a href="https://www.youtube.com/channel/UCzDUXIuodcb9f6zEjqN5okw"><img src="imgs/Logo Youtube.webp" alt="Logo de youtube"></a>
                </figure>
            </li>
        </ul>
        <p>© 2023 Nestlé</p>
    </footer>  
    
    
</body>
</html>
