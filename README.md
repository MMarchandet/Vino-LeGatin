# LeGatín

Página web de **LeGatín**, una bodega de vino venezolano. Es un sitio estático de una sola página, hecho con HTML y CSS.

## Secciones

- **Inicio:** título, lema y botones de *Reservar* y *Tarjeta de Vino*.
- **Info:** presentación de la bodega ("El Mejor Vino de la Ciudad").
- **Historia:** la creación de LeGatín en junio de 1986, con galería de imágenes.
- **Contáctanos:** formulario con nombre, email y nota. Se envía por correo con [FormSubmit](https://formsubmit.co/).

## Estructura

```
Vino-LeGatin/
├── index.html      # Página principal
├── css/
│   └── styles.css  # Estilos
└── imagenes/       # Imágenes del sitio
```

## Cómo ejecutarlo

No necesita instalación ni dependencias. Puedes:

1. Abrir `index.html` directamente en el navegador, o
2. Servirlo con un servidor local, por ejemplo la extensión *Live Server* de VS Code (puerto 5500).

## Formulario de contacto

El formulario usa FormSubmit. La primera vez que se envíe, FormSubmit manda un correo de activación a la dirección configurada en el `action` del formulario. Hay que confirmarlo para que lleguen los mensajes.

El campo oculto `_next` redirige a `http://127.0.0.1:5500` después de enviar. Cámbialo por la URL real del sitio al publicarlo.

## Pendiente

- Reemplazar el texto de relleno (*Lorem ipsum*) por el contenido real.
- Completar el `footer`, que está vacío.
- Conectar los botones *Reservar*, *Tarjeta de Vino* y *Descubre más*.

## Autor

Moises Marchandet
