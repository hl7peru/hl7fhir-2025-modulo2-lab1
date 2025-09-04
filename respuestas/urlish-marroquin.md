# Respuestas - Urlish Marroquin

## ¿Qué información devuelve el servidor?
El servidor devuelve un recurso de tipo Bundle, que contiene en su interior una lista de recursos Patient. Estos pacientes cumplen con el criterio de búsqueda: que en alguno de sus nombres contenga el valor "John".

## ¿Qué campos del recurso Patient se observan?
- resourceType: "Patient" → Indica el tipo de recurso, en este caso Paciente.
- id: "38100" → Indica el identificador interno del paciente en el servidor.
- meta: -> Indica la información técnica del recurso.
    + versionId: "6" -> Indica la versión del registro.
    + lastUpdated": "2022-04-01" -> Indica la fecha de la ultima actualización.
    + source: "#W1Jd7uh91KLzZXsV" -> Indica la fuente.
- text: -> representación narrativa en XHTML.
    + status: "generated" -> Indica el estado del registro.
    + div: "6" -> Indica el resumen del registro en texto.
- identifier: Indica el identificador del paciente dentro del sistema.
    + type.coding.system: "http://hl7.org/fhir/v2/0203" -> Indica el sistema del identificador.
    + type.coding.code: "MR" -> Indica el código del identificador.
    + value: "537b0c24-4e55-45a7-a0dd-516290e6b055" -> Indica el valor único del identificador.
- name: Indica los datos del nombre completo del paciente.
    + family → "Wang": Indica el apellido del paciente.
    + given → "John": Indica el nombre del paciente.
- birthDate: "1988-01-18" → Indica la fecha de nacimiento del paciente.
- search → Indica la búsqueda del paciente.
- mode: "match" → Indica el método de búsqueda del paciente.