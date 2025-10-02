# 🌱 La Quimera - Sitio Web Empresarial

Este proyecto es la página web oficial de **La Quimera S.A**, una empresa dedicada a la siembra y cultivo de caña de azúcar, trigo, soja y zapallo, además de ofrecer servicios de pulverización y cosecha de caña de azúcar.  

El sitio fue desarrollado con **Blazor WebAssembly** utilizando **.NET 7**, pensado para ser **responsivo**, moderno y desplegado de manera sencilla en **GitHub Pages**.

---


## 🖼️ Capturas del sistema

- Inicio
<img width="1917" height="946" alt="image" src="https://github.com/user-attachments/assets/856ee176-f291-4228-8479-dcd9bac3b701" />

- Cultivos
<img width="1916" height="945" alt="image" src="https://github.com/user-attachments/assets/dbf35eda-938d-4cf9-a08d-bef72d38f05b" />

- Servicios
<img width="1917" height="944" alt="image" src="https://github.com/user-attachments/assets/6b5e79ce-7133-423b-89af-b17f6422913c" />

- Sobre Nosotros
<img width="1917" height="943" alt="image" src="https://github.com/user-attachments/assets/ce6175fb-72ac-4562-8fff-76bf88a16809" />


---

## 🛠️ Tecnologías utilizadas

- **.NET 7** → Framework principal para construir aplicaciones modernas.
- **Blazor WebAssembly** → Permite ejecutar aplicaciones web interactivas directamente en el navegador, sin necesidad de backend.
- **HTML5 / CSS3** → Diseño visual, estilos personalizados y estructura del sitio.
- **Bootstrap** → Framework de estilos para asegurar un diseño responsivo.
- **GitHub Pages** → Servicio gratuito de GitHub para desplegar sitios estáticos.
- **Visual Studio 2022** → Entorno de desarrollo integrado (IDE).

---

## 📂 Estructura del Proyecto

```
LaQuimera/
│── wwwroot/           # Archivos estáticos (imágenes, CSS, JS, fuentes)
├── css/               # Hojas de estilo personalizadas
├── images/            # Recursos gráficos (iconos, cultivos, logotipo)
│── Pages/             # Páginas de la aplicación Blazor
├── Index.razor        # Página principal (Inicio)
├── Contact.razor      # Página de contacto con formulario
│── Shared/            # Componentes compartidos (Header, Footer, NavMenu)
│── Program.cs         # Configuración principal de la app Blazor
│── LaQuimera.csproj   # Archivo de configuración del proyecto
```

---

## 📑 Páginas principales

### 🏡 Inicio (`Index.razor`)
- Bienvenida a los visitantes.
- Presentación de los cultivos principales (caña de azúcar, trigo, soja, zapallo).
- Animaciones y tarjetas interactivas de cada cultivo.

### 📬 Contacto (`Contact.razor`)
- Formulario de contacto con validación.
- Campos: **Nombre, Correo Electrónico, Mensaje**.
- Botón de envío estilizado con Bootstrap.
- Preparado para integrarse con un **API o servicio de correo**.

### 🔗 Navegación (`NavMenu.razor`)
- Barra de navegación superior con enlaces a **Inicio** y **Contacto**.
- Estilos adaptativos para dispositivos móviles, tablet y escritorio.

### ⚡ Footer
- Información de derechos de autor de La Quimera.
- Estilo minimalista y fijo al final de la página.

---

## 🎨 Estilos personalizados

El diseño se realizó con una paleta de **verdes** para transmitir el estilo de campo y naturaleza:

- **Verde oscuro:** `#204921`
- **Verde medio:** `#2D5425`
- **Verde claro:** `#f0f9f0`

También se configuraron:
- **Tipografía principal:** Segoe UI / Galano Grotesque.
- **Tarjetas de cultivos con hover animado.**
- **Diseño responsivo con `flexbox` y media queries.**

---

## 📱 Responsividad

El sitio se adapta automáticamente a:
📱 Teléfonos

💻 Computadoras

📟 Tablets

Esto se logra con flexbox, media queries y componentes de Bootstrap.

---

## 📌 Próximas mejoras

- Integrar un backend API para enviar correos desde el formulario de contacto.
- Añadir más secciones: Servicios, Galería, Historia de la empresa.
- Animaciones adicionales para una experiencia más interactiva.
- Optimización SEO para mejor posicionamiento en buscadores.
---

## 👨‍💻 Autor

**Luis Nicolás Gomez**  
Proyecto desarrollado para La Quimera S.A con fines corporativos y de presentación en línea.
