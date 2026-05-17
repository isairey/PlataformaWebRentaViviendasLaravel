<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/619/619034.png" />

# 🏠 Rental House Management System

### Plataforma web de administración y renta de viviendas 🚀

<p align="center">
  <b>Rental House Management System</b> es un sistema web diseñado para administrar propiedades, gestionar alquileres y facilitar el control de viviendas en renta mediante una interfaz moderna y centralizada.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HouseRental-WebPlatform-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Management-System-success?style=for-the-badge">
  <img src="https://img.shields.io/badge/RealEstate-Platform-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/OpenSource-Academic-brightgreen?style=for-the-badge">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-módulos-del-sistema">Módulos</a> •
  <a href="#-características">Características</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-vista-previa">Vista previa</a>
</p>

</div>

---

# 🌌 Acerca del proyecto

**Rental House Management System** es una plataforma orientada a la administración de viviendas en renta, permitiendo gestionar propiedades, usuarios y procesos inmobiliarios desde un entorno centralizado.

El sistema fue desarrollado para optimizar el proceso de alquiler y administración de inmuebles, ofreciendo herramientas modernas para propietarios y administradores.

El sistema fue diseñado para:

- 🏠 Gestionar propiedades
- 👥 Administrar usuarios
- 📅 Controlar alquileres
- 📍 Organizar viviendas
- 💰 Gestionar pagos
- 📊 Visualizar información
- 🔐 Administrar accesos
- 🌐 Facilitar operaciones inmobiliarias

---

# ✨ Características

## 🏘️ Gestión inmobiliaria

- 🏠 Registro de viviendas
- 📍 Gestión de ubicaciones
- 📋 Información detallada
- 🖼️ Administración de imágenes
- 💰 Configuración de rentas

---

## 👥 Gestión de usuarios

- 👤 Registro de clientes
- 🔐 Inicio de sesión
- 📄 Gestión de perfiles
- ⚡ Administración centralizada
- 📊 Control de accesos

---

## 📅 Gestión de alquileres

- 📆 Control de rentas
- 💰 Gestión de pagos
- 📋 Historial de alquileres
- ⚡ Operaciones dinámicas
- 📊 Supervisión administrativa

---

## 📊 Panel administrativo

- 📈 Dashboard inmobiliario
- 🏠 Gestión de propiedades
- 👥 Administración de usuarios
- 📅 Control de alquileres
- 🔐 Gestión del sistema

---

# 👨‍💼 Módulos del sistema

## 🏠 Property Module

Este módulo administra las viviendas y propiedades disponibles.

### Funcionalidades:

- ➕ Registro de propiedades
- 🖼️ Gestión de imágenes
- 📍 Administración de ubicaciones
- 💰 Configuración de precios
- 📋 Información detallada

---

## 👤 Tenant Module

Este módulo es utilizado por los usuarios interesados en alquilar viviendas.

### Funcionalidades:

- 🔍 Buscar propiedades
- 📋 Consultar información
- 📅 Gestionar alquileres
- 📞 Contactar administradores
- 🏘️ Explorar viviendas

---

## 🛠️ Admin Module

Este módulo funciona como administrador principal del sistema.

### Funcionalidades:

- 👥 Gestión de usuarios
- 🏠 Supervisión inmobiliaria
- 📊 Dashboard administrativo
- 📅 Control de alquileres
- 🔐 Gestión de permisos

---

# 🛠️ Tecnologías utilizadas

## 🎨 Frontend

<p>
  <img src="https://skillicons.dev/icons?i=html,css,js,bootstrap" />
</p>

- HTML5
- CSS3
- JavaScript
- Bootstrap

---

## ⚙️ Backend

<p>
  <img src="https://skillicons.dev/icons?i=php" />
</p>

- PHP
- Arquitectura web
- Sistema CRUD
- Gestión administrativa

---

## 🗄️ Base de datos

<p>
  <img src="https://skillicons.dev/icons?i=mysql" />
</p>

- MySQL
- Persistencia de datos
- Relaciones SQL
- Gestión inmobiliaria

