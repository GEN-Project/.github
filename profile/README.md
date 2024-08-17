# Bienvenido al proyecto GEN 👋 - Aplicación para Coaching

---


## 1. Resumen del Proyecto
La aplicación GEN es una plataforma diseñada para gestionar programas de coaching con una estructura de niveles y comisiones, permitiendo la inscripción de alumnos y el manejo de pagos de manera eficiente. La aplicación soportará múltiples idiomas para ofrecer contenido de video adaptado a usuarios de diferentes regiones.

![image](https://github.com/user-attachments/assets/1026ad04-58e4-4d88-8f10-d0ed72c557b8)



---

## 2. Objetivos del Proyecto

- **Parametrización de Comisiones y Montos de Inscripción:** Permitir la configuración flexible de porcentajes de comisión y montos de inscripción por parte de los administradores.
- **Estructura de 7 Niveles:** Implementar un sistema de niveles en el que los usuarios puedan invitar a otros, distribuidos en hasta 7 niveles.
- **Gestión de Usuarios por Nivel:** Permitir la inscripción de un número indefinido de usuarios en cada nivel, con restricciones para evitar la reincorporación en niveles anteriores.
- **Gestión de Pagos:** Integrar métodos de pago como PayPal y BancoGanadero QR, con la posibilidad de procesar los pagos una vez al mes.
- **Soporte Multilingüe:** Implementar un sistema que permita subir videos en diferentes idiomas para satisfacer a una audiencia global.

![image](https://github.com/user-attachments/assets/11df924a-a5ec-4123-b628-35f1c5547ebe)


---

## 3. Requerimientos Funcionales

- **Parametrización de Comisiones:**
  - Interfaz para definir el porcentaje de comisión.
  - Opción para establecer el monto de inscripción.
  
- **Gestión de Niveles:**
  - Crear un sistema jerárquico de 7 niveles.
  - Permitir la inscripción de usuarios bajo un esquema multinivel.
  - Prevenir la reincorporación de un usuario bajo una misma pirámide.

- **Manejo de Pagos:**
  - Integración con PayPal y BancoGanadero QR.
  - Configuración para que los pagos se procesen mensualmente.
  - Al inscribir a otro alumno, el sistema debe permitir el pago con créditos y almacenar el efectivo.

- **Soporte Multilingüe para Videos:**
  - Sistema para subir videos en diferentes idiomas.
  - Interfaz que permita a los usuarios seleccionar el idioma de preferencia.
  - Gestión de contenido multilingüe para garantizar una experiencia de usuario fluida.



---

## 4. Requerimientos No Funcionales

- **Escalabilidad:**
  - El sistema debe soportar el crecimiento en el número de usuarios sin afectar el rendimiento.
  
- **Seguridad:**
  - Asegurar la protección de datos financieros y personales de los usuarios.
  - Implementar medidas contra el fraude y la reincorporación indebida en la pirámide.

- **Usabilidad:**
  - Interfaz de usuario intuitiva que permita a los usuarios navegar fácilmente por las funcionalidades de la aplicación.
  
- **Soporte Multiplataforma:**
  - La aplicación debe estar disponible en plataformas web y móviles (iOS y Android).

---

![image](https://github.com/user-attachments/assets/f8c779c5-87fb-406c-b778-b4d4179e6580)


## 5. Cronograma Tentativo

- **Fase 1: Análisis y Planificación**(Primer reunion)
  - Reunión con stakeholders para definir requisitos detallados.
  - Elaboración del plan de proyecto y cronograma.

- **Fase 2: Diseño** (1 semana)
  - Diseño de la arquitectura de software.
  - Diseño de la interfaz de usuario y experiencia (UI/UX).

- **Fase 3: Desarrollo** (2 meses)
  - Desarrollo de la parametrización de comisiones y gestión de niveles.
  - Integración de sistemas de pago.
  - Implementación del soporte multilingüe.

- **Fase 4: Pruebas y Ajustes** (1 mes)
  - Pruebas unitarias, de integración y de usuario.
  - Ajustes según retroalimentación.

- **Fase 5: Implementación y Lanzamiento** (2 semanas)
  - Despliegue en servidores de producción.
  - Publicación en tiendas de aplicaciones (App Store, Google Play).
  - Monitoreo post-lanzamiento.

---

## 6. Recursos Necesarios

- **Equipo de Desarrollo:**
  - Diseñadores UI/UX.
  - Desarrolladores Front-end.
  - Desarrolladores Back-end.
  - Especialidas en Base de datos y Sql.
  - Especialista en seguridad.
  - Consultor de integraciones API

- **Herramientas de Desarrollo:**
  - React Native para aplicaciones móviles y web.
  - Backend en Java.
  - Base de datos PostgreSQL.
  - Integración con API de PayPal y BancoGanadero QR.
  - Servidores Linux con Docker

- **Infraestructura:**
  - Servidores para hosting y base de datos locales.
  - Sistema de almacenamiento seguro para videos en diferentes idiomas local.
  - Firewall para asegurar la seguridad de la información.

---

## 7. Presupuesto

### Costo de desarrollo

|Descripcion|Forma de pago|Monto|
|-|-|-|
|Diseño de interfaz UI/UX|Un solo pago|$us.800|
|Configuracion de servidores|Un solo pago|$us.1.000|
|Inicio de desarrollo|Un solo pago|$us.1.200|
|Beta 1|Un solo pago|$us.1.500|
|Pruebas 1|Un solo pago|$us.500|
|Beta 2|Un solo pago|$us.1.500|
|Pruebas 2|Un solo pago|$us.500|
|Salida a producción|Un solo pago|$us.1.000|
|**Total**||$us.8.000|

`Distribuido en 4 pagos`

|Descripcion|Forma de pago|Monto|
|-|-|-|
|Pago para iniciar el desarrollo|$us.2000|⚠️|
|Cuota 2|$us.2000|⚠️|
|Cuota 3|$us.2000|⚠️|
|Pago final|$us.2000|⚠️|

`Si se realiza el primer deposito antes del 30 de Agosto de 2024 se le realizará un descuento de $500.`

### Costo de mantenimiento

|Descripcion|Forma de pago|Monto|
|-|-|-|
|Servidores|Mensual|$us.300|
|Storage Video|Mensual|$us.300|
|Pasarela Qr|Transacción|1%|
|PayPal|Transacción|[paypal-fees](https://www.paypal.com/bo/webapps/mpp/paypal-fees)|


`El costo de mantenimiento incluye un equipo de desarrolladores para resolver problemas de bugs.`

---

## 8. Consideraciones Finales

El éxito del proyecto GEN dependerá de la correcta implementación de cada uno de los componentes planificados y de la capacidad del equipo para adaptarse a las necesidades emergentes durante el proceso de desarrollo. La satisfacción del usuario y la seguridad serán pilares fundamentales en la ejecución de este proyecto. Al mismo tiempo la puntualidad de los pagos para evitar perder el ritmo de tiempos de la entraga final.


 
