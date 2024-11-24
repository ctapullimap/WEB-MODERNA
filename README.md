# Web Moderna

## Autor

**Carlos Martin Tapullima Pezo**  
*Fundamentals Software Development*  
📧 [ctapullima73@gmail.com](mailto:ctapullima73@gmail.com)  
🗓️ 23/11/2024

- Sobre el Proyecto

## "La Web Moderna" es una iniciativa que explora las tecnologías y prácticas actuales en el desarrollo web. Este proyecto aborda las últimas tendencias y herramientas que definen la construcción de aplicaciones web contemporáneas, incluyendo

- Arquitecturas modernas de frontend y backend
- Frameworks y bibliotecas JavaScript de última generación
- Prácticas de diseño responsivo y experiencia de usuario
- Optimización de rendimiento y mejores prácticas de desarrollo
- Integración de APIs y servicios modernos
- Implementación de Progressive Web Apps (PWA)

- El objetivo es proporcionar una visión completa y práctica de cómo se construyen las aplicaciones web en la actualidad, siguiendo los estándares y metodologías más recientes de la industria.

## Explicación del archivo `.eslintrc.json`

- El archivo `.eslintrc.json` configura ESLint para aplicar ciertas reglas y establecer un estándar en el código. A continuación, se detalla cada línea del archivo proporcionado:

``json
{
  "env": {
    "browser": true,
    "es2021": true
  },
  "extends": ["eslint:recommended"],
  "parserOptions": {
    "ecmaVersion": "latest",
    "sourceType": "module"
  },
  "rules": {
    "indent": ["error", 2],
    "linebreak-style": ["error", "unix"],
    "quotes": ["error", "single"],
    "semi": ["error", "always"],
    "no-unused-vars": "warn",
    "no-console": "warn"
  }
}

## Explicación línea por línea del archivo `.eslintrc.json`

### `"env"`  

Define los entornos en los que el código se ejecutará.  

- `"browser": true`: Permite las variables globales disponibles en navegadores, como `window` y `document`.  
- `"es2021": true`: Habilita características de ECMAScript 2021, como operadores lógicos avanzados y nuevos métodos.  

### `"extends"`  

- `["eslint:recommended"]`: Usa las reglas básicas recomendadas por ESLint, como detección de errores comunes y mejores prácticas.  

### `"parserOptions"`  

Configura cómo ESLint analiza el código.  

- `"ecmaVersion": "latest"`: Permite utilizar las características más recientes de ECMAScript.  
- `"sourceType": "module"`: Permite el uso de módulos ES6, es decir, `import` y `export`.  

### `"rules"`  

Define reglas personalizadas para el análisis del código.  

- `"indent": ["error", 2]`: Obliga a usar una indentación de 2 espacios. Si no se cumple, se genera un error.  
- `"linebreak-style": ["error", "unix"]`: Fuerza el uso de saltos de línea estilo Unix (`\n`). Esto es útil para mantener la consistencia entre sistemas operativos.  
- `"quotes": ["error", "single"]`: Obliga a usar comillas simples (`'`) en lugar de comillas dobles.  
- `"semi": ["error", "always"]`: Exige que todas las líneas terminen con un punto y coma (`;`).  
- `"no-unused-vars": "warn"`: Muestra una advertencia si hay variables declaradas pero no usadas en el código.  
- `"no-console": "warn"`: Genera una advertencia cuando se usa `console.log` u otros métodos de consola. Esto es útil para evitar dejar mensajes de depuración en el código final.  

### Conclusión  

Este archivo garantiza que el código siga estándares consistentes, previniendo errores comunes y promoviendo buenas prácticas.

## Despliegue

[link de Github](https://github.com/ctapullimap)
