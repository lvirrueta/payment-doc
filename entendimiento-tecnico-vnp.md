[&larr;](readme.md)

# Entendimiento Técnico VNP (Venta de pagos no Presente)<a id="index"></a>

- [Pasarela de pagos](#pasarela)
- [Clientes pasarela de pagos](#clientes-pasarela)
- [Tipos de transacciones](#tipos-transacciones)
- [Funcionamiento VP y VNP](#funcionamiento-vp-vnp)
- [Quienes pueden cobrar con tarjeta?](#quien-tarjeta)
- [Riesgos que existen al cobrar/pagar con tarjeta](#riesgos)

## Pasarela de pagos <a id="pasarela"></a>

Una pasarela de pagos es un servicio que actua como intermediario entre un comercio y las entidades financieras para procesar pagos de manera segura.

Ejemplos de pasarela de pagos
- Paypal
- Mercadopago
- Adyen
- Stripe

Ejemplo:

Si tienes una tienda en línea y utilizas MercadoPago como método de pago, este se convierte en tu pasarela de pagos. MercadoPago se encarga de gestionar todas las transacciones y notificarte si una operación fue aprobada o rechazada.

<div style="text-align: right; font-size: 20px;">
  <a href="#index">&uarr;</a>
</div>

***

## Clientes pasarela de pagos <a id="clientes-pasarela"></a>

Existen dos tipos de clientes pasarela de pagos: 

- **Los comercios:** Son los que integran la pasarela de pagos en sistemas para aceptar pagos en linea.

- **Los consumidores finales(clientes del negocio):** Son quienes realizan las compras usando transferencia, tarjeta, o cualquier metodo de pago habilitado por la pasarela 

<div style="text-align: right; font-size: 20px;">
  <a href="#index">&uarr;</a>
</div>

***


## Tipos de transacciones<a id="tipos-transacciones"></a>

- **Venta:** Es la transaccion principal donde un cliente realiza un pago por un producto o servicio.
  - Ejemplo: Una persona compra un articulo en una tienda y paga con tarjeta.

- **Anulacion:** Es el proceso de cancelar una transaccion que aun no ha sido procesada completamente.
  - Ejemplo: Un cliente se arrepiente inmediatamente despues de realizar el pago, y el negocio lo anula antes de que el banco lo confirme. 

- **Reverso:** Es la devolucion del dinero al cliente despues que de la transaccion ya fue procesada.
  - Ejemplo: Una tienda devuelve el dinero por que le producto estaba defectuoso o no llego.

- **Contracargo:** Es una disputa iniciada por el cliente ante su banco para revertir una transaccion no valida. 
  - Ejemplo: El cliente no reconoce un cargo en su tarjeta o recibio un producto que no corresponde. 

<div style="text-align: right; font-size: 20px;">
  <a href="#index">&uarr;</a>
</div>

***

## Funcionamiento VP y VNP<a id="funcionamiento-vp-vnp"></a>

### Venta Presente (VP)
Cliente y tarjeta estan fisicamente en el punto de Venta

Ejemplo: Pagar con tarjeta en una tienda fisica, supermercado o restaurante.

- **Funcionamiento:**
  - **Lectura de tarjeta:** el cliente inserta, desliza, o acerca la tarjeta en el datafono.
  - **Validacion de PIN**.
  - **Envio de datos:** el datafono envia los datos de la transaccion.
  - **Autorizacion:** se valida si hay fondos y se emite una respuesta
  - **Finalizacion:** Si la respuesta fue exitosa, el cliente recibe el producto o servicio.

### Venta No Presente (VNP)
Cliente y tarjeta no estan fisicamente en el lugar de la transaccion.

Ejemplo: Compras en linea, suscripciones.

- **Funcionamiento:**
  - **Lectura de tarjeta:** En este caso el cliente tiene que proporcionar los datos de la tarjeta, como numero, fecha de expiracion, codigo CVV, y datos personales.
  - **Envio de datos:** La informacion se cifra y se transmite a traves de la pasarela de pagos hacia el banco emisor.
  - **Autorizacion:** se valida si hay fondos y se emite una respuesta.
  - **Finalizacion:** Si la respuesta fue exitosa, el comercio confirma la compra, y se procesa el envio o acceso al servicio.

<div style="text-align: right; font-size: 20px;">
  <a href="#index">&uarr;</a>
</div>

***

## Quienes pueden cobrar con tarjeta?<a id="quien-tarjeta"></a>
- Comercios fisicos
- Negocios en linea
- Profesionales independientes
- Pymes y microempresas
- Emprendedores y trabajadores informales
- Grandes empresas
- Instituciones educativas y de salud

<div style="text-align: right; font-size: 20px;">
  <a href="#index">&uarr;</a>
</div>

***

## Riesgos que existen al cobrar/pagar con tarjeta<a id="riesgos"></a>
Existen varios riegos al cobrar o pagar con tarjeta. Estos riegos son principalmente **fraude**, **seguridad**, y **proteccion de datos**

- **Fraude de tarjeta(Clonacion o skimming)**
  - **Descripcion:** Los atacantes pueden copiar los datos de la tarjeta a traves de dispositivos falsos(skimmers) en los datafonos de pago o cajeros automaticos.
  - **Impacto:** El dinero se puede robar de las cuentas de los usuarios
  
- **Pishing**
  - **Descripcion:** Los atacantes pueden intentar obtener informacion personal y financiera a traves de correos electronicos, mensajes o sitios web que imiten bancos, comercios o pasarelas de pago
  - **Impacto:** Los usuarios entregan los datos de sus tarjetas.

- **Exposicion de datos personales**
  - **Descripcion:** Si los sistemas de pago no estan bien protegidos, los datos de las tarjetas pueden ser robados.
  - **Impacto:** Se pueden utiliar los datos robados para usuarlos en otros fraudes.  

- **Diferencias en el tipo de cambio**
  - **Descripcion:** Las conversiones entre diferentes monedas pueden generar costos adicionales o imprecisiones si no se usan servicios de pago transparentes.
  - **Impacto:**  Los comercios o clientes pueden enfrentarse a tasas de cambio no favorables o costos ocultos.

- **Problemas con la verificación de identidad**
  - **Descripcion:** La verificación de identidad de los tarjetahabientes internacionales puede no ser tan estricta como en algunos países, lo que facilita los fraudes en comercios online.
  - **Impacto:** El comercio podría enfrentarse a devoluciones o contracargos de clientes internacionales que no hayan sido validados correctamente.

<div style="text-align: right; font-size: 20px;">
  <a href="#index">&uarr;</a>
</div>

***
