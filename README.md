# Kluby Backend - API para Conectar Comunidades de Clubes

Este es el backend de **Kluby**, una plataforma diseñada para conectar comunidades de clubes como motociclistas, patinadores, ciclistas, automovilistas, entre otros. El backend proporciona una API RESTful para gestionar usuarios, clubes, eventos, chats, y la sección de e-commerce. También maneja la autenticación, pagos y geolocalización.

## Funcionalidades Principales

- **Autenticación de Usuarios**: Utiliza JWT (JSON Web Tokens) para proteger las rutas de la API y manejar la autenticación de usuarios.
- **Gestión de Clubes y Eventos**: CRUD (Crear, Leer, Actualizar, Eliminar) de clubes y eventos, con soporte para ubicaciones geográficas.
- **Geolocalización y Mapas**: Integración con la API de Google Maps para gestionar y visualizar las ubicaciones de los eventos.
- **Chat en Tiempo Real**: Soporte para WebSockets o tecnologías de tiempo real para la mensajería instantánea entre miembros de clubes.
- **E-commerce**: Implementación de una sección de productos para venta, con integración de pasarelas de pago como Stripe.
- **Notificaciones**: Envío de notificaciones push a través de Firebase Cloud Messaging (FCM).
- **Gestión de Comentarios y Advertencias**: Los usuarios pueden agregar comentarios y alertas sobre los eventos y ubicaciones.

## Tecnologías Utilizadas

- **Node.js**: Plataforma utilizada para construir el servidor backend.
- **Express.js**: Framework utilizado para crear la API RESTful.
- **MongoDB**: Base de datos NoSQL para gestionar la persistencia de datos.
- **Firebase Cloud Messaging (FCM)**: Para enviar notificaciones push.
- **Google Maps API**: Para manejar la geolocalización y visualización de ubicaciones.
- **Stripe API**: Para procesar pagos en la sección de e-commerce.
- **Socket.io**: Para implementar la funcionalidad de chat en tiempo real.

## Requisitos

- Node.js (>= 14.x)
- MongoDB
- Firebase Account para FCM (opcional para notificaciones push)
- Google Maps API Key para geolocalización
- Stripe Account para gestionar pagos

## Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tuusuario/kluby-backend.git
   ```
