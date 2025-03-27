# 🌐 Mi Sitio Web con Jekyll

Este es el código fuente de mi sitio web personal, creado con [Jekyll](https://jekyllrb.com/) y alojado en [GitHub Pages](https://pages.github.com/).  

## 🚀 Características  

- Diseño personalizado sin usar un theme predefinido  
- Uso de layouts en `_layouts/`  
- Componentes reutilizables en `_includes/`  
- Estilos en `assets/css/style.css`  
- Compatible con GitHub Pages  

## 📂 Estructura del Proyecto  

mi-pagina/
│── _layouts/
│   ├── default.html
│   ├── post.html
│── _includes/
│   ├── head.html
│   ├── header.html
│   ├── footer.html
│── assets/
│   ├── css/
│   │   ├── style.css
│   ├── img/
│── _posts/
│── about.md
│── index.md
│── _config.yml


## 🛠️ Instalación y Uso  

1. Clona este repositorio:  
   ```sh
   git clone https://github.com/tu-usuario/tu-repositorio.git
   cd tu-repositorio
2. Instala Jekyll y las dependencias:
    ```sh
    gem install jekyll bundler
    bundle install
3. Inicia un servidor local:
    ```sh
    bundle exec jekyll serve
4. Abre tu navegador en:
    ```arduino
    http://localhost:4000

## 🌍 Despliegue en GitHub Pages
Este sitio se despliega automáticamente en GitHub Pages cada vez que se actualiza la rama main. Asegúrate de que en la configuración del repositorio, GitHub Pages esté activado en la rama correcta.

## 📜 Licencia
Este proyecto está bajo la licencia MIT.