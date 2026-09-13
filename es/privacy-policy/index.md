---
layout: default
title: Política de privacidad
permalink: /es/privacy-policy/
lang: es
---

# Política de privacidad de Just 3 Days (v1.1)

**Entrada en vigor:** 31 de julio de 2026
**Última actualización:** 13 de septiembre de 2026

## 1. Responsable

DreamAppLab (el «Operador») gestiona Just 3 Days (el «Servicio») y trata la información de los usuarios conforme a la legislación aplicable.

- **Responsable/Operador:** DreamAppLab
- **Contacto de privacidad:** [demianjun1@gmail.com](mailto:demianjun1@gmail.com)

## 2. Información tratada y finalidades

| Categoría | Información | Finalidad |
|---|---|---|
| Objetivos y registros locales | Título, dificultad, fecha de inicio, duración, hora del aviso, registros diarios e historial de reinicios | Gestión, progreso, estadísticas, avisos y función de reinicio |
| Ajustes locales | Idioma, tema, avisos, visualización, PIN de cuatro dígitos y estado de eliminación de anuncios | Preferencias, bloqueo local y estado de compra |
| Iniciar sesión con Apple | Identificador de Apple y correo público o de retransmisión privada | Inicio de sesión, verificación y conexión de la cuenta |
| Inicio de sesión con Google | Identificador, correo, nombre y URL de imagen de perfil, cuando se faciliten | Inicio de sesión, verificación y conexión de la cuenta |
| Firebase Authentication | UID de Firebase, proveedor y estado de autenticación | Autenticación y gestión de cuenta |
| Cloud Firestore | Objetivos, registros diarios e información de reinicio sincronizados; estado y fecha de eliminación de anuncios; metadatos de cambios y borrado | Sincronización y restauración entre dispositivos |
| Compra integrada | Identificadores de producto y transacción, fecha y derecho verificado | Provisión, verificación y restauración de la eliminación de anuncios |
| Publicidad y consentimiento | Dirección IP, datos del dispositivo, SO y app, identificadores publicitarios disponibles, impresiones, interacciones, diagnóstico y consentimiento | Publicidad y medición, prevención del fraude, consentimiento y soporte |
| Firebase App Check | Token de validación e información técnica de la app y el dispositivo | Impedir accesos no autorizados al servidor |

Sin conectar una cuenta, los objetivos y registros permanecen normalmente en el dispositivo y no se sincronizan con Cloud Firestore. No recopilamos directamente números de tarjeta ni datos faciales de Face ID. iOS realiza la comprobación facial y solo comunica el resultado.

## 3. Obtención y bases jurídicas

La información se introduce o genera al crear objetivos, registrar progreso, cambiar ajustes, iniciar sesión, comprar o elegir opciones de consentimiento. La app y sus SDK pueden transmitir automáticamente datos técnicos al funcionar.

Según la legislación aplicable, tratamos datos para ejecutar el servicio solicitado y las funciones de cuenta, sincronización y compra; con consentimiento para publicidad opcional cuando sea necesario; por interés legítimo en seguridad, prevención del fraude y diagnóstico; y para cumplir obligaciones legales. Rechazar una cuenta opcional o los avisos limita la sincronización o los recordatorios, pero permite gestionar objetivos en el dispositivo.

## 4. Usos

- Ofrecer objetivos, registros, progreso, estadísticas, avisos ordinarios y un aviso de reinicio tras siete días sin actividad
- Ofrecer inicio de sesión con Apple/Google, gestión de cuenta y sincronización
- Verificar, activar y restaurar la eliminación de anuncios
- Mostrar y medir anuncios de Google AdMob y prevenir fraude
- Gestionar el consentimiento publicitario y las opciones de privacidad
- Mantener la seguridad, estabilidad y calidad y atender solicitudes

## 5. Publicidad y seguimiento

El Servicio puede usar Google Mobile Ads SDK y Google User Messaging Platform para obtener consentimiento y mostrar opciones de privacidad donde corresponda. Esta versión no solicita permiso de App Tracking Transparency ni usa IDFA para seguimiento entre apps. Según el consentimiento, la región y los ajustes, pueden mostrarse anuncios no personalizados o limitados.

