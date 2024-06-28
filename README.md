# Prueba Webmaster - Luis Hernandez
## Sección 1: Evaluación de UX/UI
### Identificación de Problemas:
1. Hay una mala distribución de los elementos del hero.
2. En la versión móvil los espacios entre letras del titulo principal son muy cortos impidiendo la buena lectura del mismo.
   
   ![Problema 6](https://github.com/lahr0809/emprendehoy/blob/main/assets/Problem3.png)
   
3. El texto principal del hero no debería ser “MASTER CLASS GRATIS”, se puede reemplazar por algo más objetivo.
4. En la versión móvil la imagen principal del hero sobrepone el texto “JUAN DIEGO CEPEDA”.
   
   ![Problema 6](https://github.com/lahr0809/emprendehoy/blob/main/assets/Problem41.png)
   
5. Color rojo en los botones.
6. No se logra observar en su totalidad el botón “GESTIONAR COOKIES”.

   
![Problema 6](https://github.com/lahr0809/emprendehoy/blob/main/assets/Problem5.png)

---------------
Otros problemas encontrados
 - No existe una etiqueta H1 (Importante para la estructuración y SEO)
 - No se estan usando imagenes de actual generación como Webp. (Ayuda al performance del sitio)
 - LCP es de 2.9 segundos no deberia pasar los 1.2 segundos (Tiempo de carga del elemento más grande)

### Solución de Problemas:
1. Al abrir la landing page el foco principal debe ser el titulo objetivo por lo tanto se propone una redistribución de los elementos del Hero.
   
 ![Problema 6](https://github.com/lahr0809/emprendehoy/blob/main/assets/Hero-Propuesta.png)
 
2. La lectura de los textos debe ser clara por tal razón se debe aumentar el espaciado entre letras del titulo.
   
 ![Problema 6](https://github.com/lahr0809/emprendehoy/blob/main/assets/Problem31.png)

   `letter-spacing: 1.1px;`
   
3. Se propone un titulo principal más objetivo con la naturaleza del negocio, enfocado en los 5 segundos para captar la atención del usuario una ves visite la landing.
   
   **Aprende a Conseguir Capital a 0% de Interés para Crecer tus Negocios en Estados Unidos**

4. Se debe asegurar la visivilidad de todos los elementos en las diferentes versiones responsivas de la landing, en este caso la imagen principal del Hero se sobrepone al texto, se ajustaria a unos 70px de margen superior para solucionar el problema.
   
 ![Problema 6](https://github.com/lahr0809/emprendehoy/blob/main/assets/Problem42.png)
 
5. No usar color rojo en los botones, el rojo a menudo se asocia con advertencias, peligro o errores. Esto puede crear una sensación de urgencia negativa o desalentar a los usuarios de hacer clic.
El color naranja atrae la atención sin la connotación negativa del rojo, y es energizante.

 ![Problema 6](https://github.com/lahr0809/emprendehoy/blob/main/assets/Problem61.png)
                       
6. El elemento de política de cookies no se visualiza en su totalidad, este debería mostrarse como una ventana emergente automaticamente o cambiarlo de hubicación.

![Problema 6](https://github.com/lahr0809/emprendehoy/blob/main/assets/Problem51.png)
   
## Sección 2: Creación de Landing Pages
### Landing page promocional Emprende Hoy
Landing page creada con el CMS Wordpress e implementando el builder Oxygen. Se siguieron las instrucciones creado secciones de presentación, formulario, testimonios y llamado a la acción.

Url: [Emprende Hoy](https://emprendehoy.42web.io "Emprende hoy")

### A/B Testing:

**Tipo de test:** test A/B

**Variables:** original (con color naranja(#ff5f00)), variante 1 color de botón rojo(#ff4141) y CTA sin texto).

**Duración del test:** 30 días

**Herramienta:** VWO

**Objetivo principal:** aumento de leads

**Objetivo secundario:** Conocer a aceptación de color de boton y estructura de CTA

La efectividad de cada versión de test se medirá por la tasa de conversión según la interacción de los usuarios sobre el CTA durante 30 días.

#### Evidencias
![ABtest](https://github.com/lahr0809/emprendehoy/blob/main/assets/ABtest1.png)

![ABtest](https://github.com/lahr0809/emprendehoy/blob/main/assets/ABtest2.png)

![ABtest](https://github.com/lahr0809/emprendehoy/blob/main/assets/ABtest3.png)

### Sección 3: Caso de Implementación de Procesador de Pagos

**Procesadores de pago**

**Adyen**

**Descripción:** Adyen es una plataforma global de pagos que ofrece una solución unificada para aceptar pagos en línea, en aplicaciones móviles y en tiendas físicas. Es conocida por su tecnología avanzada y su capacidad de adaptación a diferentes mercados.

**Características Destacadas:**

-Soporte para múltiples métodos de pago globales y locales.

-Herramientas avanzadas de análisis y reportes.

-Protección contra fraudes con inteligencia artificial.

-Integración fluida con plataformas de comercio electrónico y aplicaciones móviles.

**Square**

**Descripción:** Square es conocida por su simplicidad y por ofrecer soluciones completas para pequeñas y medianas empresas, incluyendo procesamiento de pagos, puntos de venta (POS) y herramientas de facturación.

**Características Destacadas:**

-Procesamiento de pagos en línea y en persona.

-Integración con hardware POS.

-Herramientas de facturación y gestión de inventario.

-Tarifas competitivas y sin tarifas ocultas.

**WorldPay**

**Descripción:** WorldPay permite a las empresas aceptar una variedad de métodos de pago, incluyendo tarjetas de crédito y débito, transferencias bancarias, y pagos electrónicos. Con un enfoque en la seguridad y la innovación, WorldPay proporciona soluciones de pago robustas tanto para tiendas físicas como para comercios electrónicos.

**Características Destacadas:**

-Soporte Global de Pagos

-La plataforma ofrece robustas medidas de seguridad para proteger las transacciones y los datos de los clientes.

-WorldPay proporciona diversas opciones de integración, incluyendo APIs, SDKs y plugins para plataformas de comercio electrónico populares como Shopify, WooCommerce, y Magento.

-La plataforma ofrece herramientas de informes y análisis que permiten a los comerciantes obtener una visión detallada de sus transacciones y rendimiento de ventas.

### Selección e implementación de procesador de pagos

Se adjunta documento con lo solicitado en esta sección.

Url: [Documento Procesador de Pagos](https://github.com/lahr0809/emprendehoy/blob/main/assets/Procesador-de-pagos.pdf "Procesador de Pagos")
