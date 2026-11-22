# Servidor dedicado barato: ¿cuánto cuesta de verdad, qué entra por 85 € al mes y cuándo te conviene seguir con un VPS? (IVA, compromiso y costes ocultos)

El servidor dedicado más barato de AvaHost cuesta **85 €/mes** y trae un AMD Ryzen 5 4650G de 6 núcleos y 12 hilos, desde 16 GB de DDR4, desde 256 GB de NVMe, puerto de 1 Gbps, una IPv4 y mitigación DDoS incluida. El catálogo sube hasta **149 €/mes** con dos Xeon E5-2699 v3 y 36 núcleos. En otras partes del mercado hay dedicados desde 4,99 €/mes con 2 núcleos, 4 GB de RAM y 120 GB de SSD: entre esos 4,99 € y los 85 € hay un factor 17, y en ese hueco caben casi todas las interpretaciones de la palabra "barato".

La factura final depende de cuatro cosas que no aparecen en el número grande de la portada: el IVA, el compromiso de permanencia, el tráfico y las IPs, y las licencias o el soporte que se facturan aparte. Aquí tienes las cuatro configuraciones de AvaHost con sus precios, qué compra cada franja del mercado en euros, pesos chilenos y rublos, los cuatro casos en los que un VPS sigue saliendo más barato que cualquier dedicado y las comprobaciones que conviene hacer antes de pagar.

> **Vistazo rápido**
> - **Sitio con tráfico moderado, staging o backend pequeño:** el plan de 85 €/mes (Ryzen 5 4650G, 6C/12T, 16 GB, 256 GB NVMe) es hardware físico completo y sobra para empezar.
> - **Lo que aprieta es el disco, no la RAM:** el plan de 99 €/mes lleva 256 GB de RAM, pero en DDR3 y sobre discos SAS de 600 GB. Si tu cuello de botella es la base de datos, los 120 €/mes con DDR4 y SSD te sirven mejor.
> - **Virtualización, render o muchos procesos en paralelo:** 149 €/mes por 36 núcleos y 72 hilos.
> - Si no cumples ninguno de los cuatro umbrales del apartado "cuándo no lo necesitas", quédate en un VPS.

