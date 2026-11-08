# Practica3-DispositivosFormatos-UnrealVR
Repositorio para guardar los archivos de la práctica 3 de la asignatura dispositivos y formatos. 

PRÁCTICA 3 - LUCÍA LÓPEZ SÁNCHEZ

TABLA DE CONTROLES

- Desplazamiento: W A S D
- Desplazarse hacia adelante/atrás --> Rueda del ratón
- Movimiento Izquierda/Derecha/rotativo --> Click derecho ratón
- Coger objeto: doble click en la rueda del ratón
- Soltar objeto: doble click en la rueda del ratón con el objeto en las manos. 
- Disparar: Click Izquierdo ratón

INDICACIONES MINIJUEGOS

- Hacer que se rompa estatua: Coger martillo con doble click en la rueda del ratón + acercar martillo hacia la estatua.

- Hacer que se mueva la piñata: coger martillo con doble click en la rueda del ratón + acercar el martillo hacia la piñata.

- Míster potado: Coger objeto con doble click en la rueda del ratón + doble click en rueda del ratón para dejar la pieza en el lugar deseado. 

- Billar: Doble click en rueda de ratón para coger palo de billar + mover palo de billar con rueda del ratón hacia adelante y hacia atrás para mover bolas. 

- Dardos: Agarrar el dardo con doble clic en rueda de ratón + acercar el dardo a la diana para sumar puntos

- Bolos: Derriban los bolos por sí solos, pero se puede agarrar con doble click en rueda de ratón + doble click en rueda de ratón 


VALORES FINALES: 

- Bola de bolos: Blueprint con componente Grab/Físicas activadas/ masa 6kg
- Bola de billar: Fisicas activadas/masa 0.2kg
- Dardo: Blueprint con componente Grab/Fisicas activadas/ masa 0,5kg
- Diana: Blueprint con Event Graph concomponente on component Hit, una función Construction Script, variables dardo y punto. / No tiene físicas activadas.
- Piñata: BluePrint con PhysicsConstraint, componente 1 un cubo simple y componente 2 la malla de la piñata/ Linear limits limited en 4.0 / Angular limits con swing 1 y swing 2 limited y trwist motion locked / Físicas activadas / masa 20kg.
- Estatua: Geometry Collection con fractura uniforme / materiales asociados / físicas activadas
- Bolos:Fisicas activadas/masa 1kg
- Palo de billar: Blueprint con componente Grab/ Físicas activadas / masa 3kg
- Martillo: Blueprint con componente grab/ Físicas activadas/ masa 4kg. 
- Piezas potato: Blueprint actor con componente Grab/ Evento OnDropped/ función Construction Script/ Variable cuerpo / tarjet y self asociado a attach actor/ Sin físicas activadas


MEJORAS IMPLEMENTADAS

- Se han cambiado los materiales de las paredes por unos importados desde FAB.
- Se ha extendido el escenario haciendo una zona más amplia y con mayor distribución de los minijuegos
- Se han añadido elementos adicionales como la piñata colgando y una mesa de billar como minijuego extra
- Como elementos de decoración, se ha añadido unas máquinas recreativas de color amarillo para que conjunten con la estatua del oso. 
- Como elemento de decoración para implementar en un futuro otro minijuego, se han añadido unas dianas a la zona de pistolas para que el usuario practique.
- Sobre la diana se ha añadido un texto a modo de sistema de puntos
- Se ha añadido unos carriles y una rampa para la zona de bolos. 
- Los cubos se han sustituido por mesas de mármol sacadas de FAB. 
 

