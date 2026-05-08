# Sistema de Gestión de Citas Médicas

Un sistema web desarrollado en Python con Flask para la gestión y administración de citas médicas.

## Características

- Autenticación de usuarios
- Gestión de citas médicas
- Búsqueda y filtrado de registros
- Panel de control con gráficos
- Gestión de pacientes
- Sistema de actualización de datos

## Requisitos Previos

- Python 3.8+
- MySQL
- pip (gestor de paquetes de Python)

## Instalación

### 1. Clonar el repositorio

```bash
git clone <URL_DEL_REPOSITORIO>
cd GestionCitasMedicasREAL/sistemaplana
```

### 2. Crear un entorno virtual

```bash
# En Windows
python -m venv venv
venv\Scripts\activate.bat

# En macOS/Linux
python3 -m venv venv
source venv/bin/activate
```

### 3. Instalar las dependencias

```bash
pip install -r requirements.txt
```

### 4. Configurar la base de datos

- Crear una base de datos MySQL
- Configurar las credenciales en `src/bd.py`

### 5. Ejecutar la aplicación

```bash
cd src
python app.py
```

La aplicación estará disponible en `http://localhost:5000`

## Credenciales de Prueba

- **Usuario:** 123
- **Contraseña:** 123

## Estructura del Proyecto

```
sistemaplana/
├── src/
│   ├── app.py                 # Aplicación principal
│   ├── bd.py                  # Configuración de base de datos
│   ├── Model/                 # Modelos de datos
│   ├── rutas/                 # Rutas y controladores
│   ├── templates/             # Plantillas HTML
│   └── static/                # Archivos estáticos (CSS, JS, imágenes)
├── requirements.txt           # Dependencias del proyecto
└── Requerimientos.txt        # Instrucciones de configuración
```

## Tecnologías Utilizadas

- **Backend:** Flask
- **Base de Datos:** MySQL
- **Frontend:** HTML, CSS, JavaScript
- **ORM:** SQLAlchemy
- **Validación:** Marshmallow

## Dependencias Principales

- Flask 2.3.2
- Flask-SQLAlchemy 3.0.3
- PyMySQL 1.0.3
- Flask-APScheduler 1.12.4
- Marshmallow 3.19.0

## Desarrollo

### Estructura de Carpetas

- `Model/` - Contiene los modelos de datos (plana.py, registro.py, validar.py)
- `rutas/` - Contiene los controladores (home.py, formulario.py, buscador.py, etc.)
- `static/` - Archivos CSS, JavaScript e imágenes
- `templates/` - Plantillas HTML

### Rutas Principales

- `/` - Inicio de sesión
- `/home` - Panel de control
- `/formulario` - Formulario de registro
- `/buscador` - Búsqueda de citas
- `/grafico` - Panel de gráficos

## Licencia

Este proyecto es de uso interno.

## Autor

Desarrollado por el equipo de desarrollo.

---

Para más información, consultar la documentación en la carpeta `Documentacion Del Proyecto/`