👉 [Ver las configuraciones dedicadas disponibles y su precio actual](https://my.ava.hosting/aff.php?aff=15562)

## Los cuatro planes de AvaHost y qué lleva cada uno

El catálogo es corto y se entiende rápido. Todos son máquinas físicas completas, con facturación mensual en euros y sin compromiso de permanencia.

| Plan | Núcleos / RAM | Almacenamiento | Precio |  |
| --- | --- | --- | --- | --- |
| AMD Ryzen 5 4650G | 6C/12T · desde 16 GB DDR4 | desde 256 GB NVMe, hasta 4 discos adicionales | **85,00 €/mes** | [Ver plan](https://my.ava.hosting/aff.php?aff=15562) |
| 2× Intel Xeon E5-2680 v2 | 20C/40T · 256 GB DDR3 ECC | 8 × 600 GB SAS con controladora RAID | **99,00 €/mes** | [Ver plan](https://my.ava.hosting/aff.php?aff=15562) |
| 2× Intel Xeon E5-2620 v3 | 12C/24T · desde 32 GB DDR4 | desde 1 TB SSD | **120,00 €/mes** | [Ver plan](https://my.ava.hosting/aff.php?aff=15562) |
| 2× Intel Xeon E5-2699 v3 | 36C/72T · desde 32 GB DDR4 | desde 1 TB SSD | **149,00 €/mes** | [Ver plan](https://my.ava.hosting/aff.php?aff=15562) |

Lo que va incluido en los cuatro: puerto de 1 Gbps, una dirección IPv4, protección DDoS sin coste, acceso root, soporte 24/7 y complementos opcionales. Los tres planes Xeon añaden controladora RAID y gestión remota. El SLA publicado es del **99,9 %** y cubre potencia y red. El centro de datos está en Chișinău (Moldavia) y la empresa opera desde 2002.

Dos detalles de la ficha que conviene leer antes de emocionarse con el precio: el plan de 99 €/mes es el que más RAM pone sobre la mesa, pero es DDR3 y va sobre ocho discos SAS de 600 GB, tecnología de hace dos generaciones. El salto a DDR4 y SSD son 21 €/mes más. Y el almacenamiento se puede ampliar: el Ryzen admite hasta cuatro discos adicionales, un dato relevante si vas a montar un servidor de backups o de vídeo.

## El precio de portada no es la factura: cuatro cosas que cambian el total

**1. El IVA.** En el mercado español y chileno el precio que se anuncia suele ir sin impuestos: Arsys publica sus dedicados desde 64 €/mes con la coletilla "IVA no incluido", y Chilecom arranca en 100.000 pesos al mes "+ IVA". AvaHost muestra 85 €/mes en su catálogo en euros; confirma en el momento del pago si ese importe lleva IVA o se suma después, porque en una cuota de 85 € la diferencia son casi 18 € al mes.

**2. El compromiso.** Los precios bajos de verdad casi siempre esconden una firma. Scaleway vende su servidor de 6 núcleos y 32 GB a 33,99 €/mes, pero con 36 meses de compromiso; el Xeon de 4 núcleos y 32 GB sale a 37,99 €/mes con 12 meses. AvaHost factura mes a mes. Sobre el papel, tres años del plan de 33,99 € son 1.223,64 € y tres años del Ryzen de 85 € son 3.060 €, pero no es la misma máquina: 32 GB y 2 TB de NVMe frente a 16 GB y 256 GB. Si necesitas ese almacenamiento y puedes firmar tres años, el compromiso juega a tu favor; si prevés cambiar de proveedor o de país, la flexibilidad mensual vale dinero.

**3. Tráfico e IPs.** Beget incluye cuatro IPv4 y 30 TB de tráfico por servidor, con exceso a 200 rublos por TB. Scaleway presume de no cobrar egreso. AvaHost incluye una IPv4 y no publica un límite de tráfico en la ficha, así que si vas a servir vídeo o backups fuera del servidor, pregunta antes. Y si necesitas más de una IP (por ejemplo, para certificados SSL por IP o para separar servicios), pide el precio de las adicionales.

**4. Licencias y soporte.** Chilecom cobra CloudLinux aparte, 10.000 pesos chilenos al mes, y el cPanel/WHM se contrata por separado. En AvaHost los planes se entregan sin panel de control y con complementos opcionales que la ficha no detalla; si tu operativa depende de cPanel o Plesk, pide el importe antes de contratar. El soporte gestionado también se factura aparte, a 20 €/hora según la documentación de la marca.

👉 [Comprobar qué incluye cada plan antes de contratar](https://my.ava.hosting/aff.php?aff=15562)

## Qué compra cada franja de precio en el mercado

Esta tabla sirve para situar los 85 € de AvaHost, no para coronar un ganador: hay euros, rublos y pesos chilenos, con reglas de IVA distintas y compromisos de distinta duración.

| Franja | Configuración verificada | Condiciones que van con ese precio |
| --- | --- | --- |
| 4,99 €/mes | Intel C2350 (Avoton) 2C/2T a 1,7 GHz, 4 GB de RAM, 1 × 120 GB SSD, hasta 1 Gbps | Precio permanente, sin compromiso, sin cargos por tráfico de salida |
| 33,99 €/mes | AMD Ryzen 5 PRO 3600 6C/12T a 3,6 GHz, 32 GB, 2 × 1 TB NVMe | 36 meses de compromiso; SLA 99,9 %; centros en París, Ámsterdam y Varsovia |
| 37,99 €/mes | Xeon E3 1240v6 4C/8T, 32 GB, 3 × 250 GB SSD | 12 meses de compromiso |
| 64 €/mes + IVA | CPU Intel o AMD dedicada, hasta 256 GB de RAM, SSD y NVMe, hasta 1 Gbps | Pago por uso; 11 ubicaciones en 4 países; certificación Tier III; 99,98 % de disponibilidad |
| 85–149 €/mes | Ryzen 5 4650G 6C/12T hasta 2 × Xeon E5-2699 v3 36C/72T | Facturación mensual en EUR, sin compromiso, 1 IPv4, DDoS incluido, centro en Moldavia |
| 12.600 ₽/mes | Xeon E3-1275 V5 4C/8T, 32 GB DDR4, 2 × 480 GB SSD en RAID1 | 4 IPv4 y 30 TB incluidos, exceso a 200 ₽/TB, prueba de hasta 7 días |
| 100.000 CLP/mes + IVA | Core i7 a 3,4 GHz, 8/16/32 GB, 2 SSD de 250 a 500 GB | Entrega en 48–72 h, CloudLinux +10.000 CLP/mes, cPanel aparte |

Un aviso de actualidad sobre la fila de los 12.600 rublos: Beget publica en su propia web que sufrió un ataque informático en la noche del 1 al 2 de noviembre de 2026 y que está recuperando la infraestructura, con la página actualizada el 10 de noviembre. Sus precios son verificables, su disponibilidad ahora mismo no.

## Cuándo no te hace falta un servidor dedicado

Esta es la parte que ahorra más dinero de todo el artículo. El salto al hierro dedicado se justifica en cuatro situaciones concretas:

1. Tu VPS consume **más del 80 % de CPU o de memoria de forma sostenida**, no en picos puntuales.
2. Tu base de datos supera los **50 GB** y el disco compartido empieza a meter latencia impredecible.
3. Necesitas cumplir un **compliance que exige aislamiento por hardware** (PCI-DSS, ISO 27001 o una norma local equivalente); el aislamiento por software no basta.
4. Necesitas **kernel propio** o configuraciones que un hipervisor no te deja tocar.

Fuera de esos cuatro casos, un VPS sale más barato y se administra igual. Un WooCommerce con 200 productos y 3.000 visitas al día no necesita 85 €/mes de hierro: necesita un VPS con RAM suficiente y alguien que mire los logs. Cambiar a dedicado sin haber medido antes el consumo real es la forma más común de pagar el triple para resolver un problema que era de configuración.

## Ryzen, i7 o Xeon: dónde se va el dinero

La frecuencia por núcleo manda cuando la aplicación depende de un hilo: la mayoría de los sitios web, las bases de datos medianas y los CMS. Los Xeon con muchos núcleos y memoria ECC ganan en cargas paralelas, virtualización, renderizado y bases grandes. En el catálogo de AvaHost esto se traduce en una decisión bastante clara.

El Ryzen 5 4650G es el único de los cuatro pensado para frecuencia y respuesta rápida, y por eso es el plan de entrada razonable para web y aplicaciones. Los dos Xeon E5-2620 v3 y E5-2699 v3 añaden DDR4 y SSD, que es lo que vas a agradecer en cuanto la base de datos crezca. El de 99 €/mes es una trampa de lectura rápida: 256 GB de RAM impresionan, pero con DDR3 y discos SAS el rendimiento por euro en I/O queda por detrás del plan de 120 €/mes. Si tu proyecto pide memoria por encima de todo (caché, contenedores, análisis en memoria), es una compra defendible; si pide disco rápido, no.

## Dónde está el servidor y qué te exige tu normativa

AvaHost aloja en Chișinău, Moldavia. Es un dato que decide más contratos de los que parece: Moldavia no forma parte de la Unión Europea, así que si tu cliente o tu departamento legal exige residencia de datos en la UE, este dedicado barato deja de ser una opción por muy bien que esté de precio.

El resto del mercado lo resuelve con ubicaciones. Arsys ofrece 11 localizaciones en 4 países (España, Alemania, Reino Unido y Estados Unidos) con certificación Tier III, precisamente para cumplir normativas de protección de datos distintas. Scaleway mantiene sus Dedibox en París, Ámsterdam y Varsovia, con los datos dentro de la UE. Chilecom monta su propio centro en Santiago y lo justifica con la Ley 21.719 chilena. Si tu requisito es "los datos se quedan en España" o "en la UE", comprueba la ubicación antes que el precio.

## Stock, entrega y pruebas antes de pagar

Los dedicados no se crean en treinta segundos como un VPS: hay que preparar hardware, instalar el sistema y validarlo. Chilecom declara 48–72 horas desde la confirmación del pago. AvaHost indica un aprovisionamiento de hasta 24 horas, a menudo menos, y entrega la máquina con acceso root y el sistema instalado, sin administración incluida.

El stock merece un apartado propio. En el momento de revisar el catálogo, el plan Ryzen 5 4650G aparecía con 0 unidades disponibles y el de 2 × Xeon E5-2680 v2 con una sola. Son máquinas físicas: cuando se agotan, toca esperar reposición o elegir otra configuración. Comprueba la disponibilidad el mismo día que decidas.

Sobre probar antes de comprar: Beget da hasta 7 días de test y 14 días gratis si pagas seis meses; Chilecom y AvaHost no publican un periodo de prueba en sus fichas. Si vienes de un VPS y quieres validar rendimiento con tu propia carga, pregunta por las condiciones antes de firmar.

## Preguntas frecuentes

**¿Cuál es el servidor dedicado más barato que puedo contratar hoy?**
En euros, el mínimo del mercado son 4,99 €/mes por una máquina de 2 núcleos, 4 GB de RAM y 120 GB de SSD. En AvaHost el primer dedicado son 85 €/mes con 6 núcleos, 16 GB y NVMe, una configuración que ya aguanta producción ligera.

**¿Merece la pena firmar 36 meses para pagar 33,99 € en lugar de 85 €?**
Solo si necesitas 32 GB de RAM y 2 TB de NVMe y tienes claro que no vas a cambiar de proveedor ni de país en tres años. Si tu proyecto puede moverse o crecer, la facturación mensual de AvaHost compensa la diferencia.

**¿Puedo correr una tienda WooCommerce en el plan de 85 €/mes?**
Sí, con margen de sobra para el catálogo y el tráfico de una tienda mediana. Antes de pagar, mide cuánta CPU y memoria consume tu VPS actual: si no pasa del 80 %, el dedicado te da tranquilidad pero no te resuelve nada que no estuviera resuelto.

**¿Está incluido cPanel?**
No. En AvaHost los planes se entregan sin panel y los complementos se contratan aparte. Chilecom también cobra la licencia de cPanel/WHM por separado, y CloudLinux supone 10.000 pesos chilenos más al mes. Suma esa licencia al presupuesto antes de comparar precios.

**¿Puedo empezar con una IP y añadir más después?**
Los planes de AvaHost incluyen una IPv4 y admiten complementos; pide el precio de las adicionales. Beget incluye cuatro IPv4 de serie, un detalle que importa si vas a alojar varios servicios con certificados separados.

## Cómo decidir en dos minutos

- **Un sitio con tráfico moderado, un entorno de staging o un backend pequeño:** plan de 85 €/mes. Es el único del catálogo con frecuencia alta por núcleo y sobra para empezar.
- **Producción con base de datos activa y concurrencia real:** 120 €/mes por DDR4 y SSD, o 149 €/mes si vas a virtualizar o a repartir muchos procesos en paralelo.
- **Caché, contenedores o análisis que piden RAM por encima de todo:** los 99 €/mes con 256 GB tienen sentido, asumiendo los discos SAS.
- **Normativa que exige datos en la UE o en España:** AvaHost no es la opción; busca un proveedor con centro en el país que tu normativa pida.

Antes de pagar, confirma cuatro datos: si el importe de 85 € lleva IVA, cuántas IPv4 necesitas y a qué precio, qué tráfico entra y cuánto cuesta el exceso, y si el panel que usas va incluido o se factura aparte. Con esas cuatro respuestas sabrás si el precio que viste es el que vas a pagar.

👉 [Ver precios, configuraciones y disponibilidad actual de AvaHost](https://my.ava.hosting/aff.php?aff=15562)
