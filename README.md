# IABD

## Creación de entornos virtuales

- Instalar python desde la [Microsoft Store](https://apps.microsoft.com/detail/python-310/9PJPW5LDXLZ5?hl=es-es&gl=ES)
- Crear entorno virtual
~~~
python -m venv environment_1
~~~
- Entrar en el entorno virtual
 ~~~
environment_1\Scripts\activate
~~~
- Instalar una dependencia
~~~
pip install pandas
~~~
- Listar dependencias
~~~
pip list
~~~
| **Dependencias del entorno 1** | **Dependencias del entorno 2** |
|----------|----------|
| ![image](https://github.com/Romera02rrs/IABD/assets/76781930/70bdf2ba-4402-413e-ac1f-8a9e3fb7aaae) | ![image](https://github.com/Romera02rrs/IABD/assets/76781930/2ae8a1e4-a9e9-4c08-bc9f-12ca9af41187)

- Salir del entorno
~~~
deactivate
~~~

## Pros y contras de los difetentes creadores de entornos
| Ventajas                          | Entornos Locales | Anaconda | Google Colab |
|----------------------------------|:----------------:|:--------:|:------------:|
| Acceso a recursos locales        |        ✓         |          |              |
| Personalización completa         |        ✓         |          |              |
| Gestión de paquetes flexible     |        ✓         |          |              |
| Facilita la colaboración        |                  |          |       ✓      |
| Gestión de paquetes simplificada |                  |    ✓     |              |
| Compatibilidad con múltiples sistemas |             |    ✓     |              |
| Entornos preconfigurados         |                  |          |       ✓      |
| Compartir entornos con colegas   |                  |    ✓     |              |


| Desventajas                       | Entornos Locales | Anaconda | Google Colab |
|-----------------------------------|:----------------:|:--------:|:------------:|
| Configuración inicial más complicada |      ✓         |          |              |
| Potencial de conflictos de versiones |      ✓         |    ✓     |              |
| Dificultad en la colaboración    |      ✓         |          |              |
| Requiere espacio en disco        |                  |    ✓     |              |
| Algunos recursos compartidos     |                  |    ✓     |       ✓      |
| Sin acceso a recursos locales    |                  |          |       ✓      |
| Dependencia de conexión a internet |               |          |       ✓      |
| Recursos compartidos limitados   |                  |          |       ✓      |

