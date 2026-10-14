# AMH Store — cliente

Catálogo de AMH Store con carrito y pedido. **Cliente** de Zerufy Studio.

**En línea:** https://amhstore.store

**Hosting:** hoy sale de GitHub Pages. Ya está preparado en Cloudflare Pages (proyecto `amhstore`, también en https://amhstore.pages.dev). Para mudarlo, el dueño tiene que poner en su cuenta de Namecheap los nameservers `emerson.ns.cloudflare.com` y `reza.ns.cloudflare.com`; después se conecta el dominio en Custom domains. El dominio está en la cuenta de Namecheap del cliente, no en la de Zerufy.

| Archivo | Qué es |
|---|---|
| `index.html` | El catálogo que ve el cliente, con carrito y pedido |
| `admin.html` | Panel para subir productos, precios, fotos y ver pedidos |
| `CNAME` | Dominio amhstore.store para GitHub Pages. Se quita cuando el sitio pase a Cloudflare |

**Supabase:** sistema de Tiendas, `store_id = 3` (tablas `stores`, `categories`, `products`, `orders`). Fotos en el bucket `store-products`, carpeta `3/`. Solo se usa la llave pública.

---
Hecho por **Zerufy Studio** · zerufystudio.com · El mapa de todos los repos está en el README de `Zerufy-Studio-`.
