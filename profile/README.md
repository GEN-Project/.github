# Bienvenido al proyecto GEN 👋 - Aplicación para Coaching

---

## 1. Resumen del Proyecto
La aplicación GEN es una plataforma diseñada para gestionar programas de coaching con una estructura de niveles y comisiones, permitiendo la inscripción de alumnos y el manejo de pagos de manera eficiente. La aplicación soportará múltiples idiomas para ofrecer contenido de video adaptado a usuarios de diferentes regiones.



---

## 2. Objetivos del Proyecto

- **Parametrización de Comisiones y Montos de Inscripción:** Permitir la configuración flexible de porcentajes de comisión y montos de inscripción por parte de los administradores.
- **Estructura de 7 Niveles:** Implementar un sistema de niveles en el que los usuarios puedan invitar a otros, distribuidos en hasta 7 niveles.
- **Gestión de Usuarios por Nivel:** Permitir la inscripción de un número indefinido de usuarios en cada nivel, con restricciones para evitar la reincorporación en niveles anteriores.
- **Gestión de Pagos:** Integrar métodos de pago como PayPal y BancoGanadero QR, con la posibilidad de procesar los pagos una vez al mes.
- **Soporte Multilingüe:** Implementar un sistema que permita subir videos en diferentes idiomas para satisfacer a una audiencia global.

![image](https://github.com/user-attachments/assets/16e5a73e-8d12-40d3-aca6-95b5e29e2fc1)

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

## 5. Cronograma Tentativo

- **Fase 1: Análisis y Planificación** (2 semanas)
  - Reunión con stakeholders para definir requisitos detallados.
  - Elaboración del plan de proyecto y cronograma.

- **Fase 2: Diseño** (3 semanas)
  - Diseño de la arquitectura de software.
  - Diseño de la interfaz de usuario y experiencia (UI/UX).

- **Fase 3: Desarrollo** (8 semanas)
  - Desarrollo de la parametrización de comisiones y gestión de niveles.
  - Integración de sistemas de pago.
  - Implementación del soporte multilingüe.

- **Fase 4: Pruebas y Ajustes** (4 semanas)
  - Pruebas unitarias, de integración y de usuario.
  - Ajustes según retroalimentación.

- **Fase 5: Implementación y Lanzamiento** (2 semanas)
  - Despliegue en servidores de producción.
  - Publicación en tiendas de aplicaciones (App Store, Google Play).
  - Monitoreo post-lanzamiento.

---

## 6. Recursos Necesarios

- **Equipo de Desarrollo:**
  - Desarrolladores Full-Stack.
  - Diseñadores UI/UX.
  - Especialista en seguridad.

- **Herramientas de Desarrollo:**
  - Frameworks como React Native para aplicaciones móviles.
  - Backend en Node.js con base de datos MongoDB o PostgreSQL.
  - Integración con API de PayPal y BancoGanadero QR.

- **Infraestructura:**
  - Servidores para hosting y base de datos.
  - Sistema de almacenamiento seguro para videos en diferentes idiomas.

---

## 7. Presupuesto

El presupuesto estimado incluirá los costos de desarrollo, diseño, pruebas, infraestructura, y posibles costos de licencias y comisiones de plataformas de pago. Un análisis detallado se realizará durante la fase de planificación.

---

## 8. Consideraciones Finales

El éxito del proyecto GEN dependerá de la correcta implementación de cada uno de los componentes planificados y de la capacidad del equipo para adaptarse a las necesidades emergentes durante el proceso de desarrollo. La satisfacción del usuario y la seguridad serán pilares fundamentales en la ejecución de este proyecto.
