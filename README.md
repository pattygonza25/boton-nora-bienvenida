# Bot-On NORA · Landing Bienvenida Beta

Landing page de bienvenida para usuarios beta de Bot-On NORA. Presenta el producto, agradece a los primeros usuarios y recopila feedback a través de un formulario integrado. Diseñada especialmente para adultos mayores de 60 años con tipografía grande, contrastes claros y lenguaje simple y cálido.

---

## Sobre esta página

Esta página fue creada para los usuarios beta de Bot-On NORA, el producto de acompañamiento cognitivo de Bot-On que opera por WhatsApp. La página presenta NORA a usuarios que ya se registraron, les agradece por ser parte del programa beta y recopila su experiencia a través de un formulario de Tally.

---

## Personalización por nombre

La página soporta personalización del nombre del usuario a través de un parámetro en la URL.

**URL sin nombre:**
```
https://pattygonza25.github.io/boton-nora-bienvenida
```

**URL con nombre:**
```
https://pattygonza25.github.io/boton-nora-bienvenida?nombre=Carmen
```

Cuando se incluye el parámetro `nombre`, la página muestra **"Hola Carmen. Bienvenido a NORA."** en el headline principal. El nombre se capitaliza automáticamente sin importar cómo se escriba en la URL.

---

## Consideraciones de diseño para adultos mayores

La página fue diseñada específicamente pensando en usuarios mayores de 60 años. Estas son las decisiones de diseño que guiaron su construcción:

- **Tipografía base de 18px**, mayor que el estándar web, para facilitar la lectura sin esfuerzo
- **Títulos mínimo 32px** con `clamp()` para adaptarse de forma fluida a cualquier tamaño de pantalla
- **Contrastes de color muy marcados** entre texto y fondo para facilitar la lectura en cualquier condición de luz
- **Lenguaje simple, cálido y sin tecnicismos**, cercano y directo, sin asumir conocimientos digitales
- **Botones grandes con padding generoso** para facilitar el clic en dispositivos móviles y pantallas táctiles

---

## Estructura de la página

1. **Header fijo** con logo Bot-On
2. **Bienvenida** con headline dinámico personalizado
3. **Así funciona NORA**, tres tarjetas explicativas
4. **Cuéntanos cómo te va**, introducción al feedback
5. **Formulario de feedback** integrado con Tally
6. **Cierre** con mensaje de agradecimiento
7. **Footer** con disclaimer

---

## Tecnologías

- HTML5, CSS3 y JavaScript vanilla
- Sin frameworks ni dependencias externas
- [Google Fonts, Ubuntu](https://fonts.google.com/specimen/Ubuntu)
- [Tally](https://tally.so) para el formulario de feedback
- [GitHub Pages](https://pages.github.com) para el hosting

---

## Brand System

| Color | Hex | Uso |
|---|---|---|
| Azul claro | `#6AB7EA` | Fondos dominantes |
| Azul primario | `#008bdb` | Botones y acentos |
| Navy | `#1a1f5e` | Header y footer |
| Navy profundo | `#12174a` | Footer |
| Blanco | `#ffffff` | Fondos |
| Gris claro | `#f0f4f8` | Fondos de secciones |

---

## Cómo generar links para usuarios beta

Para generar links personalizados para cada usuario beta se puede usar una hoja de cálculo con la siguiente fórmula en Google Sheets o Excel:

```
="https://pattygonza25.github.io/boton-nora-bienvenida?nombre="&A2
```

Donde `A2` contiene el nombre del usuario. Esto genera un link único por persona que se puede enviar directamente por WhatsApp o email. Solo hay que arrastrar la fórmula hacia abajo para generar tantos links como usuarios haya en la lista.

---

## Deployment

La página está desplegada en GitHub Pages y se actualiza automáticamente con cada push a la rama `main`. No requiere pasos de build ni configuración adicional.

**URL de producción:**
```
https://pattygonza25.github.io/boton-nora-bienvenida
```

---

## Parte del ecosistema Bot-On

Esta landing es parte del ecosistema de productos de Bot-On, que incluye:

- **Bot-On NORA**, acompañamiento cognitivo para adultos mayores
- **Bot-On TEO**, entrenamiento mental para profesionales y adultos activos

Ambos productos operan 100% por WhatsApp, sin necesidad de descargar aplicaciones ni crear cuentas.

---

© 2026 Bot-On. Confidencial.