---

## 🧰 Herramientas

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode" />
</p>

- Git
- GitHub
- Visual Studio Code
- XAMPP / WAMP

---

# 📂 Estructura del proyecto

```bash
RentalHouseManagementSystem/
│
├── admin/                    # Panel administrativo
├── properties/               # Gestión de propiedades
├── tenants/                  # Gestión de usuarios
├── assets/                   # Recursos frontend
├── database/                 # Scripts SQL
├── uploads/                  # Imágenes de viviendas
├── includes/                 # Configuración del sistema
├── index.php                 # Página principal
├── login.php                 # Inicio de sesión
├── register.php              # Registro de usuarios
├── README.md
└── LICENSE
```

---

# ⚡ Instalación

## 📋 Requisitos

- PHP 7+
- MySQL
- Apache
- XAMPP / WAMP
- Navegador moderno

---

# 🚀 Configuración del proyecto

## 1️⃣ Clonar repositorio

```bash
git clone https://github.com/isairey/RentalHouseManagementSystem.git
```

---

## 2️⃣ Mover archivos

Copiar proyecto hacia:

```bash
xampp/htdocs/RentalHouseManagementSystem/
```

---

## 3️⃣ Crear base de datos

Crear base:

```bash
rental_house_system
```

---

## 4️⃣ Importar SQL

Importar:

```bash
database/rental_house_system.sql
```

---

## 5️⃣ Configurar conexión

Editar:

```bash
includes/config.php
```

Agregar:

```php
define('DB_HOST','localhost');
define('DB_USER','root');
define('DB_PASS','');
define('DB_NAME','rental_house_system');
```

---

## 6️⃣ Ejecutar proyecto

Abrir:

```bash
http://localhost/RentalHouseManagementSystem/
```

---

# 📊 Funcionalidades principales

## 🏠 Gestión inmobiliaria

- Publicación de propiedades
- Gestión de viviendas
- Administración de alquileres
- Control de disponibilidad

---

## 👥 Administración de usuarios

- Registro y autenticación
- Gestión de perfiles
- Administración de clientes
- Roles administrativos

---

## 📅 Gestión de rentas

- Control de pagos
- Historial de alquileres
- Supervisión administrativa
- Información detallada

---

# 📸 Vista previa

## 🖥️ Interfaces del sistema

<div align="center">

### 🔐 Inicio de sesión
![Login](https://github.com/lvweicheng/Rental-house-management-system/blob/master/WX20180903-111006.png)

</div>

---

# 🧠 Objetivos del proyecto

## 🎯 Aprendizaje y administración

- Desarrollo web full stack
- Gestión inmobiliaria
- Bases de datos relacionales
- CRUD administrativos
- Sistemas de autenticación
- Arquitectura web
- Automatización de procesos

---

# 🚧 Roadmap

## 🔮 Próximas mejoras

- 📱 Aplicación móvil
- ☁️ Infraestructura cloud
- 💳 Integración de pagos online
- 📊 Dashboard avanzado
- 🤖 Recomendaciones inteligentes
- 🌐 API REST moderna
- 🔔 Notificaciones en tiempo real

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Fork del proyecto

```bash
git checkout -b feature/nueva-funcionalidad
```

2. Commit

```bash
git commit -m "✨ Nueva funcionalidad"
```

3. Push

```bash
git push origin feature/nueva-funcionalidad
```

4. Pull Request 🚀

---

# 👨‍💻 Desarrollador

<div align="center">

## Isai Reyes — Full Stack Developer

Desarrollador apasionado por plataformas inmobiliarias, sistemas administrativos y soluciones web modernas 🚀

</div>

---

# 🌟 Apoya el proyecto

⭐ Dale una estrella  
🍴 Haz fork  
📢 Comparte el proyecto

---

# 📜 Licencia

Proyecto open source orientado al aprendizaje y administración de sistemas inmobiliarios.

---

<div align="center">

### 🏠 Rental House Management System — administración inteligente de propiedades y alquileres 🚀

</div>
