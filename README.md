# Perfil Random 👨‍💻

Proyecto simple en **Vanilla JS** que consume la API [RandomUser.me](https://randomuser.me/api) y muestra el perfil aleatorio de un supuesto **desarrollador web**.  
El proyecto utiliza **Webpack** y varios plugins para manejar **CSS, imágenes, minificación** y compatibilidad con **Babel**.

---

## 🚀 Características
- Consumo de API REST con `fetch`.
- Generación de un perfil aleatorio (nombre, foto, correo, etc.).
- Interfaz ligera con HTML, CSS y JS puro.
- Configuración de **Webpack** para:
  - Compilación de JS con Babel (compatibilidad ES6+).
  - Carga y minificación de CSS.
  - Manejo de imágenes y assets.
  - Optimización en producción.


## ⚙️ Instalación y uso

### 1. Clonar el repositorio
```bash
git clone https://github.com/palmalion1980/perfil_random.git
cd perfil_random
2. Instalar dependencias
bash
Copiar código
npm install
3. Entorno de desarrollo
Ejecuta el servidor de desarrollo:

bash
Copiar código
npm run dev
Accede en http://localhost:8080.

4. Generar build para producción
bash
Copiar código
npm run build
Esto crea la carpeta /dist lista para desplegar en Netlify u otro servicio.

## 🛠️ Tecnologías utilizadas
JavaScript (Vanilla)

Webpack + Plugins:

html-webpack-plugin

css-loader, style-loader, mini-css-extract-plugin

babel-loader (para compatibilidad)

image-webpack-loader (optimización de imágenes)

terser-webpack-plugin, css-minimizer-webpack-plugin

API pública: randomuser.me

## 📸 Vista previa
Ejemplo de perfil generado:


👨‍💻 Nombre: John Doe
📧 Correo: john.doe@example.com
🌍 País: United States
📄 Licencia
Este proyecto se distribuye bajo licencia MIT.

Eres libre de usarlo, modificarlo y compartirlo.
