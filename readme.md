# OpenCatalogueAPI

## Descripción

OpenCatalogueAPI es una API basada en Django para gestionar un catálogo de recursos. Este proyecto proporciona una interfaz para CRUD (Crear, Leer, Actualizar, Eliminar) operaciones en el catálogo, diseñada para ser utilizada por aplicaciones frontend o integraciones de terceros.

## Requisitos

- Python 3.12
- venv

## Instalación

Sigue estos pasos para configurar el entorno de desarrollo:

1. **Clonar el Repositorio**

   Clona este repositorio en tu máquina local:

   ```bash
   git clone https://github.com/Kuzan-dev/opencatalogue-api
   cd opencatalogue-api

2. **Crear el Entorno venv**

   Crea un entorno venv:

   ```bash
   python -m venv venv

3. **Activar el Entorno**

   Activa el entorno venv recién creado:

   ```bash
   .\venv\Scripts\activate

4. **Instalar Dependencias**

   Puedes instalar las dependencias usando pip:

   ```bash
   pip install -r requirements.txt

5. **Migraciones de Base de Datos**

   Aplica las migraciones para configurar la base de datos:

   ```bash
   python manage.py migrate

6. **Ejecutar el Servidor de Desarrollo**

   Inicia el servidor de desarrollo de Django:

   ```bash
   python manage.py runserver
  
La API estará disponible en http://127.0.0.1:8000/.


