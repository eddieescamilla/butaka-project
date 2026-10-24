# Butaka: Tu lugar te espera

Prototipo en HTML y CSS de **Butaka**, una plataforma de venta y gestión de boletos para conciertos, teatro y deportes en El Salvador. Recrea las pantallas que diseñamos en Figma, siguiendo nuestro manual de marca. 

## Equipo

| Integrante | Carné | GitHub |
|---|---|---|
| José Edgardo Rosales Escamilla | 00129426 | [@eddieescamilla](https://github.com/eddieescamilla) |
| Gabriel Enrique Mejía Castillo | 00063924 | [@MMejiaC05](https://github.com/MMejiaC05) |

**Materia:** Programación Orientada al Usuario

**Docente:** Ing. Néstor Aldana

**Universidad Centroamericana "José Simeón Cañas" (UCA)**

## Pantallas

| Archivo | Pantalla |
|---|---|
| `index.html` | Inicio sin sesión |
| `login.html` | Inicio con el modal de inicio de sesión |
| `inicio.html` | Inicio con sesión iniciada |

Las páginas están enlazadas entre sí: "Iniciar sesión" abre el modal, "Cancelar" regresa al inicio, el formulario lleva al inicio con sesión y "Cerrar sesión" regresa al inicio. 

## Cómo verlo

1. Clona el repositorio
````bash
git clone https://github.com/eddieescamilla/butaka-project.git
````
2. Abre `index.html` en el navegador, o usa la extensión Live Server de Visual Studio Code. 

## Estructura del proyecto

```
butaka-project/
├── index.html
├── login.html
├── inicio.html
├── css/
│   ├── base.css      Variables del manual de marca y estilos generales
│   ├── header.css    Encabezado y navegación
│   ├── modal.css     Modal de inicio de sesión
│   ├── hero.css      Banner principal
│   ├── eventos.css   Sección de eventos destacados
│   └── footer.css    Pie de página
└── img/              Logo y fotos de los eventos
```

## Reparto del trabajo

Dividimos el trabajo por componentes: Cada uno hizo el HTML y el CSS completo de sus partes. 

| Componente | Responsable |
|---|---|
| Base del proyecto (variables, estilos generales, logo y esqueleto de las páginas) | José Edgardo Rosales Escamilla |
| Hero | José Edgardo Rosales Escamilla |
| Eventos destacados | José Edgardo Rosales Escamilla |
| Footer | José Edgardo Rosales Escamilla |
| Header (con y sin sesión iniciada) | Gabriel Enrique Mejía Castillo |
| Modal de inicio de sesión | Gabriel Enrique Mejía Castillo |

## Tecnologías y convenciones

- **HTML5 Semántico:** `header`, `nav`, `main`, `section`, `article` y `footer`, con atributos de accesibilidad (`alt`,`label`, `aria-*`).
- **CSS3** con variables para los colores, espacios y bordes del manual de marca, flexbox y grid. 
- **Fuentes:** Poppins para títulos e Inter para el texto, de Google Fonts. 
- **Clases con la convención BEM**, en español (Por ejemplo, `.tarjeta__titulo` y `.boton--primario`).
- **Git:** Una rama por componente, unida a `main` mediante pull requests. 