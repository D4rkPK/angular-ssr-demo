````markdown
# Angular 17 Server Side Rendering (SSR) Demo

Este repositorio contiene los pasos básicos para configurar una demo de Server Side Rendering (SSR) en Angular 17 utilizando Angular Universal.

## Requisitos previos

Asegúrate de tener Node.js y npm instalados en tu máquina.

```bash
# Instalar Angular CLI globalmente
npm install -g @angular/cli
```

## Crear un nuevo proyecto de Angular

```bash
# Crear un nuevo proyecto de Angular
ng new my-ssr-project
```

## Configuración de SSR

Navega al directorio del proyecto.

```bash
cd my-ssr-project
```

Agrega Angular Universal a tu proyecto.

```bash
ng add @nguniversal/express-engine
```

## Ejecución con SSR

Para ejecutar la aplicación Angular con SSR, utiliza el siguiente comando:

```bash
npm run dev:ssr
```

## Construcción para producción

Para construir el proyecto para producción, ejecuta:

```bash
npm run build:ssr
```

## Servir el proyecto de producción

Para servir el proyecto de producción, utiliza:

```bash
npm run serve:ssr
```
Estos pasos te ayudarán a configurar una demo básica de SSR en Angular. Para una implementación más detallada y personalizada, modifica tu aplicación de acuerdo a tus necesidades específicas.

