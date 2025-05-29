# Videojuegos App - API de Gestión y Recomendación de Juegos

---

## Descripción

Videojuegos App es una API pensada para gestionar tu colección personal de videojuegos y ayudarte a controlar tu progreso en ellos. Además, ofrece recomendaciones personalizadas basadas en tus hábitos de juego y preferencias.

La API aprovecha datos públicos de Wikipedia para obtener información actualizada sobre los juegos, incluyendo sus plataformas disponibles y géneros asociados.

---

## Objetivos

- **Gestionar juegos personales:** Permite añadir, editar y listar tus videojuegos favoritos, con detalles como plataforma, fechas de inicio y fin, y estado de progreso.
- **Recomendaciones inteligentes:** Sugiere juegos nuevos basados en el género que más juegas, evitando recomendar juegos ya añadidos.
- **Datos enriquecidos:** Consulta datos fiables y actualizados desde Wikipedia para complementar la información de los juegos.
- **Interfaz sencilla:** Diseñada para integrarse fácilmente con aplicaciones web o móviles, ofreciendo endpoints claros y estructurados.

---

## Funcionalidades principales

- Listar los 100 juegos más vendidos según Wikipedia.
- Obtener las plataformas disponibles para cada juego.
- Consultar los géneros de cada juego.
- Añadir juegos a la colección personal con fechas y estado de progreso.
- Editar la información de los juegos añadidos.
- Obtener recomendaciones personalizadas de juegos basadas en el género predominante.

---

## Tecnologías

- Python 3
- Flask (para la API y el servidor web)
- Requests y BeautifulSoup (para scraping de Wikipedia)

---

## Uso básico

La API expone endpoints para:

- Consultar lista de juegos disponibles.
- Añadir un juego nuevo.
- Editar juegos existentes.
- Consultar recomendaciones personalizadas.

---

## Nota

Esta API depende del scraping de Wikipedia, por lo que cambios en la estructura de las páginas pueden afectar su funcionamiento. Se recomienda usar mecanismos de cacheo para mejorar rendimiento y reducir solicitudes externas.

---

## Licencia

Proyecto bajo licencia MIT © 2025

---

**¡Disfruta gestionando y descubriendo nuevos juegos con Videojuegos App!**
