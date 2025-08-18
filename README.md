# NTT Data Config Repo

Este repositorio contiene los **archivos de configuración externos** de los microservicios del Bootcamp de Microservicios (NTT Data - Cibertec).  
Es consumido por el [Config Server](https://github.com/ArturoRoncal2704/nttdata-config-serve) para centralizar las propiedades de la aplicación.

---

## Descripción
Las configuraciones de los microservicios no están embebidas en el código, sino en este repositorio.  
De esta forma, cada servicio puede leer sus propiedades desde el **Config Server** en tiempo de ejecución.
