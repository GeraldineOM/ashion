# Ashion | Tienda de moda

Réplica de la página principal de la tienda de moda **Ashion**, desarrollada para el examen de Programación 4.

**Autora:** Geraldine Herrera Rodríguez
**Sitio publicado:** https://ashion-geraldine.netlify.app

## Tecnologías

- HTML5 semántico (`header`, `nav`, `main`, `section`, `article`)
- CSS3 con metodología **BEM** (`bloque__elemento--modificador`)
- **Bootstrap 5.3** para la rejilla responsive y el menú colapsable
- Bootstrap Icons y Google Fonts (Cookie y Montserrat)

## Estructura

```text
ashion/
├── index.html
├── css/
│   └── styles.css
├── img/
│   ├── women.svg
│   ├── men.svg
│   ├── kids.svg
│   ├── cosmetics.svg
│   └── accessories.svg
└── README.md
```

## Bloques BEM

| Bloque | Elementos | Modificadores |
|---|---|---|
| `header` | `__navbar`, `__container`, `__logo`, `__menu`, `__link`, `__actions`, `__account`, `__icon`, `__badge`, `__toggler` | `__link--active` |
| `categories` | `__item`, `__text`, `__title`, `__count`, `__description`, `__link`, `__img` | `__item--large`, `__item--women`, `__item--men`, `__item--kids`, `__item--cosmetics`, `__item--accessories`, `__title--script`, `__text--large` |

## Responsive

| Dispositivo | Ancho | Distribución |
|---|---|---|
| PC | ≥ 992 px | Tarjeta principal a la izquierda (`col-lg-6`) y rejilla 2 × 2 a la derecha |
| Tablet | 576 – 991 px | Tarjeta principal arriba y categorías en 2 × 2 (`col-sm-6`); menú colapsado |
| Celular | < 576 px | Todas las tarjetas en una columna; menú colapsado |
