
## Film funding (Premiere)

### Mecanica de sitio

El productor del film crea un teaser, fija una cantidad que le seria suficiente para producir la película, establece un plan del proyecto con roadmap, un plan de liberación de los recursos y un resumen del guión. Los usuarios del portal pueden ver los teasers y calificarlos, si ellos les gustara un teaser y quisieran colaborar a la realización del film, pueden comprar el film por anticipado (Esquema premier). Si el monto de lo comprado supera el costo de la producción, los fondos se comienzan a liberan para la realización del film. 

Los activos se liberarán de acuerdo al plan de liberación de los recursos que se elabora al crear el proyecto. La plataforma aceptará Fiat y ETH. Usando Fiat se descontarán los impuestos que apliquen. Usando Eth se utilizará un smart contract para hacer la transferencia a la cuenta del productor.

En cada milestone, el productor tendrá que documentar y subir a la plataforma el avance de la película (disponible solo para los stakeholders *1). La plataforma avisará a los stakeholders del avance.

** Los stakeholders antes de la premier son los compradores y los prestamistas.

El máximo monto para liberación de fondos será del 50% (prorrateado de acuerdo al plan de liberación de recursos). El restante 50% será liberado después de la premier. Esto creará 2 condiciones: La primera será que el productor tenderá a exagerar el presupuesto para poder financiarse por completo sin tener necesidad del 50% que se libera después de la premier (encareciendo el precio del boleto premier); La segunda será que el productor tendrá que buscar financiamiento alternativo.

Después de cada milestone, los compradores tendrán opción para convocar a votación a cancelar el proyecto. Si existe consenso con respecto a cancelar el proyecto, los fondos que posea el smartcontract al momento de la cancelación serán distribuidos entre los compradores (esta opción solo estará disponible si el productor no solicitó un préstamo).

### Información necesaria para iniciar el Film funding:

1. Elaboración del proyecto (plan de proyecto, roadmap, plan de liberación de recursos, resumen del guión.
2. Subir teaser.

### Esquema de Comercialización:

- **Premier**. Contiene toda la documentación del film, tiene la capacidad de involucrarse mas durante el desarrollo del film (tener contacto con los actores, productores y staff) y puede transferir sus derechos.

- **Cinema**. Puede reproducir el film en teatros con el permiso del productor.

- **Home**. Puede reproducir la película en cualquiera de sus dispositivos compatibles. Puede transferir sus derechos.

- **Ticket**. Tiene el derecho de reproducir una sola vez el film.

** Cinema, Home y Ticket solo estarán disponibles hasta después de la premier. Un smart contract.

** El boleto de Cinema tiene una vigencia en la cual el productor sede los derechos de proyección al cine durante ese periodo.

### Premium

Un premium de esto sería ofrecer una alternativa para financiamiento complementario con interés. Los productores podrán solicitar hasta un 50% del presupuesto de la película (en cualquier momento del roadmap). Los prestamistas (minimo 3) podrán prestar Eth a los productores bajo un acuerdo de pago de intereses.  El productor tendrá que pagar mes a mes el interes fijado a los prestamistas más el porcentaje por el uso de la plataforma de prestamo, de no ser así los prestamistas podrán cancelar (previo consenso) el proyecto y se les devolvería el total de recursos restantes a todos los stakeholders ( >50% asegurado para los compradores y para los prestamistas sería menos pero ellos mismos tendrán que supervisar el proyecto para asegurar el avance y su pago con los fondos destinados a la premier).

### Ventajas de este esquema

El productor podrá fondear su film. Obtendrá todos los recursos y solo tendrá que pagar de su bolsa los intereses a los prestamistas (de aplicar esto).
Compradores iniciales podrán seguir el desarrollo del fim y a su vez adquirir un articulo digital coleccionable.
Prestamistas podrán adquirir deuda a bajo riesgo y tazas de interés superiores a los instrumentos convencionales de inversión.

### Despues de la premier

Después del fundraise del film, los derechos de reproducción serán adquiridos con fiat o film-coin. Inicialmente los usuarios quedrán pagar con film-coin porque esa opción seria mas económico (con respecto al fiat, debido al precio inicial del film-coin)  pero con el tiempo al incrementar la demanda y haberla listado en varios exchanges, la paridad file-coin / eth tendría que apreciarse del lado de film-coin (por oferta y demanda).

Cuando el usuario adquiera la película con fiat, esos fondos serán transferidos al productor menos los impuestos a pagar. Cuando el usuario adquiera la película con la opción de film-coin se hará una transferencia de la cartera del usuario a la cartera del productor (esto menos 5% que se utilizarán para pagar fees a los mineros).

El productor tendrá que solventar los fees de las reproducciones de Premier, Cinema y Home. El total de ganancia se obtendrá con la diferencia entre lo recaudado menos lo reproducido. En caso de que esta diferencia sea positiva, se restará lo reproducido a lo recaudado y esta diferencia será la ganancia del productor por bloque.

## Minería

La moneda del sitio será film-coin. Se minará con espacio en disco duro y ancho de banda prestados. Las películas se almacenarán de manera encriptada y particionada en los discos duros de los mineros (posiblemente usando IPFS). El software de minería pagará con la moneda de film-grid cada vez que exista una petición y transacción de reproducción de ‘activo’ contenido en la maquina del minero.

Los mineros no podrán escoger que activos hostear. Existirá una capa paralela al blockchain con el indice de:

| film | particiones | mineros hosteando |
| ---- | ----------- | ----------------- |
| xxxx | xxxxxxxxxxx | xxxxxxxxxxxxxxxxx |

Los mineros recibirán recompensa tipo coinbase y fees. Las recompensas tipo coinbase serán dadas por la plataforma, los fees serán otorgados en base al streaming de activos en los que participen.

El cliente de mineria deberá estar embebido en la aplicación de reproducción, así los usuarios podrán optar por prestar su ancho de banda y disco duro para hostear los archivos de los films y obtener film-coins. Estos mismos film-coins podrán ser utilizados para ver peliculas o incluso cambiarlos en algun exchange por fiat o alguna otra crypto-moneda.

1 film-coin permitirá una reproducción (o ticket).

## Marketing

> Gana dinero viendo tus peliculas favoritas

