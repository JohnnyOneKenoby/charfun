# Proyecto Charfun - Verificador de Palíndromos

Este proyecto consiste en un script en Python que permite verificar si una frase es un **palíndromo**. Un palíndromo es una palabra o frase que se lee igual en ambos sentidos, ignorando espacios, puntuación y diferencias entre mayúsculas y minúsculas.

##  Objetivos del Proyecto

- Crear una función que determine si una cadena es palíndroma.
- Solicitar una frase al usuario y analizarla.
- Realizar pruebas de aceptación mediante `unittest`.

##  Tecnologías Utilizadas

- **Lenguaje:** Python 3
- **Entorno de desarrollo:** PyCharm Community Edition 2024.2.3
- **Testing:** Framework de pruebas `unittest` incluido por defecto en Python
- **Control de versiones:** Git

##  Estructura del proyecto

```bash
proyecto-charfun/
│
├── charfun.py             # Script principal
├── test_charfun.py        # Pruebas unitarias
└── README.md              # Documentación del proyecto
```

## Instalación y ejecución

1. Clona o descarga este repositorio en tu máquina.
2. Asegúrate de tener **Python 3** instalado.
3. Ejecuta el script principal:

```bash
python charfun.py
```

4. Ejecuta las pruebas unitarias con:

```bash
python -m unittest test_charfun.py
```

## Casos de prueba contemplados

- Frases claramente palíndromas:
  - "Anita lava la tina"
  - "Amo la pacífica paloma"
  - "La ruta natural"
  - "12321"

- Frases que no son palíndromas:
  - "Hola mundo"
  - "Esto no es un palíndromo"

- Casos límite:
  - Cadena vacía: ""
  - Solo símbolos o caracteres especiales: "!!!"
  - Palíndromos con puntuación: "A man, a plan, a canal, Panama"

## Autor

**Juan Antonio Gálvez Arévalo**

Estudiante del módulo "Puesta en Producción Segura", Ciclo de Especialización en Ciberseguridad.

## Licencia

Este proyecto se distribuye bajo la licencia MIT. Puedes usarlo, modificarlo y distribuirlo libremente, siempre que mantengas la atribución del autor original.

