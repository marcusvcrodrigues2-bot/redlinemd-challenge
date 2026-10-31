<div align="center">

[🇺🇸 English](./README.md) · [🇧🇷 Português](./README.pt-BR.md) · **🇪🇸 Español**

# RedlineMD — Rediseño de landing page

### Reto de diseño mobile-first orientado a la conversión

**UX/UI · Implementación web responsiva · Estrategia de conversión**

[Vista previa en Vercel](https://redlinemd-challenge.vercel.app/) · [Perfil de Marcus Castro](https://github.com/marcuscastrodev)

</div>

> **Reto de diseño independiente**, realizado para un proceso de selección de web designer; no es el sitio oficial de RedlineMD. Las decisiones descritas son hipótesis de UX basadas en el briefing, **no mejoras de conversión medidas**.

## Resumen

| | |
| --- | --- |
| **Contexto** | Prueba de diseño web para Foundey |
| **Objetivo** | Mejorar claridad, confianza y compra móvil de un servicio de revisión de contratos médicos |
| **Mi trabajo** | UX, dirección visual, interfaz responsiva e interacciones |
| **Entrega** | Concepto interactivo empaquetado en `index.html` |
| **Estado** | Vista previa publicada, sin A/B test real ni checkout de producción |

## El reto

Según el briefing, **el 35 % de las visitas eran móviles, pero el escritorio generaba más del 90 % de los ingresos**. Esto sugería una posible diferencia de conversión sin confirmar su causa.

Los visitantes de Google Ads necesitaban entender qué ofrece el servicio, cuánto cuesta, qué ocurre después de enviar el contrato y por qué confiar en el proceso.

## Enfoque de diseño

```text
Intención de búsqueda → Oferta y precio claros
                     → Importancia de revisar el contrato
                     → Informe interactivo ilustrativo
                     → Una acción principal
```

### 01 — Mensaje claro

Título alineado con la búsqueda de revisión de contratos médicos, precio cerca del CTA y propuesta directa.

### 02 — Menos distracciones

Una oferta prioritaria, botones consistentes y navegación reducida.

### 03 — Demostrar el valor

Informe de muestra con riesgos, cláusulas y propuestas de cambios. Los ejemplos son **ilustrativos**, no asesoramiento legal real.

### 04 — Experiencia móvil

Oferta visible desde el inicio, barra condicional, objetivos táctiles diseñados para 44 px o más y lectura simplificada del informe.

### 05 — Reducir la fricción

El concepto incluye una interacción para añadir el contrato. **La demostración no carga ni procesa archivos.**

## Sistema visual

| Elemento | Dirección |
| --- | --- |
| Azul marino | `#172B46`, base profesional |
| Rojo | `#D42A2F`, botones y alertas |
| Tipografía | Geist y Geist Mono |
| Secciones | Alternancia de fondos claros y oscuros |
| Detalles | Bordes y sombras sutiles; títulos en sentence case |

## Galería

**01 — Portada escritorio:** propuesta, comparación de precios, CTA e informe.

![RedlineMD escritorio](screenshots/01-hero-desktop.webp)

**02 — Portada móvil:** navegación y jerarquía adaptadas.

<img src="screenshots/02-hero-mobile.webp" alt="RedlineMD en móvil" width="360" />

**03 — Riesgos contractuales:** tarjetas educativas sobre los riesgos.

![Riesgos contractuales](screenshots/03-contract-risks.webp)

**04 — Informe interactivo:** cláusulas, alertas y sugerencias ilustrativas.

![Informe de ejemplo](screenshots/04-sample-report.webp)

## Accesibilidad e implementación

El diseño contempla estructura semántica, foco visible, preferencias de movimiento reducido, contraste, objetivos táctiles y metadatos SEO. **No implica una auditoría o certificación completa de accesibilidad.**

## Código y ejecución

El [archivo HTML](./index.html) es una exportación empaquetada con runtime integrado, no el código original organizado en componentes. Puede abrirse en un navegador con JavaScript.

La [vista previa de Vercel](https://redlinemd-challenge.vercel.app/) figura en el repositorio, pero su funcionamiento actual no se ha comprobado independientemente.

## Aspectos pendientes

- Medir la conversión con analítica y experimentos A/B.
- Aclarar la discrepancia del briefing entre entrega “instantánea” y “en 24 horas”.
- Implementar checkout y carga real de archivos con medidas de privacidad.
- Validar jurídicamente los ejemplos del informe.
- Completar pruebas de accesibilidad y dispositivos.
- Publicar el código fuente editable si está disponible.

---

**Diseñado y documentado por [Marcus Castro](https://github.com/marcuscastrodev)**.
