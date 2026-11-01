# legales

Páginas legales de los productos: políticas de privacidad, términos y condiciones, y similares. Se publican con GitHub Pages en <https://lucasg18c.github.io/legales/>.

## Estructura

Una carpeta por producto, con el mismo slug que en `~/Extra/productos/<slug>/`:

```
<slug>/privacy-policy.html
<slug>/terms.html
```

La URL pública queda así: `https://lucasg18c.github.io/legales/<slug>/privacy-policy.html`.

| Producto | Política de privacidad | Términos |
|---|---|---|
| Countapp | [`countapp/privacy-policy.html`](countapp/privacy-policy.html) | — |
| Skyla | [`skyla/privacy-policy.html`](skyla/privacy-policy.html) | — |

## Reglas

- **Los cambios van directo a `main`.** Hacer push a `main` publica en internet, sin vista previa.
- **Solo se publican las páginas.** `_config.yml` excluye este README de GitHub Pages. Cualquier otro archivo de documentación hay que sumarlo ahí, porque si no se publica. La raíz del sitio no tiene página y da 404.
- **Este repo es público.** Nada de secretos, datos de usuarios ni borradores.
- **Las URLs no cambian.** Google Play, AdMob y las apps enlazan estas páginas. Si hay que mover una, primero actualizar todos esos enlaces.
- **Cada página es un HTML autónomo**, con sus estilos dentro. No agregar scripts ni etiquetas de anuncios: AdMob no acepta scripts que requieran consentimiento en la página de la política.
- **El texto describe lo que hace el código.** Antes de escribirlo, revisar los SDK y servicios del producto, incluidos los que recopilan datos por su cuenta.
- **Actualizar la fecha de «Última actualización»** en cada cambio de contenido.
- **Identidad git personal:** `Lucas Slavik <lucasg18c@gmail.com>`, configurada en este repo.

## Cuándo actualizar

Hay que revisar las páginas de un producto cuando:

- se agrega o quita un SDK o servicio que recibe datos, como anuncios, errores, analítica o pagos;
- cambia qué datos salen del dispositivo o quién los recibe;
- se agregan cuentas, sincronización o funciones para compartir;
- cambia la forma de pedir consentimiento o de retirarlo.

Al cambiar una política, revisar también lo que se declara en otros lados, como Seguridad de los datos en Google Play o la privacidad de la App Store. Una página nueva o un cambio de URL se anota en `productos/<slug>/PRODUCTO.md`.

Estas páginas no son asesoramiento legal.
