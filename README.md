<div align="center">

# 💬 Exfiltración de Información mediante RAG — Frontend

### Chat en Next.js para el asistente RAG del proyecto

[![Estado](https://img.shields.io/badge/estado-en%20desarrollo-yellow)]()
[![Avance](https://img.shields.io/badge/avance-1%20%2F%203-blue)]()
[![Repo backend](https://img.shields.io/badge/repo-backend-teal)](https://github.com/ORG_O_USUARIO/rag-exfiltration-backend)

*Escuela Colombiana de Ingeniería Julio Garavito*

</div>

---

> 📦 Este repositorio contiene **solo el frontend** del proyecto. Toda la documentación completa (descripción, objetivos, arquitectura, diagramas, risk register y evidencias) vive en el repositorio del backend:
>
> ➡️ **[`rag-exfiltration-backend`](https://github.com/ORG_O_USUARIO/rag-exfiltration-backend)**

## 👥 Equipo

**Grupo 4L — Ciberseguridad y Desarrollo**
Juan Pablo Caballero Castellanos · Robinson Steven Nuñez Portela · Oscar Andrés Sánchez Porras

**Asignatura:** Fundamentos de Seguridad de la Información — Profesora Tatiana Marcela Gómez Sarmiento

## 📖 Qué hace este repositorio

Interfaz de chat donde el usuario (autenticado con un rol) consulta al asistente RAG. Este frontend:

- Envía la consulta del usuario al backend (`rag-exfiltration-backend`) vía API REST.
- Muestra la respuesta generada por el asistente.
- No contiene lógica de negocio ni acceso directo al vector store o al LLM — todo pasa por el backend.

## ⚙️ Tecnologías

- **Framework:** Next.js (React)
- **Despliegue:** Vercel
- **Comunicación con el backend:** API REST (`POST /chat`)

## 📂 Estructura de este repositorio

```
.
├── README.md
├── .gitignore
└── (código del chat — próximo paso)
```

## ▶️ Cómo ejecutar el frontend

> 🚧 Sección en construcción — se completará junto con el `package.json` y el scaffolding de Next.js.

## 🔗 Enlaces relacionados

- Documentación completa del proyecto, arquitectura, DFD y risk register: repo [`rag-exfiltration-backend`](https://github.com/ORG_O_USUARIO/rag-exfiltration-backend)

---

<div align="center">

*Proyecto académico — Fundamentos de Seguridad de la Información — Septiembre 2026*

</div>
