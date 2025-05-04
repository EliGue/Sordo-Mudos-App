# Manos que Hablan

**Manos que Hablan** es una aplicación web desarrollada con tecnologías modernas de Microsoft y enfocada en ofrecer una experiencia adaptable a múltiples dispositivos. Esta aplicación implementa un sistema de autenticación robusto y utiliza herramientas de desarrollo que facilitan el manejo seguro y eficiente de datos.

## Tecnologías utilizadas

- **.NET 8**: Framework principal para el desarrollo del backend y lógica de negocio.
- **SQL Server 2019**: Sistema de gestión de bases de datos relacional para almacenar la información de la aplicación.
- **Entity Framework Core (EF Core)**: ORM (Object-Relational Mapper) que permite trabajar con la base de datos utilizando código C# en lugar de escribir consultas SQL manuales.
- **ASP.NET Identity**: Sistema de autenticación integrado en .NET para la gestión de usuarios, inicios de sesión, roles, y seguridad.
- **Bootstrap**: Framework CSS utilizado en el frontend para asegurar una interfaz responsive y adaptada a todos los tamaños de pantalla.

## Características principales

- ✅ Backend desarrollado en .NET 8.
- ✅ Base de datos persistente en SQL Server 2019.
- ✅ Autenticación completa de usuarios con .NET Identity.
- ✅ Frontend responsive gracias a Bootstrap.
- ✅ Integración con Entity Framework Core para acceso a datos.

## Requisitos previos

- [.NET 8 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)
- [SQL Server 2019](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)
- Visual Studio 2022 (o superior) recomendado
- Node.js (opcional, si se quiere compilar o manejar assets del frontend)

## Configuración del proyecto

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/tu-usuario/manos-que-hablan.git
   cd manos-que-hablan
2. **Configurar la cadena de conexión en appsettings.json:**
```json "ConnectionStrings": { "DefaultConnection": "Server=TU_SERVIDOR_SQL;Database=ManosQueHablanDB;Trusted_Connection=True;" } ``` 
3. **Aplicar las migraciones y crear la base de datos:**
   ```bash
   dotnet ef database update
4.**Ejecutar la aplicación:**
  ```bash
  dotnet run
  
