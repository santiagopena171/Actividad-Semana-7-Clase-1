# Análisis de páginas de detalle de producto (PDP) — Temu (web de escritorio)

> Corte: agosto 2025 • Alcance: versión web de escritorio de Temu. Puede variar en app móvil o regiones.

## Encabezado y navegación
- **Logo:** ubicado en la **esquina superior izquierda**. Funciona como enlace a la página principal (patrón estándar).
- **Buscador:** barra de búsqueda **en la parte superior, centrada** o centrada hacia el eje del encabezado. Incluye icono de lupa y placeholder.
- **Carrito:** **visible en la barra superior** (esquina superior derecha). Se representa con un **icono de carrito de compras**. Al pulsarlo abre el panel/página del carrito.
- **Perfil / iniciar sesión:** acceso en la **esquina superior derecha**, junto al carrito (icono de usuario / texto “Iniciar sesión” según estado).
- **Tipo de menú:** **menú horizontal superior** con accesos a categorías y promos; usa **desplegables** para subcategorías. En móvil se resuelve con **menú hamburguesa**.

## Disposición en la PDP
- **Imágenes del producto:** a la **izquierda**, con **galería vertical de miniaturas** y área principal de imagen/galería.
- **Título, precio y señales de confianza:** en la **columna derecha**, por encima del pliegue. Incluye precio, descuento/cupones, variaciones (talla/color), envío y devoluciones.
- **Botones de acción:** **“Agregar al carrito”** y **“Comprar ahora”** se ubican en la **columna derecha**, inmediatamente debajo de precio/variantes.
- **Descripción y características:** **debajo del módulo principal**, en secciones/tabs como “Descripción”, “Detalles”, “Especificaciones” y **Reseñas** de clientes.
- **Contenido adicional frecuente:** módulos de “Preguntas y respuestas”, productos relacionados (“También te puede gustar”) y bloques de promociones/temporizadores.

## Observaciones de UX (reflexión)
1. **Estructura de dos columnas clásica**: galería a la izquierda y “columna de conversión” a la derecha. Reduce fricción para decidir (ver imágenes) y actuar (precio + CTA).
2. **Búsqueda prominente**: la barra superior centrada refleja el peso del buscador en catálogos muy amplios.
3. **Señales de confianza y urgencia**: badges de envío/devoluciones y contadores de oferta reforzando conversión; útiles, pero conviene no saturar (riesgo de “banner blindness”).
4. **Gestión de variantes junto a CTA**: seleccionar talla/color antes del CTA evita errores en el carrito y reduce pasos.
5. **Información larga en secciones colapsables**: descripción técnica extensa y reseñas se relegan bajo el pliegue para no competir con el área de compra inmediata.
6. **Consistencia con patrones de mercado**: la cabecera (logo–búsqueda–cuenta–carrito) y la PDP en dos columnas siguen estándares comunes, lo que acorta la curva de aprendizaje.

## Recomendaciones (si se replicara el patrón)
- Mantener **CTA primarios grandes** y por encima del primer pliegue.
- Asegurar **texto alternativo** y **zoom** en galería para confianza en categorías táctiles (moda, hogar).
- Incluir **políticas de envío/devolución** resumidas cerca del precio (máximo 2–3 bullet points).
- Evitar demasiadas **llamadas de urgencia** simultáneas; priorizar una sola.
- Hacer que la cabecera sea **sticky** solo si no tapa contenido; ajustar altura reducida al hacer scroll.

---

### Resumen rápido (para checklist)
- Logo: arriba izquierda → inicio
- Buscador: arriba, centrado
- Carrito: arriba derecha, icono carrito
- Perfil: arriba derecha, junto al carrito
- Menú: horizontal superior (desplegable);
- Imágenes: izquierda (galería)
- Descripción/especificaciones: debajo, en secciones
- Precio: derecha, junto al título
- CTA: derecha, bajo el precio