## 6. Proveedores

| Proveedor | Servicios | Finalidad |
|---|---|---|
| Google LLC | Google Sign-In, Firebase Authentication | Inicio de sesión, autenticación y cuenta |
| Google LLC | Cloud Firestore | Almacenamiento y sincronización |
| Google LLC | Firebase App Check | Prevención de accesos no autorizados |
| Google LLC | Google AdMob, User Messaging Platform | Publicidad, medición, fraude y consentimiento |
| Apple Inc. | Iniciar sesión con Apple, App Store, StoreKit | Inicio de sesión, pago, verificación y restauración |

No vendemos información personal ni la usamos fuera de las finalidades indicadas salvo que la ley lo permita. Revisamos las garantías contractuales y públicas de estos proveedores para exigir una protección acorde con esta política y la legislación aplicable.

## 7. Almacenamiento y transferencias internacionales

Los datos sincronizados de Cloud Firestore se guardan en la base `just3db` de la región de Seúl de Google Cloud (`asia-northeast3`). Firebase Authentication, App Check, Google Sign-In, AdMob, User Messaging Platform, Iniciar sesión con Apple y App Store pueden tratar datos fuera del país del usuario donde operen Google o Apple, mediante conexiones cifradas.

- [Política de privacidad de Google](https://policies.google.com/privacy?hl=es)
- [Uso de información por Google en apps asociadas](https://policies.google.com/technologies/partner-sites?hl=es)
- [Política de privacidad de Apple](https://www.apple.com/legal/privacy/es/)

## 8. Conservación y eliminación

| Ubicación/información | Conservación y eliminación |
|---|---|
| Objetivos y registros locales | Hasta que el usuario elimine esos datos o los datos de la app |
| Ajustes en UserDefaults | Hasta que se eliminen el ajuste o los datos de la app |
| PIN y sesión en Keychain | Hasta desactivar la función, borrar el elemento o su eliminación por iOS; algunos elementos pueden sobrevivir a una reinstalación |
| Firebase Authentication y Cloud Firestore | Hasta eliminar la cuenta; después, sin demora indebida salvo obligación legal |
| Registros de App Store | Según las políticas de Apple y la ley |
| Información publicitaria y diagnóstica | Según las políticas de Google y la ley |

Eliminar la cuenta desde la app borra la cuenta de Firebase Authentication y los datos asociados de Cloud Firestore. Cerrar sesión no borra datos del servidor. Los objetivos y registros locales no se borran automáticamente, y Apple controla el historial de compras de App Store.

## 9. Derechos y opciones

Con arreglo a la ley aplicable, el usuario puede solicitar acceso, rectificación, supresión, limitación, oposición, portabilidad, retirada del consentimiento y el cese de comunicaciones a terceros.

- La cuenta se elimina en «Gestión de cuenta».
- Los objetivos y registros se eliminan en sus pantallas de la app.
- Los avisos se cambian en Ajustes de iOS.
- Las opciones publicitarias se cambian en «Privacidad de anuncios» cuando esté disponible.
- Otras solicitudes pueden enviarse, indicando el correo registrado y la acción solicitada, a [demianjun1@gmail.com](mailto:demianjun1@gmail.com).

Podemos verificar la identidad antes de responder. Los usuarios del EEE pueden reclamar ante su autoridad de protección de datos.

## 10. Seguridad, menores y cambios

Aplicamos TLS, Firebase Authentication, reglas de Firestore por usuario, Firebase App Check, Keychain, acceso mínimo y actualizaciones de seguridad. El Servicio no pretende crear cuentas conectadas de menores sin el consentimiento exigido de sus padres o tutores. Los cambios importantes se anunciarán antes de entrar en vigor en la app, esta página u otro medio adecuado.

## 11. Contacto

- **Operador:** DreamAppLab
- **Correo:** [demianjun1@gmail.com](mailto:demianjun1@gmail.com)
