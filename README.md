# 🚗 API de Gestión de Vehículos - Spring Boot

API REST desarrollada con Spring Boot que permite gestionar información de vehículos mediante operaciones CRUD (Crear, Leer, Actualizar y Eliminar), con persistencia en base de datos MySQL.

---

## 📌 Descripción

Este proyecto permite administrar vehículos almacenando información como marca, modelo, año y características adicionales.
Fue desarrollado para practicar el diseño de APIs REST y la integración con bases de datos relacionales.

---

## 🚀 Funcionalidades

* 📄 Listado de vehículos
* ➕ Registro de nuevos vehículos
* ✏️ Actualización de información
* ❌ Eliminación de registros
---

## 🛠 Tecnologías utilizadas

* Java
* Spring Boot
* Spring Data JPA
* MySQL (MySQL Workbench)
* Maven
* Insomnia (pruebas de API)

---

## 🧠 Arquitectura

El proyecto está estructurado en capas:

* **Controller:** Exposición de endpoints REST
* **Service:** Lógica de negocio
* **Repository:** Acceso a base de datos
* **Entity:** Representación de la tabla vehículos

---

## 🌐 Endpoints principales

| Método | Endpoint        | Descripción                 |
| ------ | --------------- | --------------------------- |
| GET    | /vehiculos      | Obtener todos los vehículos |    
| POST   | /vehiculos      | Crear nuevo vehículo        |
| PUT    | /vehiculos/{id} | Actualizar vehículo         |
| DELETE | /vehiculos/{id} | Eliminar vehículo           |

---

## ▶️ Cómo ejecutar el proyecto

1. Clonar el repositorio:

```bash id="zz9q0r"
git clone https://github.com/Sebas-avila-hash/-Sistema-de-Seguros-para-Vehiculos

```

2. Abrir en IDE (IntelliJ, VS Code)

3. Configurar base de datos en:

```properties id="w8i3m9"
src/main/resources/application.properties
```

Ejemplo:

```properties id="9h8qcm"
spring.datasource.url=jdbc:mysql://localhost:3306/vehiculos_db
spring.datasource.username=root
spring.datasource.password=tu_password
spring.jpa.hibernate.ddl-auto=update
```

4. Ejecutar la aplicación

---

## 🧪 Pruebas de la API

Los endpoints fueron probados utilizando:

* Insomnia

Ejemplo de JSON:

```json id="0dld4c"
{
    "placa": "ABC123",
    "marca": "Toyota",
    "modelo": "Corolla",
    "anio": 2025,
    "color": "blanco",
    "conductor": 2,
    "seguro": "SEG001"
}

```

---

## 📷 Evidencia de funcionamiento

### 🔹 Obtener vehículos (GET)
![GET](https://github.com/user-attachments/assets/47a6d7f0-969a-4046-bf71-f7251f792b7f)

---

### 🔹 Crear vehículo (POST)

![POST](https://github.com/user-attachments/assets/e9aafca9-c693-4dee-98a2-b2447d2be4ea)

---

### 🔹 Actualizar vehículo (PUT)

![PUT](https://github.com/user-attachments/assets/462bc956-6f5a-40d0-9ad0-52b361710279)

---

### 🔹 Eliminar vehículo (DELETE)

![DELETE](https://github.com/user-attachments/assets/dec5861e-ce58-4a68-824d-d0bd195e888f)

---

### 🔹 Base de datos (MySQL)

![BD](https://github.com/user-attachments/assets/38649391-ccd9-46db-b6dd-b4cdf5b18f46)

---

## 🧠 Aprendizajes

* Desarrollo de APIs REST con Spring Boot
* Implementación de CRUD completo
* Persistencia de datos con MySQL
* Uso de JPA y repositorios
* Pruebas de endpoints con Insomnia

---

## 👨‍💻 Autor

Desarrollado por **Thomas Avila**

🔗 https://github.com/Sebas-avila-hash
