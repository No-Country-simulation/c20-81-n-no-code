# Planificación del MVP para "Brave Coffee"

## Objetivo
Establecer una hoja de ruta clara para el desarrollo del MVP de la aplicación "Brave Coffee", asegurando que cada miembro del equipo comprenda su papel y las metas a alcanzar.

## 1. User Stories

- **User Story 1: Visualización de Menú**
  - **Como** cliente, **quiero** ver una lista de cafés disponibles **para** elegir el que más me guste.

- **User Story 2: Personalización del Pedido**
  - **Como** cliente, **quiero** personalizar mi café **para** adaptarlo a mis gustos personales.

- **User Story 3: Selección de Mesa**
  - **Como** cliente, **quiero** seleccionar la mesa en la que estoy sentado **para que** el mesero pueda encontrarme fácilmente.

- **User Story 4: Confirmación del Pedido**
  - **Como** cliente, **quiero** recibir una confirmación detallada de mi pedido **para** asegurarme de que todo esté correcto antes de pagar.

- **User Story 5: Acceso vía QR Code**
  - **Como** cliente, **quiero** acceder a la aplicación rápidamente escaneando un QR **para** ver y hacer pedidos de manera eficiente.

## 2. Features (Funcionalidades)

- **Página de Inicio:**
  - Breve descripción de la cafetería y bienvenida.
  - Acceso directo al menú de cafés.

- **Menú de Cafés:**
  - Visualización de opciones de café de diferentes países.
  - Filtrado por categoría (nacionales, internacionales).

- **Personalización del Pedido:**
  - Opciones para agregar o quitar leche y alcohol.
  - Selección de cantidad.

- **Selección de Mesa:**
  - Funcionalidad para que el usuario indique su ubicación en la cafetería.

- **Confirmación del Pedido:**
  - Resumen detallado del pedido.
  - Información sobre el importe total y el mesero asignado.

- **Integración QR Code:**
  - Acceso a la aplicación mediante escaneo de un código QR.

## 3. Roles del Equipo

- **Product Owner:**
  - Define la visión del producto, prioriza el backlog y asegura que el equipo esté alineado con los objetivos del proyecto.

- **Scrum Master:**
  - Facilita la comunicación y las reuniones, elimina impedimentos y guía al equipo en la adopción de prácticas ágiles.

- **Desarrolladores No Code:**
  - **Diseñador de Flujos:** Diseña y configura los flujos de trabajo y las automatizaciones dentro de la plataforma No Code.
  - **Constructor de Interfaces:** Crea las interfaces de usuario usando herramientas No Code como Bubble, Glide o Adalo.
  - **Especialista en Integraciones:** Configura las integraciones necesarias, como la generación de QR codes, pasarelas de pago y servicios de backend.

- **Diseñador UX/UI:**
  - Crea wireframes, diseña la interfaz de usuario y asegura una experiencia de usuario intuitiva.

- **Tester/QA:**
  - Realiza pruebas funcionales, reporta bugs y asegura la calidad del producto antes del lanzamiento.

## 4. Tipo de Usuarios

- **Cliente:**
  - **Descripción:** Usuario final que accede a la aplicación para seleccionar y personalizar su pedido de café.
  - **Acciones Principales:** Escanear el QR, visualizar el menú, personalizar su pedido, seleccionar la mesa, confirmar el pedido.

- **Mesero:**
  - **Descripción:** Usuario que recibe los pedidos realizados por los clientes y se encarga de entregarlos en la mesa correspondiente.
  - **Acciones Principales:** Revisar el pedido asignado, confirmar la entrega.

- **Administrador:**
  - **Descripción:** Usuario encargado de gestionar los menús, opciones de personalización, y revisar estadísticas de pedidos.
  - **Acciones Principales:** Actualizar el menú, gestionar mesas, generar informes de ventas.

## 5. Stack Tecnológico

- **Frontend:**
  - FlutterFlow.

- **Backend:**
  - Plataforma No Code: Supabase.

- **Base de Datos:**
  - Integrada en la plataforma No Code: Supabase para almacenamiento y autenticación.

- **Generación de QR Codes:**
  - API de generación de QR Codes para el acceso a la aplicación.

- **Gestión de Proyectos:**
  - Trello para la organización y seguimiento de tareas.

## 6. Metodología

- **Ágil (Scrum):**
  - **Sprints:** Planificación de sprints semanales con objetivos claros.
  - **Reuniones Diarias:** Sincronización diaria del equipo para revisar el progreso y abordar bloqueos.
  - **Revisión de Sprint:** Evaluación del sprint al final de cada ciclo para ajustar prioridades y backlog.
  - **Retrospectiva:** Reflexión sobre lo que funcionó y lo que puede mejorarse en futuros sprints.
