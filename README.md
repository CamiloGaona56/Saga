# SagaBag - Sitio Web Oficial y Portafolio de Productos

SagaBag es una landing page y catálogo virtual responsivo diseñado para **Manufacturas Saga**, una empresa 100% colombiana con más de 19 años de trayectoria en el sector textil de manufactura. La empresa está dedicada al diseño, confección y comercialización de artículos de alta calidad como morrales, maletas, bolsos, loncheras y accesorios en general.

Este sitio web permite a los usuarios explorar los diferentes productos, examinar sus detalles técnicos y características a través de modals interactivos con carruseles de imágenes, y cotizar directamente por WhatsApp.

---

## 🚀 Características Principales

- **Diseño Responsivo (Mobile-First):** Totalmente adaptable a dispositivos móviles, tablets y computadoras gracias a Bootstrap 5.
- **Portafolio Interactivo:** Sección de productos organizada en cuadrícula con modales detallados para cada artículo.
- **Carrusel de Imágenes Personalizado:** Cada modal cuenta con un carrusel interactivo que permite ver el producto desde distintos ángulos (Frente, Lateral, Posterior, Superior).
- **Integración con WhatsApp:** Botón flotante persistente y botones de cotización directa por cada producto que pre-cargan un mensaje personalizado con la referencia seleccionada.
- **Sección Corporativa "Quiénes Somos":** Línea de tiempo que narra la historia, misión, valores y compromisos sociales/ambientales de la marca.
- **Formulario de Contacto Dinámico:** Captura información básica del usuario (Nombre, Correo y Comentario) y automatiza el envío del mensaje preformateado a través de WhatsApp.

---

## 🛠️ Tecnologías Utilizadas

El proyecto está desarrollado con tecnologías web estándar para garantizar una carga rápida y compatibilidad total:

* **HTML5:** Estructuración semántica de todo el sitio.
* **CSS3:** Estilos personalizados basados en la plantilla *Agency* de Start Bootstrap, adaptados a la identidad visual de SagaBag.
* **JavaScript (Vanilla JS):** Lógica interactiva para la barra de navegación (efecto shrink al hacer scroll), ScrollSpy, colapso de menú en móviles y redirecciones automáticas a WhatsApp.
* **Bootstrap v5.1.3:** Framework de CSS para el grid del portafolio, tipografía, modals y componentes dinámicos.
* **Font Awesome v6.1.0:** Biblioteca de iconos vectoriales para elementos gráficos y redes sociales.
* **Google Fonts:** Tipografías *Montserrat* y *Roboto Slab* para un diseño moderno y legible.

---

## 📁 Estructura del Proyecto

El código fuente del proyecto se organiza de la siguiente manera:

```text
Saga/
├── Style/                         # Carpeta contenedora de los archivos de la web
│   ├── Saga/                      # Assets fotográficos de los productos
│   │   ├── Canguro motociclista/  # Fotos del canguro motociclista
│   │   ├── Canguro sencillo/      # Fotos del canguro sencillo
│   │   ├── Morral Academico/      # Fotos del morral académico
│   │   ├── Morral de campo/       # Fotos del morral tipo ingeniero
│   │   ├── Morral motociclista/   # Fotos del morral motociclista
│   │   └── (Logos e imágenes complementarias)
│   ├── assets/                    # Assets del tema/plantilla base (favicon, iconos)
│   ├── css/
│   │   └── styles.css             # Estilos CSS compilados de Bootstrap y personalizados
│   ├── js/
│   │   └── scripts.js             # Lógica JS del comportamiento del menú y navegación
│   └── index.html                 # Estructura principal y modals del sitio web
└── README.md                      # Documentación del proyecto (este archivo)
```

---

## 🎒 Catálogo de Productos Detallado

A continuación se listan las referencias principales incluidas en el sitio:

| Producto | Referencia | Capacidad | Características Clave | Peso |
| :--- | :---: | :---: | :--- | :---: |
| **Morral Tipo Ingeniero** | `M1-02` | 26 Lt | Espalda ergonómica, correas ajustables, cremalleras antirrobo, porta laptop (14"). | 620 g |
| **Morral Académico** | `M1-03` | 24 Lt | Estilo clásico y sencillo, organizador interno, 2 compartimentos, costuras no visibles, porta laptop (14"). | 430 g |
| **Morral Motociclista** | `M1-01` | 23 - 29 Lt | Expansible con cremalleras, sistema de sujeción en abdomen, cremalleras antirrobo, ergonómico. | 650 g |
| **Canguro Sencillo** | `M2-02` | N/A | Monedero interno, porta celular, porta documentos, costuras no visibles. | 105 g |
| **Canguro Motociclista** | `M2-01` | N/A | Convertible (pierna o bolso), correas ajustables, 3 compartimentos, costuras ocultas. | 160 g |

---

## 💻 Ejecución en Local

Al ser un sitio web estático, no requiere un servidor de aplicaciones ni base de datos para funcionar. 

### Pasos para visualizar el proyecto:
1. Descarga o clona este repositorio.
2. Navega a la carpeta `Style/`.
3. Haz doble clic en el archivo [index.html](file:///c:/Proyect/Saga/Style/index.html) para abrirlo directamente en cualquier navegador moderno (Google Chrome, Firefox, Edge, Safari).

*Opcional (para desarrollo local):* Puedes utilizar la extensión **Live Server** de VS Code o cualquier servidor local de desarrollo (`http-server`, `browser-sync`, etc.) en la raíz del proyecto para visualizar los cambios en tiempo real.

---

## 📞 Enlaces y Canales de Atención

- **Sitio de producción / hosting:** Configurado bajo el dominio de GoDaddy (detalles en `Style/Saga/Godaddy.txt`).
- **WhatsApp Directo:** +57 317 678 3106
- **Instagram:** [@sagabagco](https://www.instagram.com/sagabagco/)
- **Facebook:** [Manufacturas Saga](https://www.facebook.com/manofacturas.saga/)
