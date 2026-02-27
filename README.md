# nyan-army-web

Proyecto de demos de Nyan Cat (horizontal, vertical, combinado y colisiones) montado sobre **Vite**.

## Requisitos

- Node.js 18+
- npm

## Desarrollo local

```bash
npm install
npm run dev
```

## Build de producción

```bash
npm run build
npm run preview
```

## Páginas disponibles

- `/` → demo principal
- `/nyancat.html` → varios gatos en direcciones opuestas
- `/nyancat-vertical.html` → movimiento vertical
- `/nyancat-combined.html` → horizontal + vertical
- `/nyancat-collision.html` → colisiones múltiples
- `/nyancat-collision-diagonal.html` → colisiones con cola diagonal

---

## Si vas a crear **un proyecto nuevo en Vite** y copiar esta funcionalidad

### 1) Crear proyecto base

```bash
npm create vite@latest nyan-army-web -- --template vanilla
cd nyan-army-web
npm install
```

### 2) Copiar estos archivos en la **raíz** del nuevo proyecto

Copia desde este repo al nuevo proyecto los siguientes archivos:

- `index.html`
- `nyancat.html`
- `nyancat-vertical.html`
- `nyancat-combined.html`
- `nyancat-collision.html`
- `nyancat-collision-diagonal.html`
- `nyan-sprite.svg`
- `nyan-trail.svg`
- `nyan-cat-only.svg`
- `nyancat.svg`
- `vite.config.js`

> Importante: conserva exactamente esos nombres y ubicación (raíz), porque las páginas referencian SVGs con rutas relativas.

### 3) Reemplazar `package.json`

Usa este bloque mínimo:

```json
{
  "name": "nyan-army-web",
  "version": "1.0.0",
  "private": true,
  "type": "module",
  "scripts": {
    "dev": "vite",
    "build": "vite build",
    "preview": "vite preview"
  },
  "devDependencies": {
    "vite": "^5.4.11"
  }
}
```

### 4) Instalar y ejecutar

```bash
npm install
npm run dev
```

Con eso tendrás la misma funcionalidad en tu repo nuevo.
