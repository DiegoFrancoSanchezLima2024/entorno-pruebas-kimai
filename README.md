# Entorno de Pruebas Kimai para Presentación ASVS

Este repositorio contiene la infraestructura de **Kimai** (un sistema de gestión y control de horas de trabajo) para nuestra demostración de ASVS.

## Instrucciones para levantar la aplicación (Infraestructura)

1. Deben tener instalado [Docker](https://www.docker.com/products/docker-desktop).
2. Clonen este repositorio (si es que no lo han hecho): `git clone [URL_DE_TU_REPOSITORIO]`
3. Entren a la carpeta del repositorio y abran una terminal.
4. Ejecuten el siguiente comando para levantar la infraestructura:
   ```bash
   docker-compose up -d
   ```
5. Abran su navegador y vayan a: `http://localhost:8000`

### Primer acceso
Una vez que cargue la aplicación, Kimai te permitirá registrar el primer usuario que quedará configurado como **Super Administrador**.

¡Listo! Ya tienen el sistema de gestión corriendo en su propia máquina para hacer las pruebas y la demostración de ASVS.
