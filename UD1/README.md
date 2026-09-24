# Lenguajes de Marcas

## Definición
Un lenguaje de marcas es aquel que permite organizar información mediante una sintaxis basada en marcas o etiquetas.

### Tipos
| Tipo | Para qué sirve | Ejemplos |
| --- | --- | --- |
| **Presentación** | Muestra información de manera formateada. | _HML_, _CSS_ |
| **Descriptivo** | Facilita el intercambio de información entre programas. | _XML_, _JSON_ |
| **Documentación** | Se emplea para redactar documentos de información sobre proyectos. | _Markdown_, _LaTeX_ |

## Instalación y Configuración del Entorno de Trabajo
1. Instalar [VS Code](https://code.visualstudio.com/).
2. Instalar plugins:
   - [HTML CSS Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)
   - [Live Preview](https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server)
   - [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
   - [XML (Red Hat)](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-xml)
3. Instalar git:
   ```bash
   sudo apt install git
   ```
4. Configurar usuario de GitHub:
   ```bash
   git config --global user.name "Tu Usuario"
   git config --global user.email tu@email.com
   ```
5. Crear repositorio y añadir los ficheros:
   ```bash
   git init
   git add .
   ```
6. Hacer commit y publicar los cambios:
   ```bash
   git commit -m "Mensaje"
   git push origin main
   ```
## Plugins instalados
| Plugin | Imagen | Uso |
| --- | --- | --- |
| **HTML CSS Support** | ![Página de instalación del plugin HTML CSS Support.](img/HTML_CSS_Support.png) | Aporta ayuda de sintaxis y autocompleción para CSS. |
| **Live Preview** | ![Página de instalación del plugin Live Preview.](img/Live_Preview.png) | Previsualizar de código HTML en tiempo real. |
| **Markdown All in One** | ![Página de instalación del plugin Markdown All in One.](img/Markdown_All_in_One.png) | Previsualizar de código Markdown en tiempo real. |
| **XML (Red hat)** | ![Página de instalación del plugin XML (Red hat).](img/XML_(Red_Hat).png) | Aporta ayuda de sintaxis y autocompleción para XML. |