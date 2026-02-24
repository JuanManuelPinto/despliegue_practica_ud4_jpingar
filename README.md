# Proyecto de Despliegue - UD4
**Autor:** Juan Manuel Pinto Garrucho
**Fecha:** Febrero 2026

## 1. Entorno de Servidor
* **Servidor Web:** Apache (XAMPP) / Nginx (Linux)
* **Versión PHP:** 8.2.12
* **Acceso SFTP:** Configurado para usuario `dev_junior` y `dev_senior`
* **IP (Local):** 127.0.0.1 

## 2. Configuración de Red
* **Dominio Backend:** `backend.test` -> Resolviendo a 127.0.0.1
* **Dominio Frontend:** `frontend.test` -> Resolviendo a 127.0.0.1
* **Dominio SGBD:** `bd.test` -> Resolviendo a 127.0.0.1

## 3. Instrucciones de Despliegue
1. **Clonación:** Clonar el repositorio desde el servidor Git mediante `git clone https://github.com/JuanManuelPinto/despliegue_practica_ud4_jpingar.git`.
2. **Transferencia:** Mover los archivos mediante SFTP (usando FileZilla o VS Code) a la carpeta `htdocs`

## 4. Historial de Versiones (Ciclo de Vida)
* **v1.0:** Inicialización del repositorio y subida de la Práctica 1 (UD4).
* **v1.1:** Actualización con el archivo PDF de la Práctica 2 (UD4).
* **v1.2:** Creación de rama `fix-styles`, creaciónd de fichero de prueba con contenido y fusión con `main`. Se incluye archivo `fichero_fix_styles.txt`.