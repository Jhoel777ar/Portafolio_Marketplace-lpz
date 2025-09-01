### Local Market - Portfolio Digital

![Local Market Logo](https://via.placeholder.com/200x200.png?text=Local+Market+Logo)---

## 📋 Resumen Ejecutivo

**Local Market** es una plataforma digital innovadora que conecta emprendedores universitarios con la comunidad local, facilitando la venta de productos y servicios mientras fomenta el ecosistema emprendedor. Desarrollada con **Laravel 12**, surge para profesionalizar la presencia digital de estudiantes emprendedores.

**Mi contribución:** Como **Scrum Master** y desarrollador backend, lideré la implementación del sistema de autenticación, gestión de usuarios y arquitectura de base de datos, coordinando la integración frontend-backend y entregando 21 Story Points en el Sprint 1.

**Impacto:** Digitalización de ventas, creación de un ecosistema emprendedor y acceso a productos únicos para la comunidad estudiantil.

---

## 💻 Contribuciones Técnicas

### Tecnologías Utilizadas

| **Backend** | **Frontend** | **Herramientas** | **Metodología** |
| --- | --- | --- | --- |
| Laravel 12 | Blade Templates | Composer | Scrum |
| PHP 8.1+ | JavaScript ES6+ | npm | Test-Driven Development |
| MySQL | CSS3 | Git | Code Review |
| Eloquent ORM | Responsive Design | JIRA | CI/CD |

### 🔑 Contribuciones Clave de Código

1. **Sistema de Autenticación y Recuperación de Contraseñas**

   - **Funcionalidad:** Registro, login y recuperación de contraseñas.
   - **Tecnologías:** Laravel Authentication, Email Verification, Password Reset.
   - **Commits:** US-001, US-002, US-003.

2. **Sistema de Gestión de Productos**

   - **Funcionalidad:** Creación, edición y gestión de productos con validaciones.
   - **Tecnologías:** Eloquent Models, Image Upload, Form Validation.
   - **Commits:** US-004, US-006.

3. **Dashboard del Emprendedor**

   - **Funcionalidad:** Panel con métricas de ventas, pedidos y análisis.
   - **Tecnologías:** Laravel Controllers, Blade Components, Chart.js.
   - **Commits:** US-010.

### 🛠️ Desafíos Técnicos Resueltos

- **Validación de Correos Universitarios:** Sistema de validación de dominios educativos con confirmación por email.\
  **Aprendizaje:** Importancia de validaciones robustas para la integridad de la comunidad.
- **Dependencias Backend-Frontend:** Documentación de APIs y comunicación clara para reducir bloqueos.\
  **Aprendizaje:** Documentación temprana clave para desarrollo ágil.
- **Gestión de Imágenes:** Compresión automática y almacenamiento optimizado.\
  **Aprendizaje:** Optimización esencial para aplicaciones multimedia.

---

## 🏃 Aplicación de Metodología Ágil

### Roles Ejercidos

**Scrum Master & Desarrollador Backend:** Facilitación de ceremonias Scrum, eliminación de impedimentos y desarrollo de funcionalidades críticas. Entrega exitosa de 21 Story Points.

### Participación en Ceremonias Scrum

| **Métrica** | **Valor** |
| --- | --- |
| Daily Scrums Facilitados | 4 |
| Asistencia Ceremonias | 100% |
| Story Points Completados | 21 |
| Velocidad Final Sprint 1 | 18 |

### Métricas Personales

- **Sprint Planning:** Estimación de 4 User Stories y distribución de tareas.
- **Daily Scrums:** Resolución de 3 impedimentos críticos.
- **Sprint Review:** Demo exitosa de 4 funcionalidades con feedback positivo.
- **Retrospectiva:** Técnica "Start-Stop-Continue" con 2 experimentos de mejora.

---

## 🤝 Desarrollo de Habilidades Blandas

| **Habilidad** | **Mejora** | **Evidencia** |
| --- | --- | --- |
| 💬 Comunicación | Daily Scrums efectivos de 15 min (de 25 min). | 0 impedimentos sin resolver en Sprint 1. |
| 👑 Liderazgo | Guía para completar 100% del Sprint Goal. | Revisiones de código obligatorias aceptadas. |
| 🔧 Resolución | Resolución de dependencias backend-frontend. | Eliminación de bloqueos técnicos. |
| 🔄 Adaptabilidad | Ajuste de prioridades en tiempo real para integración de redes sociales. | Reasignación exitosa manteniendo velocidad. |

---

## 📁 Artefactos y Evidencia

### 🖼️ Funcionalidades Implementadas

- **US-001: Registro de Emprendedor**\
  Registro con validación de correo universitario. **Feedback:** "Interfaz elegante" (8/10).
- **US-002: Registro de Cliente**\
  Registro rápido con OAuth 2.0. **Feedback:** "Velocidad excelente" (9/10).
- **US-004: Crear Producto**\
  Gestión de productos con imágenes e inventario. **Feedback:** "Amigable" (7/10).
- **US-006: Editar Productos**\
  Edición con historial de cambios. **Feedback:** "Interfaz clara" (7/10).

### 📚 Documentación Creada

- Product Backlog con 15 User Stories.
- Documentación de 4 Daily Scrums.
- Análisis de métricas y velocidad.
- Sprint Retrospective con plan de mejora.
- Sprint Review con feedback de stakeholders.

### 🏆 Reconocimientos

- **Evaluación Stakeholders:** 8.25/10 en funcionalidades.
- **Feedback Equipo:** Liderazgo efectivo y comunicación proactiva.
- **Logro Técnico:** 100% Story Points completados en Sprint 1.

---

## 👥 Equipo Stark-Next

| **Miembro** | **Rol** | **Contribuciones** |
| --- | --- | --- |
| Joel Andrés Chura | Scrum Master & Backend Developer | Autenticación, Base de Datos, Dashboard |
| Shamir Erick Condori | Frontend Developer & UX Designer | Interfaces de Registro, Social Media |
| Luis Fernando Villca | UI Designer & Backend Developer | Catálogo, API Endpoints |
| Leonardo Fidel Arana | UX Designer & Frontend Developer | Carrito, Edición de Productos |
| Danner Alejandro Calle | QA Tester | Testing, Validación, Casos de Prueba |

---

## ⚙️ Instalación y Configuración

1. **Clonar Repositorio**

   ```bash
   git clone https://github.com/Jhoel777ar/marketplace-lpz.git
   cd marketplace-lpz
   ```

2. **Instalar Dependencias**

   ```bash
   composer install
   npm install && npm run build
   ```

3. **Configurar Entorno**

   ```bash
   cp .env.example .env
   php artisan key:generate
   ```

4. **Base de Datos**

   ```bash
   php artisan migrate --seed
   ```

5. **Iniciar Servidor**

   ```bash
   php artisan serve
   ```

   Disponible en: **http://127.0.0.1:8000**

### 🎯 Accesos al Sistema

- **Panel Emprendedor:** `/emprendedor` (Gestión de productos, ventas, estadísticas).
- **Panel Administrador:** `/admin` (Gestión completa del sistema).

---

## 🌱 Reflexión y Crecimiento Futuro

### 🎓 Autoreflexión

Ser **Scrum Master** transformó mi perspectiva sobre liderazgo técnico. Balancear roles duales (Scrum Master y desarrollador) enseñó gestión del tiempo y comunicación proactiva. Entrega de 21 Story Points demostró alta productividad técnica.

### 🚀 Plan de Crecimiento

- **Corto Plazo (3 meses):**
  - Técnico: Microservicios, APIs RESTful.
  - Ágil: Certificación PSM I.
  - Liderazgo: Facilitación y resolución de conflictos.
- **Mediano Plazo (6 meses):**
  - Técnico: DevOps, automatización de deploys.
  - Ágil: Roles de Product Owner, Agile Coach.
  - Liderazgo: Proyectos con equipos distribuidos.
- **Largo Plazo (1 año):**
  - Técnico: Arquitecturas cloud-native, escalabilidad.
  - Ágil: Transformaciones ágiles en organizaciones.
  - Liderazgo: Mentoring y coaching técnico.

### 🎯 Impacto en Visión Profesional

Confirmé interés en roles híbridos (**Technical Scrum Master**). Aspiro a posiciones como **Engineering Team Lead** o **Technical Product Manager**, combinando desarrollo y liderazgo ágil.

---

## 📊 Métricas y Resultados

| **Métrica** | **Valor** |
| --- | --- |
| Story Points Completados | 21 |
| Sprint Goal Alcanzado | 100% |
| User Stories Entregadas | 4 |
| Cobertura de Código | 50% |
| Bugs en Producción | 0 |
| Evaluación Stakeholders | 8.25 |

### 📈 Evolución del Sprint

- **Día 1-2:** Setup, arquitectura, resolución de dependencias.
- **Día 3-4:** Desarrollo de funcionalidades core, integración backend-frontend.
- **Día 5-7:** Pruebas, refinamiento UI, preparación para demo.

---

## 🚀 Roadmap y Próximos Sprints

### Sprint 2 - Planificado

- **Objetivo:** Sistema de compras y carrito funcional.
- **Capacidad:** 22-24 Story Points.
- **User Stories:**
  - US-005: Explorar Catálogo.
  - US-007: Carrito de Compras.
  - US-008: Proceso de Pago Simulado.
  - US-009: Cupones y Descuentos.

### Experimentos de Mejora

- **Revisiones de Código Obligatorias:** Reducir bugs, ≤4h promedio de review.
- **Daily Scrums Optimizados:** Reducir de 25 a 15 min, actualización de tablero inmediata.

---

## 🔗 Enlaces y Contacto

Ver Repositorio Demo en Vivo Documentación Técnica

**Universidad Privada Domingo Savio**

- **Facultad:** Ingeniería en Sistemas
- **Materia:** 19EBF50 - Ingeniería de Software I
- **Docente:** Lic. Rosalía Lopez Montalvo
- **Fecha:** Agosto 2025
- **Grupo:** 2 - Equipo Stark-Next
