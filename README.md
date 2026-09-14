# NEXORA — ERP inteligente para el sector Retail

Proyecto académico de **Ingeniería de Software II** — Facultad de Ingeniería, Universidad de Cundinamarca.
Docente: **Carlos Eduardo Mujica Reyes**.

## Equipo

| Integrante | Rol sugerido |
|---|---|
| Cristian Galeano | Backend / ASP.NET Core |
| Ronald Guayambuco | Frontend / Blazor |
| Jesús Lozano | Base de datos / Azure SQL |
| Juan José Gracia | Documentación / QA |

## ¿Qué es NEXORA?

NEXORA es un ERP web modular para pequeñas y medianas empresas de retail, que centraliza
**inventario, ventas (POS) y proveedores/compras** en un solo sistema, construido íntegramente
sobre tecnologías Microsoft.

📄 Documento completo de definición del proyecto (Sprint 0): [`/docs`](./docs/index.html) (publicado también vía GitHub Pages).

## Restricción tecnológica del proyecto

Este proyecto usa **exclusivamente herramientas, plataformas y tecnologías Microsoft**:

| Categoría | Tecnología |
|---|---|
| Backend | C# + ASP.NET Core (Web API) |
| Frontend | Blazor (.NET) |
| Base de datos | Azure SQL Database |
| IDE | Visual Studio 2022 / VS Code |
| Control de versiones | Git + GitHub |
| Gestión ágil | GitHub Projects / Azure Boards |
| Despliegue | Azure App Service |
| Modelado | Microsoft Visio |
| Documentación | GitHub Pages, Microsoft Teams, Loop/SharePoint |
| Reportería (fase futura) | Power BI |

## Estructura del repositorio

```
nexora-erp-retail/
├── README.md
├── docs/                  # Página de documentación (GitHub Pages)
│   ├── index.html
│   └── assets/
├── src/                   # Código fuente (a partir de Sprint 1)
│   ├── Nexora.Api/        # ASP.NET Core Web API
│   ├── Nexora.Web/        # Blazor frontend
│   └── Nexora.Data/       # Acceso a datos / EF Core
└── .github/
    └── workflows/         # CI/CD (a configurar en sprints posteriores)
```

## Módulos del MVP

- **Inventario**: productos, categorías, control de stock, alertas de stock mínimo.
- - **Ventas (POS)**: registro de venta, cálculo de totales, cierre de caja.
  - - **Proveedores / Compras**: gestión de proveedores, órdenes de compra automáticas.
   
    - ## Cómo colaborar
   
    - 1. Clonar el repositorio: `git clone https://github.com/C-Galeano/nexora-erp-retail.git`
      2. 2. Crear una rama de feature: `git checkout -b feature/nombre-de-la-tarea`
         3. 3. Hacer commit y push, y abrir un Pull Request hacia `main`.
            4. 4. Al menos un integrante debe revisar y aprobar el PR antes de fusionar.
              
               5. ## Licencia
              
               6. Proyecto académico — Universidad de Cundinamarca, 2026.
               7. 
