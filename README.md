# Proyecto de Página Web Responsiva con SASS

## Descripción

Este proyecto es una página web responsiva sobre una tienda ficticia de productos ecologicos diseñada con SASS.
La estructura y el estilo del sitio están optimizados para adaptarse a diferentes tamaños de pantalla, utilizando mixins y variables para mantener la coherencia en el diseño.
El proyecto incluye secciones como una galería de productos, una sección de "Sobre Nosotros", y un footer.

## Estructura del Proyecto

### Variables
- **Colores:** Se utilizan variables para definir los colores principales, secundarios, terciarios y de impacto.
- **Tamaños de Fuente:** Se definen tamaños de fuente en `rem` para asegurar la escalabilidad.

### Mixins
- **flexCenter:** Facilita el centrado de elementos utilizando Flexbox.
- **cardProduct:** Estiliza las tarjetas de productos, adaptándolas a diferentes dispositivos.
- **imgStandar:** Aplica un estilo uniforme a las imágenes, asegurando consistencia.
- **tablet & desktop:** Media queries para adaptar estilos a dispositivos tablet y desktop.

### Estilos Globales
- **box-sizing:** `border-box` aplicado globalmente para evitar problemas de espaciado.
- **font-size:** Base de `62.5%` para facilitar el uso de `rem` en tamaños de fuente.
- **Reseteo de márgenes y paddings:** Garantiza que todos los elementos partan de una base uniforme.

### Secciones Principales
- **Header:** Incluye la navegación principal, que se centra y adapta según el dispositivo.
- **about-us__section:** Sección de "Sobre Nosotros" con imágenes y texto alineado al centro.
- **products__gallery:** Galería de productos con un diseño en carrusel en móviles y en cuadrícula en pantallas más grandes.
- **persuading__section:** Sección de razones para persuadir al usuario, con imágenes y textos destacados.
- **styles__gallery:** Galería de estilos, adaptable a diferentes relaciones de aspecto.
- **location__section:** Información sobre la ubicación, con imágenes y textos destacados.

### Footer
- **Distribución:** Organizado en columnas que se adaptan al tamaño de la pantalla.
- **Información:** Incluye listas de enlaces informativos y redes sociales.

## Instalación

1. Clona el repositorio:
    ```bash
    git clone https://github.com/tu-usuario/tu-repositorio.git
    ```
2. Navega al directorio del proyecto:
    ```bash
    cd tu-repositorio
    ```
3. Instala las dependencias (opcional si tienes un sistema de compilación de SASS):
    ```bash
    npm install
    ```

## Uso

1. Compila los archivos SCSS a CSS:
    ```bash
    npm run sass
    ```
2. Abre el archivo `index.html` en tu navegador para ver el sitio.

## Contribuciones

Si deseas contribuir a este proyecto, por favor realiza un fork del repositorio, crea una nueva rama con tus cambios, y realiza un pull request.

## Link

Podes acceder a la pagina desde este link: [Eco-store](https://blix-luxta.github.io/Eco-store/)

## Licencia

Este proyecto está bajo la licencia MIT.

## Autor

- **Blix-Luxta** - [LinkedIn](https://www.linkedin.com/in/nahuel-agustin-caero/)

