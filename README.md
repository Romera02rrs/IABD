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

## Anaconda

Una vez instalado el programa, buscamos la opción de Notebook de Jupiter y hacemos clic sobre "Launch"
![image](https://github.com/Romera02rrs/IABD/assets/76781930/e22a086f-936d-4e2f-85c1-ae50ba9b95d9)

Se nos abrirá un localhost donde tendremos nuestro sitema de ficheros local, para crear un nuevo notebook debemos de hacer click en "New" > "Python 3 (ipykernel)"
![image](https://github.com/Romera02rrs/IABD/assets/76781930/bca24e1f-07a6-43ce-8c29-2d315a2b17c9)

Por último, podemos crear un celda con nuestro codiog de python y ejecutarla haciendo click en "Run" o presionando las teclas "Control" + "Enter"
![image](https://github.com/Romera02rrs/IABD/assets/76781930/2ed31478-3b29-4815-8529-54475dc106e8)




