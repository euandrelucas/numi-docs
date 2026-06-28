# Política de Privacidad — Numi

**Última actualización:** 28 de junio de 2026

Esta política explica qué datos recopila el bot **Numi**, para qué se utilizan y cómo puedes eliminarlos.

## 1. Qué datos recopilamos

| Datos                                                                        | Para qué se utilizan                                                                    | Cuándo                                                                           |
| ---------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- |
| Tu ID de Discord                                                             | Identificar tu cuenta y tu Numi                                                         | Al mencionar al bot o usar cualquier comando                                     |
| Idioma (locale)                                                              | Responder en el idioma correcto                                                         | Detectado automáticamente o seleccionado en Configuración                        |
| Datos de tu Numi (nombre, nivel, EXP, estado, objetos, monedas)              | Funcionamiento del juego                                                                | Cada vez que realizas una acción (alimentarlo, bañarlo, jugar, etc.)             |
| Preferencias de notificaciones                                               | Saber si podemos enviarte mensajes directos (DM)                                        | Configuración del bot                                                            |
| CPF/CNPJ                                                                     | Requerido por el proveedor de pagos para emitir la factura, solo si realizas una compra | En el momento de una compra o suscripción                                        |
| Historial de pagos (sin datos de la tarjeta)                                 | Otorgar los beneficios adquiridos y gestionar reembolsos                                | En el momento de una compra o suscripción                                        |
| Eventos de uso anónimos (por ejemplo: "comando ejecutado", "Numi eclosionó") | Comprender qué funciones se utilizan y mejorar el bot                                   | De forma continua, mediante Mixpanel, sin recopilar el contenido de los mensajes |

No leemos ni almacenamos el contenido de los mensajes del servidor. Solo procesamos la mención `@Numi`, que abre el bot, y las interacciones con comandos y botones que tú mismo realizas.

## 2. Dónde se almacenan los datos

* **Datos del juego** (Numi, monedas y objetos): almacenados en nuestra propia base de datos (PostgreSQL), alojada por el desarrollador.
* **Pagos:** procesados por Asaas (un proveedor de pagos de terceros). Los datos procesados por Asaas están sujetos a su propia política de privacidad.
* **Eventos de uso:** Mixpanel (si la recopilación de datos está habilitada).

## 3. Con quién compartimos los datos

No vendemos ni compartimos tus datos con terceros con fines de marketing. Solo compartimos la información mínima necesaria con:

* **Asaas**, para el procesamiento de pagos, únicamente si realizas una compra.
* **Mixpanel**, para análisis de uso agregados, sin datos de pago ni CPF.

## 4. Cómo eliminar tus datos

En **Configuración → Eliminar cuenta**, dentro del propio bot, puedes eliminar permanentemente tu cuenta, tu Numi y todo el progreso asociado. La eliminación es inmediata en nuestra base de datos principal.

Por motivos de auditoría relacionados con fraude y contracargos de pagos (chargebacks), conservamos una copia de seguridad temporal de los datos eliminados durante un período limitado. Si también deseas eliminar esta copia de seguridad, ponte en contacto con el desarrollador a través del servidor de soporte de Numi.

## 5. Tus derechos

En cualquier momento puedes:

* Consultar tus datos actuales con `/numi status`.
* Cambiar tu idioma y tus preferencias de notificaciones en **Configuración**.
* Eliminar tu cuenta y tus datos (consulta la sección 4).

## 6. Contacto

Si tienes preguntas sobre privacidad o solicitudes relacionadas con tus datos, ponte en contacto con nosotros a través del servidor de soporte de Numi o mediante un mensaje directo al desarrollador en Discord.

Consulta también nuestros [Términos de Servicio](./terms-of-service-es.md).
