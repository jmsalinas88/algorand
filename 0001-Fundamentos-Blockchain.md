# ¿Qué es una blockchain?

Una blockchain es un libro mayor público, archivo, o datos transaccionales, distribuido a través de multiples computadoras ("nodos") conectados en una red. Todos los nodos trabajan en conjunto, usando el mismo software y las mismas reglas, para verificar transacciones a agregar al libro mayor. 


# Bloques

La palabra "block" parte de "blockchain" son un set de transacciones que son verificados por los nodos y eventualmente agregados a la blockchain. 
Y la palabra "chain", se refiere al hecho de que cada bloque ("block") transaccional también contiene una prueba (un hash criptográfico) de las transacciones del bloque anterior. Éste patrón de capturar el bloque previo en el bloque actual se ve representado en todos los bloques hasta el origen de la cadena de bloques ("el bloque génesis") creando un registro públicamente verificable y a prueba de manipulaciones de todas las transacciones. 

![enter image description here](https://github.com/jmsalinas88/algorand/blob/main/static/bloques.png)

Prácticamente, ésto significa que si se trata de manipular incluso un simple registro, en cualquier parte de la cadena, será identificable y rechazado por los nodos de la red. 

## ¿Cómo se agregan los bloques a la cadena?

Cada nodo corre un software que contiene las instrucciones necesarias para verificar las transacciones y la forma de agregar bloques a la cadena. Éstas instrucciones son conocidas como **"protocolo de consenso"**. La naturaleza de éstas instrucciones  son uno de los factores diferenciales de las diferentes blockchains. Aprenderemos sobre el protocolo de consenso de Algorand más adelante en ésta guía y cómo difiere de las otras blockchains. 

## ¿Cómo blockchain beneficia mis aplicaciones?

Blockchain es una tecnología de innovación, en cómo transferimos valor. Entonces, si tu aplicación intercambia valor de alguna forma, blockchain podría ser una tecnología candidata para impulsar tu aplicación al siguiente nivel. 
Pero, antes de sumergirnos en blockchain, es importante entender específicamente cómo podría beneficar tu aplicación, de tal forma de diseñar un sistema que a aplicar ésos beneficios y que no agregue complejidad innecesaria a otras partes de tu aplicación. Esto usualmente se logra pensando en qué componentes poner sobre blockchain ("on-chain") versus fuera de la blockchain ("off-chain") 
A continuación, podemos encontrar algunas características de blockchain que las hace una tecnología atractiva para aplicaciones basadas en la transferencia de valores: 

 - Seguridad
 - Confianza
 - Inmutabilidad
 - Transparencia
 - Bajo costo
 - Eficiencia
 - Integrabilidad
 
 No todas éstas características podrían ser importantes en tu aplicación, posiblemente alguna de ellas podría ser más importante que otras, por lo tanto, la primera pregunta que debes hacerte es **¿Cuál de éstas son importantes para mi caso de uso?**
 
 Si elegís al menos una, entonces la siguiente pregunta sería **¿Ésta falta o es insuficiente en mi diseño actual de mi aplicación?**
 
 Si la respuesta a ésta segunda pregunta es "si", a cualquiera de las características que elegiste, entonces estás en el lugar correcto. 
 
Por ejemplo, enviando un pago internacional a través de bancos, usualmente toma días y es de alto costo, porque hay muchos intermediarios involucrados para garantizar que el valor es enviado con seguridad. Costos altos, y generalmente ineficiencia son las características que encontramos ante éste escenario, y blockchain puede mejorarlas, esto no quiere decir que el resto de las características no son importantes. Por ejemplo, no deseamos costos bajos a expensas de la seguridad, pero si sólo la seguridad importara, podríamos decir que el proceso actual es lo suficientemente bueno (asumiendo que confiamos en el banco que hace la transferencia). En éste escenario, blockchain mejora las deficiencias, sin escatimar en otro lugar. 

## La subasta de Alice y Bob

Alice es una artista talentosa, buscando ampliar su cantidad de fans y su reputación como artista.
Bob es un developer y es amigo de Alice, y la quiere ayudar. 

Alice vende sus obras de arte por medio de las personas conocidas de su entorno, de voz en voz, y a veces por medio de publicidad en redes sociales. Una de sus piezas de arte las vende a $ 100, en promedio, utilizando la técnica actual de venta. Alice cree que podría generar más ganancias si escala y llega a un público más amplio, entonces considera las características importantes para su caso de uso: 

 1. Eficiencia: Pierde mucho tiempo buscando un nuevo comprador, y últimamente no encuentra un público más amplio. 
 2. Confiancia/Transparencia: Alice quiere una audiencia más amplia, pero ella todavía está construyendo su reputación, y necesita una manera para que tanto ella como los compradores potenciales sepan que no están siendo estafados. 
 3. Costo: Le mejor opción de escalar es utilizar un e-commerce, pero sabe que deberá renunciar a una buena parte de lo que gana en comisiones. 

 Mencionamos 4 propiedades de blockchain que podría ayudar a Alice. Alice y Bob analizan junstos considerando los objetivos principales y los aspectos que ella quiere optimizar. Se les ocurre la siguiente idea: 

 Planean tokenizar el arte de Alice como un NFT en la blockchain. Esto les da un punto de entrada al ecosistema blockchain y la posibilidad de planear lo que deseen hacer a continucación. Por lo tanto, construirán una dApp para subastas en la blockchain que permitirá a Alice vender sus obras de arte a un precio fijado por el mercado. 

 La subasta será programada en la blockchain para que todas puedan verla y verificarla. Alice puede garantizar a sus compradores que no serán estafados y viceversa sin necesidad de conocerlos personalmente. Dado que eliminan la necesidad de que en tercero garantice el comercio, pueden reducir sustancialmente las tarifas y Alice puede ganar más dinero. 

 Alice puede concentrarse en publicitar su trabajo a una audiencia tan amplia como quiera a través de sus cuentas de redes sociales o en cualquier otro lugar sin necesidad de reunirse individualmente y generar confianza con compradores potenciales. 

 Ahora que sabemos los fundamentos de blockchain. Empecemos a aprender más sobre la blockchain Algorand. 