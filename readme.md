# Preprocesadores CSS y HTML

En este repositorio, están algunos archivos de práctica usando preprocesadores como: PUG, SASS, LESS y STYLUS.

## Documentación PUG (Preprocesador HTML)

Lo puedes encontrar en el siguiente [Link](https://pugjs.org/api/getting-started.html)

## Documentación SASS (Preprocesador CSS)

Lo puedes encontrar en el siguiente [Link](https://sass-lang.com/documentation/)

## Documentación STYLUS (Preprocesador CSS)

Lo puedes encontrar en el siguiente [Link](https://stylus-lang.com/)

## Documentación LESS (Preprocesador CSS)

Lo puedes encontrar en el siguiente [Link](https://lesscss.org/)

## ¿Cómo practicar con estos preprocesadores?

Posiblemente aún desconozcas cómo se usa herramientas como React, Next, Angular etc., y desees practicar un poco con estos preprocesadores.

La forma de trabajar con estos, es ejecutando un comando en la terminal, y convertir esos archivos de preprocesadores a lo deseado, ya sea HTML o CSS.

**Nota importante; debes tener instalado [Node.js](https://nodejs.org/en/) en la PC para usar npm**

### Convertir .pug a .html

**Instalación:**

```bash
npm install pug-cli -g
```

**Conversión:**

```bash
pug -w --pretty fileName.pug
```

### Convertir .less a .css

**Instalación:**

```bash
npm install less -g
```

**Conversión:**

```bash
lessc ruta/del/archivo.less ruta/de/salida.css
```

### Convertir .sass o .scss a .css

**Instalación:**

```bash
npm install sass -g
```

**Conversión:**

```bash
sass --watch ruta/del/archivo.scss ruta/de/salida.css
```

### Convertir .styl a .css

**Instalación:**

```bash
npm install stylus -g
```

**Conversión:**

```bash
stylus -w ruta/del/archivo.styl
```
