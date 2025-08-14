<!-- ![Vista previa del Portafolio](./public/presentacion/desktop-full.png) -->

![Vista previa del Portafolio](./public/presentacion/destokp-marco.png)<!-- ![Vista previa del Portafolio](./public/presentacion/mobile.png) -->

<div align="center">
  <img src="./public/presentacion/desktop-full.png" width="400" />
  <img src="./public/presentacion/mobile.png" width="250" />
</div>

## 🧠 Inspiración

> “¡La vida es el mejor maestro!” – pedro.pablo.dev

El diseño del portafolio toma inspiración de:
- La estética dinámica y limpia de redes sociales como Instagram.
- La adaptabilidad para aprender rápidamente y resolver problemas con creatividad.
- La idea de que cada experiencia (como cada proyecto aquí mostrado) forma parte del viaje de crecimiento personal y profesional.

## 📌 Funcionalidades Principales

- 🧑‍💼 Perfil con información de contacto
- 🖼️ Cuadrícula de proyectos con vistas detalladas en modales
- 🕒 Línea de tiempo de experiencia tipo storytelling
- 🧠 Sección de habilidades técnicas
- 📱 Diseño 100% responsivo para cualquier dispositivo

## 🛠️ Tecnologías Utilizadas

- **Framework Frontend**: React con TypeScript
- **Herramienta de Construcción**: Vite
- **Estilos**: Tailwind CSS
- **Iconos**: React Icons
- **Gestión de Estado**: React Hooks (useState)

## 🏗️ Estructura del Proyecto

```plaintext
src/
├── components/             # Componentes de UI
│   ├── Header.tsx          # Encabezado del perfil
│   ├── Navigation.tsx      # Navegación por pestañas
│   ├── GridProjects.tsx    # Cuadrícula de proyectos
│   ├── ModalProject.tsx    # Detalles de proyecto
│   ├── GridExperience.tsx  # Línea de tiempo
│   ├── GridSkills.tsx      # Habilidades técnicas
│   └── index.ts            # Exportador de componentes
├── constants/              # Información estática del portafolio
│   └── index.tsx
├── types/                  # Tipado global
│   └── index.ts
├── App.tsx                 # Componente raíz
└── main.tsx                # Punto de entrada
