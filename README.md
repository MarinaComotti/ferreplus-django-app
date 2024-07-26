# Ferreplus Django App

<img src="./media/home/banner/ferreplus_3.jpg" alt="cells" style="max-width: 969px; height: 300px; display: block; margin: auto;">



Este proyecto fue desarrollado como trabajo de evaluación en equipo para la cátedra de **Ingeniería de Software II** de la **Facultad de Informática (Universidad Nacional de La Plata)**. El mismo tuvo como objetivo desarrollar todas las actividades y etapas que involucran un proyecto, desde la comunicación con el cliente y la elicitación de requerimientos (con entrevistas, cuestionarios y armado de Historias de Usuario), hasta el desarrollo y la evaluación del producto. 

El trabajo consistió en desarrollar una aplicación web solicitada por un cliente (ficticio) dueño de Ferreplus, una cadena de ferreterías. Esta aplicación esta destinada a tres tipos de usuarios: los clientes, los empleados y un administrador. Los clientes, una vez registrados, tienen la posibilidad de publicar productos propios para intercambiar con otros usuarios, acceder al catálogo de productos del negocio y pagar para aumentar la visibilidad de sus publicaciones. Por otro lado, los empleados pueden registrar los trueques y las compras llevadas a cabo por los clientes, así como también penalizarlos por comportamiento inapropiado dentro de la aplicación. Por último, el administrador tiene la posibilidad de regristrar empleados, administrar sucursales, manejar el catálogo de productos y acceder a una sección de análisis de datos con métricas relevantes para el negocio. 
La idea fué propuesta por los docentes de la cátedra, quienes tomaron el rol del cliente que "contrata" al equipo para la creación del software.

A lo largo de todo el proceso se aplicó la metodología ágil **Scrum** y se utilizó la herramienta de gestión de proyectos **Pivotal Tracker**. 
La aplicación web fué construída con el framework **Django**. También se utilizó **Bootstrap**, **CSS**, **HTML** y **JavaScript**. 


### Instalación:
```
    # Clonar el repositorio:
    git clone https://github.com/MarinaComotti/ferreplus-django-app.git

    # Ir al directorio principal:
    cd ferreplus-django-app/

    # Instalar las dependencias: :
    pip install -r requirements.txt

    # Aplicar las migraciones a la base de datos:
    python manage.py makemigrations
    python manage.py migrate

    # Crear los grupos de usuarios:
    python manage.py create_user_groups
```

### Uso:

```
    # Iniciar aplicación:
    python manage.py runserver

    # Acceder desde el navegador:
    http://localhost:8000
```

### Equipo de desarrollo:

* [Marina Comotti](https://github.com/MarinaComotti)
* [Martina Mendizabal](https://github.com/MartiMendizabal)
* [Manuel Diaz](https://github.com/Numa-diazdiva)
* [Javier Ballesteros](https://github.com/javierb30)


