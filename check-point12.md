# ¿Qué significa UML?

**Respuesta:**  
UML significa *Unified Modeling Language* (Lenguaje Unificado de Modelado). Es un lenguaje de modelado estandarizado utilizado para visualizar, especificar, construir y documentar los artefactos de un sistema de software.

---

# ¿Por qué usamos UML?

**Respuesta:**  
Usamos UML para:
1. **Visualizar:** Representar gráficamente la estructura y comportamiento de un sistema.
2. **Especificar:** Detallar los componentes de un sistema y sus interacciones.
3. **Construir:** Guiar la implementación del sistema con modelos precisos.
4. **Documentar:** Crear documentación clara y comprensible para desarrolladores, clientes y otros interesados.

## Beneficios de UML

- **Comunicación clara:** Proporciona una representación gráfica estandarizada, facilitando la comunicación entre todos los miembros del equipo.
- **Planificación y diseño:** Ayuda a planificar y diseñar sistemas complejos antes de la implementación, reduciendo errores.
- **Flexibilidad:** Permite modelar diferentes aspectos del sistema, desde su estructura hasta su comportamiento.

## ¿Cuándo y por qué utilizar UML?

**Cuándo:**  
UML es útil en todas las fases de desarrollo de software, especialmente en:
- **Análisis y diseño:** Para comprender y diseñar el sistema antes de comenzar a codificar.
- **Documentación:** Para mantener una referencia clara del sistema durante todo su ciclo de vida.

**Por qué:**  
- Para asegurar que todos los involucrados comprendan el diseño del sistema.
- Para reducir ambigüedades y errores durante el desarrollo.
- Para facilitar el mantenimiento y la actualización del sistema en el futuro.

### Ejemplo: Diagrama de Clases

```plaintext
+------------------+
|     Persona      |
+------------------+
| - nombre: String |
| - edad: int      |
+------------------+
| + saludar(): void|
+------------------+
         ^
         |
+------------------+
|     Estudiante   |
+------------------+
| - carrera: String|
+------------------+
| + estudiar(): void|
+------------------+
```

# Ejemplos de Diagramas Estructurales

1. ### Diagrama de Clases
2. ### Diagrama de Componentes
3. ### Diagrama de Estructura Compuesta
4. ### Diagrama de Despliegue
5. ### Diagrama de Paquetes


# Ejemplos de Diagramas de Comportamiento
1. ### Diagrama de Casos de Uso
2. ### Diagrama de Secuencia
3. ### Diagrama de Actividades
4. ### Diagrama de Estados
5. ### Diagrama de Colaboración
   

# Ejemplo: Diagrama de Secuencia
```
Usuario      Sistema      Base de Datos
  |             |                |
  |   Iniciar   |                |
  |------------>|                |
  |             |   Validar      |
  |             |--------------->|
  |             |                |
  |             |   Respuesta    |
  |<------------|                |
  |  Acceso     |                |
  |------------>|                |
  |             |                |
```



# ¿Qué es el enrutamiento RESTful?

## Respuesta:

### El enrutamiento RESTful es un enfoque en el diseño de APIs (Interfaz de Programación de Aplicaciones) que sigue los principios de la arquitectura REST (Representational State Transfer). Se organiza en torno a recursos y utiliza métodos HTTP como GET, POST, PUT, y DELETE para realizar operaciones sobre estos recursos.

## Beneficios del enrutamiento RESTful:

1. Estructura coherente: Facilita la comprensión y uso de la API al seguir una convención predecible.
2. Escalabilidad: Permite escalar la API de manera efectiva, gracias a su diseño modular y basado en recursos.
3. Compatibilidad: Es compatible con HTTP, lo que facilita la integración con otras tecnologías web.
   
## Ejemplo: Enrutamiento RESTful
```HTTP GET /usuarios
    |
    v
Recupera una lista de usuarios

HTTP POST /usuarios
    |
    v
Crea un nuevo usuario

HTTP PUT /usuarios/1
    |
    v
Actualiza el usuario con ID 1

HTTP DELETE /usuarios/1
    |
    v
Elimina el usuario con ID 1
```