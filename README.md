#  Auto Servicio San Jorge - Sistema de Gestión de Taller Mecánico

Sistema web integral para la administración operativa y financiera del taller mecánico **Auto Servicio San Jorge**. Diseñado para optimizar la recepción de vehículos, control de inventario, seguimiento de reparaciones y venta de refacciones.

---

##  Características Principales

* **Autenticación y Roles (RBAC):** Accesos segmentados para Administrador, Técnico y Cliente.
* **Registro de Clientes y Vehículos:** Mapeo de clientes con múltiples vehículos vinculados.
* **Agenda de Citas:** Programación interactiva de servicios sin empalmes.
* **Gestión de Ventas e Inventario:** Control de stock de refacciones con descuento automático y transaccional por venta.
* **Caja y Cobro:** Procesamiento de pagos y generación de comprobantes digitales.
* **Historial Técnico:** Bitácora detallada de reparaciones y mantenimientos por vehículo.
* **Notificaciones:** Avisos automáticos de estatus de reparación al cliente.
* **Reportes y Analítica:** Estadísticas operativas y financieras exportables.

---

##  Stack Tecnológico

* **Frontend:** Next.js / React, Tailwind CSS
* **Backend:** Node.js (Express) / Next.js API Routes
* **Base de Datos:** PostgreSQL / Supabase
* **Despliegue & Cloud:** Vercel, AWS S3 (Almacenamiento de evidencias)
* **Control de versiones:** Git y GitHub

---

##  Instalación y Configuración Local

### Prerrequisitos

* Node.js (v18 o superior)
* npm, yarn o pnpm
* Instancia de PostgreSQL en ejecución

### Pasos

1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/klesnuck/auto-servicio-san-jorge.git](https://github.com/klesnuck/auto-servicio-san-jorge.git)
   cd auto-servicio-san-jorge 
   ```

2. Instalar dependencias
``` 
npm install
``` 

3. Iniciar el servidor de desarrollo
``` 
npm run dev 
``` 
