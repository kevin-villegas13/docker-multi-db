# Docker Multi Database

Este repositorio contiene configuraciones de Docker Compose para múltiples bases de datos, permitiendo levantar entornos de desarrollo rápidamente.

## 📌 Bases de datos disponibles
- **PostgreSQL**
- **SQL Server**

## 🚀 Instalación y uso

1. Clona este repositorio:
   ```sh
   [git clone https://github.com/kevin-villegas13/docker-multi-db.git](https://github.com/kevin-villegas13/docker-multi-db.git)
   cd docker-multi-db
   ```

2. Navega a la base de datos que necesitas y levántala:
   ```sh
   cd postgres
   docker-compose up -d
   ```
   O para SQL Server:
   ```sh
   cd sqlserver
   docker-compose up -d
   ```

3. Accede a la base de datos desde tu aplicación o herramienta de administración.

4. Para detener y eliminar los contenedores:
   ```sh
   docker-compose down
   ```

## 🛠 Contribuir

Si deseas agregar una nueva base de datos o mejorar las configuraciones existentes:

1. **Fork** este repositorio.
2. Crea una nueva carpeta con el nombre de la base de datos.
3. Agrega un `docker-compose.yml` y una breve documentación.
4. Abre un **Pull Request** con tus cambios.

## 📜 Licencia
Este proyecto está bajo la licencia MIT. ¡Úsalo libremente! 😃
