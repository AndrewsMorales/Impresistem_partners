# Impresistem_partners

Este proyecto desarrollado en **Symfony** tiene como objetivo crear un sistema de solicitud para que las personas puedan convertirse en **partners** de una marca y acceder a la compra de productos importados. El sistema permite una gestión eficiente de la solicitud de partnership a través de un formulario extenso que guía al usuario a través de varios pasos, permitiendo realizar el seguimiento tanto desde el lado del **cliente** como del **administrador**.

## Características Principales

### 1. **Solicitud de Partnership**
- **Formulario Extenso:** El sistema permite a los usuarios completar un formulario detallado para solicitar convertirse en **partner** de la marca. El formulario está estructurado en múltiples pasos que facilitan la recopilación de información importante, desde los datos personales hasta los detalles comerciales.
- **Proceso de Aprobación Paso a Paso:** El formulario de solicitud se gestiona a través de un sistema de pasos, donde el **administrador** puede revisar y aprobar o rechazar la solicitud del cliente. Este proceso está diseñado para ser claro y sencillo tanto para el administrador como para el usuario.

### 2. **Gestión de Direcciones de Envío**
- **Administración de Direcciones para Partners Activos:** Los usuarios que ya han sido aprobados como **partners** tienen la opción de gestionar sus direcciones de envío para los productos que adquieren. Esto les permite agregar, editar y eliminar direcciones de envío, mejorando la experiencia del usuario y facilitando la gestión de pedidos.

### 3. **Sincronización con SAP**
- **Integración con SAP:** Todo el sistema está sincronizado con la plataforma de **SAP**, lo que garantiza que los datos de las solicitudes, direcciones de envío y otros detalles estén actualizados en tiempo real. Esto mejora la eficiencia y la precisión en la gestión de información, asegurando una integración fluida entre el sistema y la plataforma de administración empresarial.

### 4. **Interfaz de Usuario y Seguimiento en Tiempo Real**
- **Panel de Administración:** Los administradores tienen acceso a un panel donde pueden ver el progreso de cada solicitud de partnership y realizar un seguimiento detallado del estado de cada cliente.
- **Experiencia de Usuario:** El sistema está diseñado con un enfoque en la usabilidad, utilizando **Symfony** para el backend y **Twig** para las plantillas. Además, se emplea **JavaScript** y **jQuery** para crear una interfaz dinámica e interactiva que mejora la experiencia del usuario.

## Tecnologías Utilizadas

- **Symfony**: Framework PHP utilizado para el desarrollo del backend.
- **API REST**: Para la interacción entre el sistema y otras plataformas (como SAP).
- **PHP**: Lenguaje principal utilizado en el backend.
- **Twig**: Motor de plantillas para renderizar el frontend.
- **JavaScript y jQuery**: Para la creación de interfaces dinámicas e interactivas.
  
Este sistema optimiza la experiencia tanto para administradores como para clientes, garantizando un flujo de trabajo ágil y eficaz en el proceso de solicitud de partnership y gestión de direcciones.
