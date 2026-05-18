# Café-IA ☕

## Descripción

Aplicación web desarrollada como proyecto académico que implementa un sistema inteligente de recomendación de café utilizando modelos de lenguaje (LLMs) mediante OpenAI, integrado con una interfaz web conversacional desarrollada en React.

El sistema permite tanto la recomendación personalizada de bebidas a partir de preferencias del usuario como un modo conversacional especializado en temas relacionados con café, preparación, métodos de extracción y cultura cafetera.

---

## Vista general

![Selección de nivel](README-assets/home.png)

![Flujo conversacional](README-assets/chat-flow.png)

![Recomendación de café](README-assets/coffee-recommendation.png)

---

## Arquitectura General

La aplicación utiliza una arquitectura frontend–backend unificada:

```text
Frontend (React)
        ↓
Assistant API
        ↓
Backend Express
        ↓
OpenAI API
```

El backend centraliza la lógica conversacional y de recomendación mediante prompts especializados para cada modo de interacción.

---

## Modos de interacción

### ☕ Recommendation Mode

El usuario responde una serie de preguntas sobre sus preferencias de sabor, intensidad, dulzura y estilo de bebida.

El sistema analiza las respuestas y genera una recomendación personalizada utilizando prompting semántico y una base de conocimiento de cafés.

### 💬 Knowledge Mode

Modo conversacional abierto enfocado exclusivamente en temas relacionados con café, incluyendo:

- métodos de preparación
- tipos de bebidas
- granos y tostados
- extracción
- cultura cafetera
- recomendaciones generales

---

## Tecnologías utilizadas

### Frontend

- React
- Vite
- Tailwind CSS
- Framer Motion
- React Router DOM

### Backend

- Node.js
- Express.js
- OpenAI API
- API REST personalizada

### Inteligencia Artificial

- LLM-based recommendation system
- Prompt Engineering
- Semantic recommendation matching

---

## Funcionalidades

- Interfaz web conversacional
- Sistema inteligente de recomendación de café
- Chat especializado en café
- Comunicación frontend–backend en tiempo real
- Recomendaciones semánticas basadas en preferencias
- Arquitectura unificada mediante OpenAI
- Transiciones dinámicas y experiencia conversacional

---

## Estado del proyecto

Proyecto académico en desarrollo activo.

---

## Aprendizajes

- Integración de modelos de lenguaje en aplicaciones web
- Diseño de arquitecturas conversacionales
- Prompt engineering
- Comunicación frontend–backend
- Desarrollo de APIs REST
- Diseño de experiencias conversacionales interactivas
- Sistemas de recomendación semánticos
