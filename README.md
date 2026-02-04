# Calculadora React - Prueba DevOps

Una aplicación web ligera de calculadora construida con React.js y Vite.

![Calculator Screenshot](https://github.com/user-attachments/assets/27e628d4-6dec-4e4e-96c4-4260e880c7f3)

## 🚀 Características

- ✨ Interfaz moderna y elegante
- 🧮 Operaciones básicas: suma, resta, multiplicación y división
- 📱 Diseño responsive
- ⚡ Rápida y ligera (construida con Vite)
- 🎨 Gradientes de color atractivos
- 🌐 Desplegada automáticamente en GitHub Pages

## 🛠️ Tecnologías

- **React.js 19.2** - Biblioteca de interfaz de usuario
- **Vite 7.2** - Herramienta de construcción rápida
- **CSS3** - Estilos modernos con gradientes y animaciones
- **GitHub Actions** - CI/CD automatizado
- **GitHub Pages** - Hosting gratuito

## 📦 Instalación

```bash
# Clonar el repositorio
git clone https://github.com/100495726/prueba-devops.git

# Navegar al directorio
cd prueba-devops

# Instalar dependencias
npm install
```

## 🏃 Ejecución

```bash
# Modo desarrollo
npm run dev

# Construir para producción
npm run build

# Vista previa de producción
npm run preview

# Linter
npm run lint
```

## 🌐 Demo en Vivo

La aplicación está desplegada automáticamente en GitHub Pages:
https://100495726.github.io/prueba-devops/

Cada push a la rama `main` despliega automáticamente la última versión.

## 📝 Uso de la Calculadora

1. Haz clic en los números para ingresar valores
2. Selecciona una operación (+, -, ×, /)
3. Ingresa el segundo número
4. Presiona "=" para ver el resultado
5. Usa "C" para limpiar y comenzar de nuevo
6. El botón "." permite ingresar decimales

## 🔧 Configuración de GitHub Pages

El proyecto incluye un workflow de GitHub Actions (`.github/workflows/deploy.yml`) que:
- Se ejecuta automáticamente en cada push a `main`
- Construye la aplicación
- Despliega el contenido en GitHub Pages

### Activar GitHub Pages

1. Ve a Settings → Pages en tu repositorio
2. En "Source", selecciona "GitHub Actions"
3. El sitio estará disponible en: `https://[tu-usuario].github.io/prueba-devops/`

## 📂 Estructura del Proyecto

```
prueba-devops/
├── .github/
│   └── workflows/
│       └── deploy.yml       # Workflow de despliegue automático
├── public/                  # Archivos estáticos
├── src/
│   ├── App.jsx             # Componente principal
│   ├── App.css             # Estilos del componente principal
│   ├── Calculator.jsx      # Componente de la calculadora
│   ├── Calculator.css      # Estilos de la calculadora
│   ├── main.jsx            # Punto de entrada
│   └── index.css           # Estilos globales
├── index.html              # HTML principal
├── package.json            # Dependencias y scripts
├── vite.config.js          # Configuración de Vite
└── README.md               # Este archivo
```

## 🎨 Personalización

Puedes personalizar los colores editando los archivos CSS:
- `src/Calculator.css` - Estilos de la calculadora
- `src/App.css` - Estilos del título y layout principal
- `src/index.css` - Estilos globales

## 📄 Licencia

Este proyecto está bajo la licencia especificada en el archivo LICENSE.

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor:
1. Haz fork del proyecto
2. Crea una rama para tu característica (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

---

Desarrollado con ❤️ usando React y Vite
