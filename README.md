# taller_bases_de_datos

Script en Python que automatiza la creación y poblado de una base de datos MySQL con 100.000 registros usando SQLAlchemy y Faker.

## Requisitos

- Python 3.10+
- MySQL
- DBeaver

## Instalación

1. Clona el repositorio:
   git clone https://github.com/danielchavarria-prog/taller_bases_de_datos.git

2. Instala las dependencias:
   pip install -r requirements.txt

3. Crea un archivo .env basado en .env.example y completa tus credenciales de MySQL.

## Uso

python main.py

## Estructura de la tabla

La tabla `personas_daniel` contiene los siguientes atributos:

- id (PK)
- nombre
- apellido
- correo
- fecha_nacimiento
- ciudad
- pais
- telefono
- profesion
