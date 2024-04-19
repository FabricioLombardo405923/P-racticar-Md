# DESCRIPCIÓN DEL TRABAJO PRÁCTICO GRUPAL DE LABORATORIO EN COMPUTACIÓN III

En este trabajo para la universidad tenemos que realizar una replica del estanciero en el lenguaje Java,para ello como primer paso se nos pidio primero realizar un diagrama de las clases que son necesarias para este proyecto. 

## LAS CLASES

Las clases que planeamos usar en este trabajo son las siguientes:

**TABLERO:** Esta es la clase principal de nuestro trabajo ya que el tablero es la pieza clave del juego ya que dependiendo de la casilla en la que caigas sucedera un evento.

**TARJETA:** La cual se te da al comprar algun tipo de vivienda del juego con el nombre y valor de la vivienda.

**PEON:** El objeto que se mueve para mostrar en que casilla se encuentra dicho jugador.

**PROPIEDAD:**  Esta clase sirve para identificar las propiedades del juego.

**JUGADOR:** Es una clase padre hecha para crear los jugadores dentro del juego. Contiene las clases: **JugadorAgresivo**, **JugadorConservador**, **JugadorConservador** y **JugadorPrincipal**. Las cuales poseen sus propios comportamientos.

## LOS ATRIBUTOS

**TABLERO:** El tablero posee como atributos todas las clases con las que se conecta de alguna forma, los dados y el numero de casillas jugables.

**TARJETA:** Posee los atributos nombre y tipo que son necesarios para diferenciar que contiene cada tarjeta.

**PEON:** Tiene los atributos color y forma principales diferenciadores de cada peon en juego.

**PROPIEDAD:** Este tiene el nombre y las posibles mejoras para dicha propiedad.

**JUGADOR:** Los jugadores poseen billetes, Posicion, Propiedades a cargo y Nombre. Estos atributos son heredados a sus clases hijas.

## LOS METODOS

**TABLERO:** Posee los siguientes metodos: tirar dados, modo de juego y tambien el metodo repartir billetes.

**TARJETA:** Esta posee un metodo para crear tarjetas llamado generadortarjeta.

**PEON:** Posee el metodo activo y el metodo mover peon.

**JUGADOR:** Esta clase posee los metodos necesarios para que el jugados pueda interactuar. Por ejemplo: adquirir propiedades, adquirir billetes, encarcelado y etc. Además cada subclase le añade sus metodos en forma de su comportamiente expetuando por la clase jugador principal que fue creada visualizandola como la clase que un jugador que no se la maquina la utilize.
