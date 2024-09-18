# Cursos - Aplicación para Gestión de Cursos y Docentes

## Descripción

Esta aplicación está diseñada para gestionar cursos y docentes. Utiliza Spring Boot para el desarrollo del backend y MySQL como base de datos. 

## Requisitos

- **Java**: 21 o superior
- **Maven**: 3.6.0 o superior
- **MySQL**: Base de datos MySQL 8.0 o superior

## Instalación

### 1. Clonar el Repositorio

Primero, clona el repositorio a tu máquina local:

```bash
git clone https://github.com/tuusuario/cursos.git
cd cursos

Configuración de la Base de Datos****
CREATE DATABASE cursosdb;


Configuración de la Aplicación

spring.datasource.url=jdbc:mysql://localhost:3306/cursosdb
spring.datasource.username=root
spring.datasource.password=
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true



