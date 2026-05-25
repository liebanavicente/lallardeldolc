# Guia rapida para personalizar la demo

Esta landing esta pensada como base para un negocio pequeno de packs, regalos o productos personalizados.

## Datos que hay que pedir al cliente

- Nombre del negocio
- Telefono y WhatsApp
- Email
- Instagram o red social principal
- Ciudad o zona de entrega
- 4 productos o packs iniciales
- Precio aproximado de cada pack
- Fotos propias o estilo de imagen deseado
- Colores preferidos de la marca
- Frase corta para explicar que vende

## Donde cambiar lo basico

En `index.html`, casi al final del archivo, busca:

```js
const demoConfig = {
  businessName: 'La Llar del Dolç',
  businessLogoHtml: 'La Llar <em>del Dolç</em>',
  email: 'info@llardeldolc.com',
  phoneDisplay: '612 345 678',
  phoneHref: '+34612345678',
  whatsappNumber: '34612345678',
  whatsappIntro: 'Hola, me interesa esta demo de packs regalo.',
};
```

Con eso cambias marca, email, telefono y WhatsApp en varios sitios a la vez.

## Mejoras faciles antes de ensenarla

- Cambiar los textos de los packs por productos reales.
- Cambiar las imagenes de Unsplash por fotos propias.
- Poner un WhatsApp real.
- Ajustar precios o quitar precios si aun no estan definidos.
- Subirla a Vercel y compartir el enlace de demo.
