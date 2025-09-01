# Respuestas - Pedraza

## ¿Qué información devuelve el servidor?
Al hacer la consulta al enlace, el servidor responde con un script en formato JSON. Este archivo contiene un objeto llamado "Bundle", que agrupa varios recursos de tipo "Patient". Cada uno de estos recursos representa a un paciente cuyos datos coinciden con el nombre "John".

## ¿Qué campos del recurso Patient se observan?
se identificaron los siguentes campos:
1. id
2. meta
    2.1 versionId
    2.2 lastUpdated
    2.3 source
3.text
    3.1 status
    3.2 status
4. name
    4.1 family
    4.2 given
5. gender
6. search
    6.1 mode 
