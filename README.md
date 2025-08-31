# 🧪 Laboratorio 1: Consulta de un recurso Patient en HL7 FHIR

Bienvenido al **Ejercicio 1** del curso de HL7 FHIR.  
En este laboratorio aprenderás a realizar consultas básicas a un servidor FHIR público usando el recurso **Patient**.

### ✅ Objetivo de la práctica
- Aprender a interactuar con un servidor **FHIR**.  
- Identificar los principales campos del recurso **Patient**.  
- Practicar el flujo de trabajo con **GitHub** y **Pull Requests**.  
- Aprender ek uso básico de Postman. Se ha cargado un manual en la plataforma de e-learning.


### 📚 Recursos de apoyo

- [Documentación HL7 FHIR R4](https://hl7.org/FHIR/R4/)
- [HAPI FHIR Test Server](https://hapi.fhir.org/baseR4)

---

## 📌 Ejercicio 1: Consulta de un recurso

1. Accede al servidor de prueba de HL7 FHIR:  
   👉 [https://hapi.fhir.org/baseR4](https://hapi.fhir.org/baseR4)

2. Realiza una búsqueda de pacientes filtrando por nombre.  

    👉 Abre **Postman** y sigue estos pasos:

- Método: **GET**  
- URL:  https://hapi.fhir.org/baseR4/Patient?name=John


    📌 Luego de ejecutar la consulta, revisa la respuesta en formato JSON.



3. Responde las siguientes preguntas:

    📌 ¿Qué información devuelve el servidor?

    📌 ¿Qué campos del recurso Patient se observan en la respuesta?

📂 Instrucciones para entregar la tarea:

1. Haz un fork de este repositorio en tu cuenta de GitHub.

2. Clona tu repositorio forkeado en tu computadora:

```bash
git clone https://github.com/TU-USUARIO/hl7fhir-lab1-patient.git
```

3. Crea una nueva rama con tu nombre:

```bash
git checkout -b respuesta-NOMBRE
```

4. Crea un archivo en la carpeta respuestas/ con tu nombre

Ejemplo:
```bash
respuestas/juan-perez.md
```

5. En ese archivo responde las preguntas del ejercicio.

Formato sugerido:

```bash
# Respuestas - Juan Pérez

## ¿Qué información devuelve el servidor?
_(escribe tu explicación aquí)_

## ¿Qué campos del recurso Patient se observan?
_(escribe tu explicación aquí)_

```

6. Sube tus cambios:
```bash
git add .
git commit -m "Respuestas de Juan Pérez - Ejercicio 1"
git push origin respuesta-NOMBRE
```

7. Desde GitHub, crea un Pull Request (PR) hacia este repositorio original.


