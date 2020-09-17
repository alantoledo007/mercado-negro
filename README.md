# Mercado Negro #

_ Mercado Negro está insiparo por Mercado Libre. Permite a los usuario crear tiendas para publicar artículos y venderlos, y también les permite realizar comprar _

## Tecnologías utilizadas"

- PHP (Laravel 7 Framework).
- Javascript (jQuery, Ajax).
- MySQL
- CSS (Bootstrap 4)
- Google Analitics.
- Google AdSense.

## Features
- Autenticación de usuarios (Registro, Login, Logout, Restablecer contraseña, Verificar correo electrónico).
- Cuenta del usuario (Modificar: corre electrónico, clave de acceso y datos personales).
- Ventas: A la hora de publicar artículos, el sistema consulta las categorías de Mercado Libre y realiza una "predicción"
  para seleccionar la categoría automáticamente. Además, se realiza una búsqueda en Google para recomendarle fotos al usuario
- Mercado Pago: Se integra Mercado Pago Merketplace, Para que cada vendedor reciba el dinero en su propia cuenta.
- Tiendas: Permite a los usuario abrir una o multiples tiendas en las que podrá cargar artículos.
- Motor de búsqueda de texto completo avanzado: El motor de búsqueda de Mercado Negro detecta todas las posibles fallas que pueda realizar el usuario y/o
  remueve o agrega términos para mejorar los resultados. Esto incluye plurarización y singularización de palabras y la exclución de preposiciones. Además, se generan internamente
  posibles combinaciones que pueden corregir errores de tipeo ocacionados por el usuario. Obviamente, SIEMPRE se prioriza el texto escrito tipeado.
- Los artículos y tiendas se almacenan en la cache del servidor para mejorar la velocidad de respuesta.
- En la homepage aparecen productos y tiendas aleatorias por un tiempo definido, pasado dicho tiempo, se refresca y se muestran otras tiendas y artículos.
- Contiene Google AdSense para monetizar el sitio web.
- Se pueden realizar preguntas. 
- Notificaciones en tiempo real ("Vendiste...","Te preguntaron...","Te respondieron...", etc). Su difución es através de la plataforma mísma (real time) y por email.
- Cancelaciones y devoluciones: Tanto el vendedor como comprador pueden cancelar la compra. Siempre y cuando Mercado Pago lo permita.
- IPN Mercado Pago. Mercado Negro siempre esta comunicado con Mercado Pago, sabe sobre los reclamos, cancelaciones, transacciones que ocurran externamente y
  (por supuesto) estén realcionadas con las operaciones del usuario.
- Se utilizan las Polices de Laravel para autorizar a los usuarios con la incorporación del paquete laravel-permissions.
