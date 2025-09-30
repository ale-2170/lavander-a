# lavander-a
Sistema de Gestión de Lavandería 

Este trabajo presenta el desarrollo de un Sistema de Gestión de Lavandería como proyecto final para optar por el título de Técnico en Desarrollo de Software. El sistema permite administrar de manera eficiente las operaciones de una lavandería, incluyendo el manejo de clientes, inventario, órdenes de servicio, generación de reportes y notificaciones automáticas. La solución se desarrolló en Python utilizando el framework Flask y la base de datos SQLite.

Objetivos Específicos
•	Analizar los procesos de negocio de una lavandería típica.
•	Diseñar la arquitectura de software basada en el framework Flask y la base de datos SQLite.
•	Implementar las funcionalidades de autenticación, gestión de clientes, inventario y órdenes.
•	Incorporar herramientas de generación de reportes y exportación de datos.
•	Integrar servicios externos para notificaciones y generación de documentos PDF.

Metodología
Se utilizó la metodología ágil Scrum para el desarrollo del proyecto, organizando el trabajo en iteraciones que permitieron integrar y probar funcionalidades de manera incremental. El análisis de requerimientos se realizó a través de entrevistas y observación de procesos en una lavandería local.

Arquitectura del Sistema
El sistema se compone de una aplicación web desarrollada en Python con Flask, una base de datos SQLite y módulos opcionales para generación de PDF (ReportLab), exportación a Excel (OpenPyXL) y notificaciones mediante Twilio. La arquitectura sigue el patrón MVC (Modelo-Vista-Controlador), separando la lógica de negocio de las interfaces de usuario y la capa de datos.

Desarrollo e Implementación
Se implementaron módulos para la gestión de clientes, inventario, lista de precios, órdenes de servicio, reportes y notificaciones. La interfaz de usuario se construyó utilizando plantillas HTML y CSS, con formularios que permiten la interacción con el sistema de forma intuitiva. Se incluyó un sistema de roles para diferenciar las funciones de administrador y usuario estándar.

Resultados
El sistema desarrollado cumple con los objetivos planteados, permitiendo la administración integral de una lavandería. Se logró reducir el tiempo de registro de órdenes, mejorar el control de inventario y proporcionar herramientas para la toma de decisiones mediante reportes de ventas y estadísticas.
