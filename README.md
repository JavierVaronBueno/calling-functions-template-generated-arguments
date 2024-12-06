# Analizador de Datos con SQLite y Pandas Mediante Modelos de Conocimiento

Este proyecto combina la potencia de SQLite como base de datos ligera con las capacidades de procesamiento de datos de Pandas. Diseñado como una herramienta flexible para analizar y manipular datos, su estructura modular permite ampliar funcionalidades mediante conceptos clave de interacción con modelos de conocimiento. Demostraremos cómo ejecutar funciones cuyas entradas se generan mediante modelos y cómo usar esto para implementar un agente que pueda responder nuestras preguntas sobre una base de datos.

## Descripción

El objetivo de este proyecto es proporcionar una base sólida para análisis de datos:
- Uso de bases de datos SQLite para almacenamiento y consultas eficientes.
- Uso de Pandas para procesar y analizar datos estructurados.
- Compatibilidad con flujos de trabajo reproducibles en Jupyter Notebook.

Además, este proyecto está alineado con buenas prácticas para extender funcionalidades mediante bibliotecas avanzadas.

## Funcionalidades principales

1. **Interacción con bases de datos SQLite**:
   - Conexión y manipulación de datos directamente desde Python.
   - Ejecución de consultas SQL dinámicas.

2. **Procesamiento avanzado con Pandas**:
   - Transformaciones de datos.
   - Limpieza y análisis exploratorio.

3. **Extensibilidad**:
   - Estructura preparada para integraciones con APIs o modelos de conocimiento.

## Requisitos

1. Python 3.8 o superior.
2. Las siguientes bibliotecas:
   - `os`
   - `pandas`
   - `sqlite3`
   - `pathlib`
   - `IPython`

3. Jupyter Notebook.

## Configuración e instalación

### 1. Clonar el repositorio

```bash
git clone https://github.com/JavierVaronBueno/calling-functions-template-generated-arguments.git
cd calling-functions-template-generated-arguments
```

### 2. Crear y activar un entorno virtual

```bash
python -m venv venv
```

- **Linux/Mac**:
  ```bash
  source venv/bin/activate
  ```
- **Windows**:
  ```bash
  venv\Scripts\activate
  ```

### 3. Instalar dependencias

```bash
pip install -r requirements.txt
```

### 4. Instalar Jupyter Notebook

```bash
pip install notebook
```

## Estructura del proyecto

```plaintext
analisis-datos-sqlite/
├── real_estate_analyzer.ipynb        # Notebook principal
├── venv/                             # Entorno virtual
├── requirements.txt                  # Dependencias del proyecto
└── README.md                         # Documentación
```

## Ejecución

1. Inicia Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

2. Abre el archivo `real_estate_analyzer.ipynb`.

3. Sigue las instrucciones dentro del notebook para ejecutar el flujo.

## Licencia

Este proyecto está bajo la licencia MIT.
