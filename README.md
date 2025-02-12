# 📊 Prueba Técnica - Talend Open Studio

## 📌 Descripción
Este proyecto contiene un **Job de Talend Open Studio** que realiza un **proceso ETL** para cargar datos en una base de datos MySQL.

## 📂 Archivos incluidos
- `Carga_Datos_Almacen.zip` → Exportación del Job en Talend.
- `Inventario.csv` → Archivo 1 de datos usado en la ETL.
- `Movimiento_almacen.csv` → Archivo 1 de datos usado en la ETL.

## 🛠 Requisitos
Antes de ejecutar el Job, asegúrate de tener instalado:
- **Talend Open Studio**
- **MySQL** (base de datos `talend_test` ya creada)
- **Git** (opcional)

## 🚀 Pasos para ejecutar el Job
### 1️⃣ **Importar el Job en Talend**
1. Abre **Talend Open Studio**.
2. Ve a **File** → **Import Item**.
3. Selecciona el archivo `Carga_Datos_Almacen.zip` y haz clic en **Finish**.

### 2️⃣ **Configurar la conexión a MySQL**
1. Asegúrate de que MySQL está en ejecución.
2. Modifica los parámetros en `tDBConnection` dentro del Job:
   ```plaintext
   Host: 127.0.0.1
   Puerto: 3306
   Base de datos: talend_test
   Usuario: root
   Contraseña: 123456789
