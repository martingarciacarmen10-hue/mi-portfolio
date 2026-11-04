# Mi Portfolio Personal - Carmen Martín
¡Hola! Este es mi portfolio personal. Lo he desarrollado usando **Astro** para poner en práctica lo que voy aprendiendo y mostrar mis proyectos, mi trayectoria académica y cómo contactarme.

---
# Tecnologías que he usado

--> **Astro** : El framework principal que he utilizado para construir la estructura y los componentes.
--> **HTML5 y CSS3**: Para dar forma a las secciones y ajustar los estilos (colores, espacios, tipografías).
--> **JavaScript**: Para algunos componentes.
--> **Google font**: Usé las fuentes *Cormorant Garamond*, *Montserrat* y *Alex Brush* para los textos y títulos.

---

# ¿Cómo he prganizado el proyecto?

Para tener un código limpio y ordenado, he dividido la web en varios componentes dentro de la carpeta `src`:

```text
mi-portfolio/
├── public/
│   ├── images/          # Mis fotos, iconos e ilustraciones
│   ├── favicon.ico      # Icono de la pestaña del navegador
│   └── favicon.svg      # Icono vectorial de la pestaña
├── src/
│   ├── components/      # Componentes de la web:
│   │   ├── Navbar.astro        # Menú de navegación superior
│   │   ├── Hero.astro          # Sección principal de bienvenida
│   │   ├── About.astro         # Conocimientos técnicos y habilidades personales
│   │   ├── BannerDivider.astro # Divisor visual entre secciones
│   │   ├── Education.astro     # Trayectoria académica e historia formativa
│   │   └── Footer.astro        # Pie de página con datos de contacto y redes
│   ├── layouts/
│   │   └── Layout.astro # Plantilla base con el HTML general de la web
│   └── pages/
│       └── index.astro  # Página principal donde se unen todos los componentes
├── .gitignore
├── astro.config.mjs     # Configuración principal de Astro
├── package.json         # Dependencias y scripts del proyecto
├── package-lock.json
├── README.md            # Documentación del proyecto
└── tsconfig.json        # Configuración de TypeScript



## Comandos que he utilizado

--> node -v: Comprobar que tengo Node.js instalado.
--> cd Documents: Entrar en la carpeta de Documentos, donde guardo mis proyectos.
--> npm create astro@latest mi-portfolio: Crear la estructura básica del proyecto desde cero.
--> cd mi-portfolio: Entrar en la carpeta del proyecto.
--> npm run dev: Arrancar el servidor local para ver la web en tiempo real.

