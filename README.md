# ☕ Colombian Coffee - Aplicación de Escritorio

<p align="center">
    <img src="https://img.shields.io/badge/SOLID-principios-blueviolet" alt="SOLID">
    <img src="https://img.shields.io/badge/Arquitectura%20Hexagonal-Vertical%20Slicing-6A5ACD" alt="Arquitectura Hexagonal">
    <img src="https://img.shields.io/badge/Git%20Flow-flujo-brightgreen" alt="Git Flow">
    <img src="https://img.shields.io/badge/Conventional%20Commits-commits-orange" alt="Conventional Commits">
    <img src="https://img.shields.io/badge/.NET%209-C%23-blue" alt=".NET 9">
    <img src="https://img.shields.io/badge/Entity%20Framework%20Core-ORM-purple" alt="Entity Framework Core">
    <img src="https://img.shields.io/badge/MySQL-base%20de%20datos-blue" alt="MySQL">
</p>

## 📋 Descripción del Proyecto

**Colombian Coffee** es una aplicación de escritorio desarrollada en C# (.NET 9) para la gestión de un catálogo de variedades de café colombiano. Permite explorar, filtrar y administrar datos de manera eficiente. El sistema implementa arquitectura Vertical Slicing, principios SOLID, Entity Framework Core con MySQL y exportación a PDF.

## 📁 Estructura del Proyecto

La estructura del repositorio está organizada de la siguiente manera:

```bash
ColombianCoffee/
├── ColombianCoffee.csproj
├── Docs/
├── Program.cs
└── Src/
    ├── Features/
    │   ├── Auth/
    │   │   ├── Contracts/        
    │   │   ├── Domain/           
    │   │   ├── Services/        
    │   │   ├── Infrastructure/   
    │   │   └── Presentation/     
    │   ├── Varieties/
    │   │   ├── Contracts/
    │   │   ├── Domain/
    │   │   ├── Services/
    │   │   ├── Infrastructure/
    │   │   └── Presentation/
    │   └── Reports/             
    │       ├── Contracts/
    │       ├── Domain/
    │       ├── Services/
    │       ├── Infrastructure/
    │       └── Presentation/
    └── Shared/
        ├── Common/              
        ├── Persistence/         
        └── Models/              
```

## 🛠️ Tecnologías Utilizadas

- **C# (.NET 9):** Lenguaje de programación y plataforma de desarrollo.
- **Entity Framework Core:** ORM para la gestión de la base de datos.
- **MySQL:** Sistema de gestión de bases de datos relacional.
- **Spectre.Console:** Librería para crear interfaces de consola avanzadas.
- **BCrypt.NET:** Librería para el hashing seguro de contraseñas.
- **QuestPDF:** Librería para la generación de documentos PDF.
- **Git Flow + Conventional Commits:** Flujo de trabajo para el control de versiones.

## 🚀 Instalación y Ejecución

Sigue estos pasos para clonar el repositorio, instalar las dependencias y ejecutar la aplicación:

```bash
git clone https://github.com/MaikGit1303/ColombianCoffee-.git
cd ColombianCoffee
dotnet restore
dotnet run
```

## 👋 Contribuciones

Las contribuciones al proyecto son altamente valoradas. Si desea colaborar, siga el siguiente procedimiento:

1. Realice un fork del repositorio.
2. Cree una rama descriptiva para su funcionalidad o corrección:  
   `git checkout -b feature/nombre-de-la-funcionalidad`
3. Implemente sus cambios y verifique que las pruebas se ejecuten correctamente.
4. Realice commits siguiendo el estándar [Conventional Commits](https://www.conventionalcommits.org/es/v1.0.0/).
5. Suba su rama al repositorio remoto:  
   `git push origin feature/nombre-de-la-funcionalidad`
6. Abra un Pull Request detallando los cambios realizados y el motivo de la contribución.
7. Espere la revisión y comentarios del equipo de mantenimiento.

Por favor, asegúrese de que su código siga las buenas prácticas y la arquitectura definida en el proyecto.

## 👥 Autoría

**Maikol Andrehy Romero Amado** - Desarrollador Fullstack

## 📄 Licencia

Este proyecto está bajo la licencia MIT.
