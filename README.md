# Salud-Vida-Plus

Proyecto fnal de herramientas computacionales

## Proposito
Este proyecto es una plataforma web desarrollada en Django para la gestión de pacientes, citas y servicios médicos dentro de una IPS. Su objetivo es optimizar procesos internos y mejorar el acceso a la información.

## ⚙️ Instalación
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/Ronny-Morelo/Salud-Vida-Plus.git
   ```

2. Entrar a la carpeta del proyecto:
```bash
    cd proyecto_final
```

3.Crear entorno virtual:
```bash
  python -m venv venv
```

4. Activar entorno:
   - Windows:
   ```bash
   venv\Scripts\activate
   ```
   - Linux/Mac:
   ```bash
   source venv/bin/activate
   ```

5. Instalar dependencias:
 ```bash
   pip install -r requirements.txt
 ```

7. Configurar variables de entorno (.env):
 ```bash
   SECRET_KEY=tu_clave
   DB_NAME=nombre_db
   DB_USER=usuario
   DB_PASSWORD=contraseña
   DB_HOST=localhost
   DB_PORT=3306
 ```

8. ▶️ Ejecución
    ```bash
   python manage.py runserver
 ```
